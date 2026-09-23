# obsidian-onedrive-sync

Built releases of an Obsidian plugin that keeps one vault in step with one folder in a
work OneDrive, on iPhone as well as desktop. It signs in through Microsoft's own page
(authorization code with PKCE), asks for the signed-in person's own files only, and talks
to nothing but Microsoft.

This repository holds releases, not source: `manifest.json` here tells
[BRAT](https://github.com/TfTHacker/obsidian42-brat) the current version, and each
release carries the plugin's `main.js` and `manifest.json`. It works only for accounts
the organisation has assigned to it.

## Install

1. Obsidian → Settings → Community plugins → Browse → **BRAT** → Install, Enable.
2. BRAT → **Add beta plugin** → `advancedhomehealth/obsidian-onedrive-sync` → Add.
3. Enable **Azure Sync**, then Settings → Azure Sync → **Sign in**.

On iPhone, keep the vault **On My iPhone** (not in iCloud): this plugin is its sync.
