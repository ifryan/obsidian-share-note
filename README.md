# Share Note

Free, encrypted public note sharing for Obsidian.

## Features

- All note data is encrypted on the server. The decryption key is provided to you with the share link, and is never sent to the server at any point.
- Uploads using your current theme.
- Local and remote image support.
- Supports anything that Obsidian Preview mode does, like rendered Dataview queries and any custom CSS you might have enabled.
- Supports callouts with full styling.
- If your shared note links to another note which is also shared, that link will also function on the public page.
- Frontmatter is stripped on upload by default to avoid leaking unwanted data.

## Setup

I have a server set up to host the shared notes. This is a free service for Obsidian users, as I already had the server and the costs to me are negligible.

Connect your plugin by clicking the "Connect plugin" button on the Settings page.

## Usage

Use the `Share Note` command from the Command Palette. You can map it to a hotkey to make things faster.

The first time a file is shared, the plugin will automatically upload all your theme styles. The next time you share a file, it will use the previously uploaded theme files. 

If you want to force the theme CSS to update, use the command `Force re-upload of all data for this note`.

## Attributions

Encryption code is based with thanks on code from https://github.com/mcndt/obsidian-quickshare
