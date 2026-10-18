# ToDo List

A mobile-first to-do list web app with a premium dark interface, restrained glassmorphism, task management, pinned work, branch organization, optional voice input, activity history, and JSON backup import/export.

## Run on your phone
1. Download and extract this ZIP.
2. Open `index.html` in a modern browser (Chrome recommended).
3. Tap **Add a task** to create your first task. The app starts with an empty task list.

## Files
- `index.html` — app interface and logic.
- `Available_doing_list.json` — empty active-task structure and default branches.
- `Available_doing_work.json` — empty pinned-work list.
- `Done_work_list.json` — empty completed-task list.
- `History_add_delete.json` — empty activity history.

## Data storage
The app stores working data in browser local storage. The JSON files are clean starter/reference files and are not automatically loaded as live storage. Use **More → Export JSON backup** to export the data currently in the app. Voice input depends on browser support and microphone permission.

## GitHub Pages
Upload the extracted files to the repository root, then open **Settings → Pages** and configure deployment from your chosen branch and `/` folder.

This is a responsive web app, not an APK.