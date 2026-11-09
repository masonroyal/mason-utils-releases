# Mason Utils (releases)

Boards and dashboard blocks for Obsidian: roadmap and planning boards, `files-created` and `periodic-cards` code blocks, and automatic dates in frontmatter. It's built for one person's vault, so some of its labels are in Chinese and some conventions are specific to that setup.

This repo holds the release builds. The source is developed in a separate private repo, so issues here may not get a reply.

## Install with BRAT

1. In Obsidian, install and enable **BRAT** from Community plugins.
2. In BRAT's settings, choose **Add beta plugin**.
3. Enter `masonroyal/mason-utils-releases` and pick the latest version.
4. Enable **Mason Utils** under Community plugins.

No GitHub token is needed. BRAT can keep the plugin up to date from here.

## What it writes to your notes

While the plugin is enabled, editing a note can change that note's frontmatter:

- A note with `type: project` gets missing `started` and `completed` dates, based on its status.
- A note with `type: thread` gets the current month added to `active-months`. You can change these stamping rules in settings.

## Install by hand

Download `main.js`, `manifest.json` and `styles.css` from the latest release into `<your vault>/.obsidian/plugins/mason-utils/`, then enable the plugin.

This is beta software. Back up your vault before trying it.
