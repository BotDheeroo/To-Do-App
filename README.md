# ToDo List

A premium, mobile-first ToDo List web app with a classic graphite-and-champagne interface. Organize work into Main, Learning, and Projects branches; set priorities; pin important tasks; track completion; search and filter; and export/import a JSON backup.

## Live website

After GitHub Pages is enabled, the project site will be available at:
https://botdheeroo.github.io/To-Do-App/

## Features

- Responsive layout designed for mobile and desktop
- Main, Learning, and Projects task branches
- High, normal, and low priorities
- Pin/unpin tasks to keep important work at the top
- Search tasks and filter by active, completed, or pinned status
- Mark tasks complete, reopen them, edit titles, or delete tasks
- Progress ring and task statistics
- Activity history stored with the app data
- JSON backup export and import
- Local browser storage; no account required

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Add a task using the bar at the bottom of the page.

## Repository files

- `index.html` — complete web app (HTML, CSS, and JavaScript).
- `Available_doing_list.json` — starter/reference structure for active tasks and branches.
- `Available_doing_work.json` — starter/reference list for pinned tasks.
- `Done_work_list.json` — starter/reference list for completed tasks.
- `History_add_delete.json` — starter/reference activity history.
- `.nojekyll` — tells GitHub Pages to serve the static files directly.

The JSON files are clean starter/reference files. The running app stores its live data in the browser's local storage; use **Export JSON** to save the current app data.

## Enable GitHub Pages

Open **Settings → Pages** in this repository. Under **Build and deployment**, choose **Deploy from a branch**, select branch **main** and folder **/(root)**, then click **Save**. GitHub Pages can take a few minutes to publish after configuration.

## Privacy and limitations

Tasks stay in the browser on the current device. Clearing browser site data may remove them, so export a backup regularly. This is a web app, not an APK.
