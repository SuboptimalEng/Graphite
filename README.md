### ⚠️ This repo is for demo purposes only ⚠️

### ⚠️ Don't use Graphite to edit local files ⚠️

---

# ✍️ Graphite - [Video Explanation](https://www.youtube.com/watch?v=Z8ufG29c0_A)

### A local-first Markdown note-taking app built with Vue.js, Tailwind, and Electron.

- In 2020, I quit my tech job to focus on creating web development tutorials on [YouTube](youtube.com/SuboptimalEng).
- After spending a few months playing around with different technologies, I decided to focus on Vue + Tailwind.
- In order to test how far I've come with the tech stack, I made Graphite, a local-first markdown note-taking app.
- Note: I built Graphite in ~1 week so don't mind the code quality or lack of tests.

### Demo GIF (takes a few seconds to load)

<img src="/demo/_graphite.gif" width="600">

### Images

#### Dracula Theme

<img src="/demo/00_dracula.png" width="600">

#### Gruvbox Theme

<img src="/demo/00_gruvbox.png" width="600">

#### Monokai Theme

<img src="/demo/00_monokai.png" width="600">

#### File Search

<img src="/demo/02_file_search.png" width="600">

#### Markdown Preview

<img src="/demo/03_md_preview.png" width="600">

### 💻 Tech Stack

- Stack
  - [Vue.js](https://vuejs.org/)
  - [Vuex](https://vuex.vuejs.org/) (state management)
  - [Electron](https://www.electronjs.org/) (desktop apps ftw)
  - [Tailwind CSS](https://tailwindcss.com/) (UI framework)
- Libraries
  - [Marked](https://marked.js.org/) (convert markdown to html)
  - [CodeMirror](https://codemirror.net/) (builing your own editor is hard)
  - [Hotkeys](https://github.com/jaywcjlove/hotkeys/) (makes keyboard shortcuts easy)

### Feature Set

- Basic
  - Add/remove/rename/move files
  - Markdown preview
  - CodeMirror editor
- Keybindings
  - Open file search -> `command + o`
  - Close file search -> `esc`
  - Toggle sidebar -> `command + b`
- Configurable Themes with CSS Variables
  - Dracula
  - Gruvbox
  - Monokai
- TODO
  - WYSIWYG
  - Add/remove/rename/move folders
  - Watch for file changes in Electron and persist changes automatically
  - Actually release a desktop app for Mac/Windows/Linux
