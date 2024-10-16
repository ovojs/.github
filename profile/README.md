## The Map of OvO 🦉

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

OvO is maintained in two [monorepos](https://monorepo.tools):

- `ovo` - OvO Runtime & Toolchain [github.com/ovojs/ovo](https://github.com/ovojs/ovo)
  - `ovo`      - All-in-one CLI     (Rust) 
  - `ovo-core` - JavaScript runtime (QuickJS + Rust)
  - `ovo-qdb`  - Debugger           (QuickJS debugger + Rust)
  - `ovo-lsp`  - Language server    (Rust)
  - `ovo-gui`  - Cross-platform GUI framework  (LVGL + Rust)
 
- `platform` - OvO Platform [github.com/ovojs/platform](https://github.com/ovojs/platform)
  - `api`  - API server     - [api.ovojs.com](https://api.ovojs.com)
  - `dash` - Dashboard      - [dash.ovojs.com](https://dash.ovojs.com)
  - `docs` - Documentations - [docs.ovojs.com](https://docs.ovojs.com)
  - `play` - Playground     - [play.ovojs.com](https://play.ovojs.com)
 
Goals and design may vary before the first release.
