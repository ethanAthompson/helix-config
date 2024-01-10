# Helix Config

## This is my helix config that I use currently.

### Custom Theme:
  * transparent + gruvbox_dark_hard
  
### Snippets:
  * html_template!
  * cmake_template!
### Setup: Libraries
  * [the-way](https://github.com/out-of-cheese-error/the-way?tab=readme-ov-file#why-the-way) 
  * [Leptos Format](https://github.com/bram209/leptosfmt)
  ```toml
    [[language]]
    name = "rust"
    auto-format = true
    formatter = { command = "leptosfmt" , args = ["--stdin"] }
    language-servers = ["rust-analyzer", "tailwindcss-ls"]

    [language-server.rust-analyzer.config]
    config = { procMacro = { ignored = { leptos_macro = [
      # Optional:
      # "component",
      "server",
    ] } } }
  ```


  
### How do I use snippets?
  1. press : key
  2. type insert-output
  3. press space key
  4. type the name of snippet

 ![image](https://github.com/ethanAthompson/helix-config/assets/140981795/7a22d4d7-c4fd-41c0-a8fe-934881d4ed26)
