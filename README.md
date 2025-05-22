# Scratch Project Loader

## Overview
[Scratch Project Loader](https://xxdakbossxx.github.io/Scratch-Project-Loader/) is a web-based tool that allows users to load and play Scratch projects using TurboWarp scaffolding. Users can enter a project ID or upload a local `.sb2` or `.sb3` file to view and interact with their Scratch projects.

## Features
- **Load Scratch Projects** via project ID or local file upload.
- **TurboWarp Integration** for smooth performance.
- **Fullscreen Support** to enhance gameplay.
- **Customizable UI** with a `noui=true` parameter to hide controls.
- **Automatic Start & Fullscreen** via URL parameters
## How to Use
1. Enter a Scratch project ID in the text field and click "Load Project."
2. Or, click "Load Project from File" to upload a `.sb2` or `.sb3` file from your computer.
3. Use the control bar to **start**, **stop**, or **toggle fullscreen mode** for the loaded project.

## URL Parameters
You can customize how projects load by adding parameters to the URL:
- `id=<project_id>` - Loads a Scratch project using its ID.
- `url=<project_link>` - Loads a project from an external file URL.
- `fullscreen` - Enables fullscreen mode automatically.
- `noui` - Hides all UI except the Scratch player.
