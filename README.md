# ⚡⚙️ My Productivity Extensions

This is a curated collection of custom-built and community-sourced extensions/plugins for Chrome, VSCode, Obsidian, and Raycast that I use every day for a lean and powerful productivity workflow.

Over time, I’ve tried countless tools and these are the essentials that stood the test of time.

## To Build or Not to Build?

In most cases, you'll find that community-built extensions cover a wide range of common workflows for mature applications. However, if your needs are highly specific, building or customizing an extension might be the best option.

### When Should You Build?

- **Niche Use Cases:**
  For example, many community AI extensions defaults to only support OpenAI API endpoints. This is a great opportunity to contribute to the community by supporting other APIs or self-hosted solutions. This trend also applies to other areas such as xloud providers, where many extensions are built for AWS APIs.

- **Learning Opportunities:**
  Building an extension is a fantastic way to learn new frameworks, APIs, and publishing processes. Who knows, you might open a new path from there?

- **Last-Mile Customization:**
  Community tools are often designed for a broad audience and can sometimes be bloated with 'unnecessary' features that you don't use. For example, I generally only use one or two key features from an extension, and I have a strong preference to access these features via keyboard shortcuts. _This is often the driving reason for me to build my own tools to adapt these tools to my workflow and not the other way around._

## 🌐 Chrome

Chrome is my go-to choice for web browsing, and most of my shortcut keys can be achieved with [davzoku/awesome-custom-search-engines](https://github.com/davzoku/awesome-custom-search-engines). The extensions are mainly to add more shortcuts or for diagnostic purposes such as analyze a website's performance and tech stack.

| Name                                                                                                                           | Description                                                     |                         Built by Me                         |
| ------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------- | :---------------------------------------------------------: |
| [Black New Tab Focus](https://chromewebstore.google.com/detail/black-new-tab-focus/picgjdlclngdpmmjhonhkkadanphjcig)           | A distraction-free new tab that keeps your focus sharp.         | [✅ Github](https://github.com/davzoku/black-new-tab-focus) |
| [Dark Reader](https://chromewebstore.google.com/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh)                           | Turns any website to dark mode. Use Option + D to toggle.       |                                                             |
| [Glimpse](https://chromewebstore.google.com/detail/glimpse-toggle-password-w/bghfjbhadcfkncomakojfpdfaodjngjj)                 | Offers quick previews of webpages to speed up content scanning. |       [✅ Github](https://github.com/davzoku/glimpse)       |
| [QuickEdit](https://chromewebstore.google.com/detail/quickedit-edit-local-page/kfgkcpcagbflnecejofneecfbcnodboh)               | Allows on-the-fly text edits directly within the browser.       |      [✅ Github](https://github.com/davzoku/quickedit)      |
| [ShareMaster](https://chromewebstore.google.com/detail/sharemaster-copy-title-ur/cglaemmecoiemahimhggkppegekpfdca)             | Formats web links to Markdown, HTML format for sharing          |     [✅ Github](https://github.com/davzoku/sharemaster)     |
| [uBlock Origin Lite](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh)             | A lean ad blocker                                               |                                                             |
| [vidiq Vision for YouTube](https://chromewebstore.google.com/detail/vidiq-vision-for-youtube/pachckjkecffpdphbpmfolblodfkgbhl) | Provides advanced insights and analytics for YouTube content    |                                                             |
| [Wappalyzer](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg)              | Checks the tech stack for websites                              |                                                             |
| [Zotero Connector](https://chromewebstore.google.com/detail/zotero-connector/ekhagklcjbdpajgpjgmbionohlpdbjgc)                 | Saves research articles to Zotero vault                         |                                                             |

## 💻 VSCode

VSCode is my primary code editor of choice. The extensions are mainly to enhance code formatting, CSV editing, and Git enhancements.

| Name                                                                                                                  | Description                                          | Built by Me |
| --------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | :---------: |
| [Black Formatter (Python)](https://marketplace.visualstudio.com/items/?itemName=ms-python.black-formatter)            | Formatter for Python                                 |             |
| [FlatlandMonokai Theme](https://marketplace.visualstudio.com/items/?itemName=gerane.Theme-FlatlandMonokai)            | My theme of choice                                   |             |
| [GitLens](https://marketplace.visualstudio.com/items/?itemName=eamodio.gitlens)                                       | Supports in-line Git Blame annotations               |             |
| [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items/?itemName=shd101wyy.markdown-preview-enhanced) | Renders Markdown files to WYSIWYG                    |             |
| [Prettier](https://marketplace.visualstudio.com/items/?itemName=esbenp.prettier-vscode)                               | Formatter for web development                        |             |
| [Rainbow CSV](https://marketplace.visualstudio.com/items/?itemName=mechatroner.rainbow-csv)                           | Syntax highlighting for CSV                          |             |
| [vscode-edit-csv](https://marketplace.visualstudio.com/items/?itemName=janisdd.vscode-edit-csv)                       | View and edit CSV in tabular format similar to Excel |             |

## 🧠 Obsidian

[Obsidian](https://obsidian.md) is my go-to tool for Personal Knowledge Management, serving as a second brain for everything from AI and software engineering to data workflows and personal productivity.

For a research-focused Second Brain workflow, check out [davzoku/paperwise](https://github.com/davzoku/paperwise) that integrates Obsidian with [Zotero](https://www.zotero.org/) and other supporting tools to streamline academic research.

| Name             | Description                                                       | Built by Me |
| ---------------- | ----------------------------------------------------------------- | :---------: |
| Citations        | Manages citations from Zotero to streamline research note-taking. |             |
| Dataview         | Create table-like views for notes                                 |             |
| Git              | Adds Git version control to track changes                         |             |
| Janitor          | Scan vault for empty notes and large files                        |             |
| Quick LaTeX      | Renders LaTeX equations in notes                                  |             |
| Recent Files     | Provides quick access to recent files                             |             |
| Style Settings   | Customizes the appearance of the vault                            |             |
| Templater        | Support template creation for note-taking                         |             |
| Vault Statistics | Adds helpful statistics in status bar                             |             |

---

## ♦️ Raycast

Raycast has emerged as my go-to productivity tool, replacing Alfred and Spotlight. It offers a powerful command palette that allows me to quickly access resources the way I prefer. With built-in features like clipboard history, Focus Session, and Quicklinks, Raycast helps me stay in flow and minimize context switching throughout the day.

I use [Karabiner Elements](https://karabiner-elements.pqrs.org/) and [Hammerspoon](https://www.hammerspoon.org/) for Hyperkey setup as I use a more advanced combination of `HyperKey` and `HyperShiftKey` in my workflow. Refer to [davzoku/dotfiles](https://github.com/davzoku/dotfiles/blob/master/macos-base/hammerspoon-app/base-init.lua) for more details.

| Name                                                                                 | Description                                                                    | Built by Me |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | :---------: |
| [Amazon AWS](https://www.raycast.com/Falcon/aws)                                     | Add Hotkey eg. `Option + CMD + A` to `Console` to access AWS resources quickly |             |
| [Apple Intelligence](https://www.raycast.com/EvanZhouDev/raycast-apple-intelligence) | Exposes Apple Intelligence such as Writing Tools as Hotkeys                    |             |
| [Brew](https://www.raycast.com/nhojb/brew)                                           | Manages Homebrew packages from Raycast                                         |             |
| [Format JSON](https://www.raycast.com/destiner/json-format)                          | Instantly formats JSON data for improved readability and quick debugging.      |             |
| [Google Gemini](https://www.raycast.com/EvanZhouDev/raycast-gemini)                  | Connects Raycast to Google Gemini via API Key as an alternative to Raycast AI  |             |
| [Kill Process](https://www.raycast.com/rolandleth/kill-process)                      | Kill apps instantly from Raycast                                               |             |
| [Port Manager](https://www.raycast.com/lucaschultz/port-manager)                     | Manages system ports from Raycast                                              |             |
| [Timers](https://www.raycast.com/ThatNerd/timers)                                    | Create timer and stopwatch with Hotkeys                                        |             |

## Suggestions

If you have any suggestions for extensions or plugins that you think I should try, feel free to reach out! I'm always looking for ways to enhance my productivity and streamline my workflow.
