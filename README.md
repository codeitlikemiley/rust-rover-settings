# Rust Rover IDE (MacOS Settings)

> Better workflow , testing and debugging capability on your Next Rust Projects


<details>
  <summary>
    <a href="https://github.com/codeitlikemiley/rust-rover-settings/raw/main/rust-rover-settings.zip">
      <strong>1. Download and Import rust-rover-settings.zip</strong>
    </a>
  </summary>
  <img src="import_settings.png" alt="Alt text" />
</details>

<details>
<summary>
2. Install  Plugins
</summary>

- IdeaVim
- IdeaVim-Sneak
- Whichkey
- .env file support
- Better highlights
- Github Copilot

</details>


<details>
  <summary>3. Load `codeitlikemiley` keymap</summary>

![Alt text](keymap.png)

</details>

#### 4. [Download ideavimrc](https://github.com/codeitlikemiley/rust-rover-settings/blob/main/.ideavimrc)

> Move the Downloaded file to your Home Directory `~/.ideavimrc`

#### 5. Learn The Keymap The Easy Way

<details>
  <summary>Keybindings for Tool Windows</summary>

### <strong>Upper Left SideBar Keybindings</strong>

![Alt text](upper-sidebar.png)

<kbd>CMD</kbd> + <kbd>F1</kbd> === `Tool Windows: Project`

<kbd>CMD</kbd> + <kbd>F2</kbd> === `Tool Windows: Structure`

<kbd>CMD</kbd> + <kbd>F3</kbd> === `Tool Windows: Bookmarks`

<kbd>CMD</kbd> + <kbd>F4</kbd> === `Tool Windows: TODO`

<kbd>CMD</kbd> + <kbd>F5</kbd> === `Refresh Cargo Projects`


### <strong>Right SideBar Keybindings</strong>

![Alt text](right-sidebar.png)

<kbd>CMD</kbd> + <kbd>F12</kbd> === `Tool Windows: Notifications`

<kbd>CMD</kbd> + <kbd>F11</kbd> === `Tool Windows: Cargo`

<kbd>CMD</kbd> + <kbd>F10</kbd> === `Tool Windows: Database`

<kbd>CMD</kbd> + <kbd>F9</kbd> === `Tool Windows: Github Co-pilot`


### <strong>Lower Left SideBar Keybindings</strong>

![Alt text](lower-sidebar.png)

<kbd>OPT</kbd> + <kbd>C</kbd> === `Tool Windows: Commit`

<kbd>OPT</kbd> + <kbd>D</kbd> === `Tool Windows: Debug`

<kbd>OPT</kbd> + <kbd>G</kbd>=== `Tool Windows: Git`

<kbd>OPT</kbd> + <kbd>B</kbd> === `Tool Windows: Build`

<kbd>OPT</kbd> + <kbd>R</kbd> === `Tool Windows: Run`

<kbd>OPT</kbd> + <kbd>P</kbd> === `Tool Windows: Problems`

<kbd>CMD</kbd> + <kbd>TILDA</kbd> === `Tool Windows: Terminal`

</details>

<details>
<summary>
<strong>Fn Keys</strong>
</summary>
Mainly used for refactoring and documentation

| Keyboard Shortcuts | Description     |
| -------------- | ------------------- |
| <kbd>F1</kbd>  | Quick Documentation |
| <kbd>F2</kbd>  | Rename              |
| <kbd>F3</kbd>  | Refactor this       |
| <kbd>F4</kbd>  | Change Signature    |
| <kbd>F5</kbd>  | Refactor: Copy      |
| <kbd>F6</kbd>  | Refactor: Move      |

</details>

<details>
<summary>
<strong>Rust Runnables</strong>
</summary>

| Keyboard Shorcuts                            | Description               |
| -------------------------------------------- | ------------------------- |
| <kbd>CMD</kbd>+<kbd>R</kbd>                  | Run Context Configuration |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>R</kbd> | Re-Run                    |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>P</kbd> | Run Cargo Command         |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>F</kbd> | Format RSX                |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>V</kbd> | Html to RSX               |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>N</kbd> | New Cargo Crate           |

</details>


<details>
<summary>
<strong>Debugging</strong>
</summary>

| Keyboard Shorcuts                            | Description                 |
| -------------------------------------------- | --------------------------- |
| <kbd>CMD</kbd>+<kbd>T</kbd>                  | Debug Context Configuration |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>T</kbd> | Stop                        |
| <kbd>CMD</kbd>+<kbd>D</kbd>                  | Resume Program              |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>D</kbd> | Toggle Breakpoint           |
| <kbd>CMD</kbd>+<kbd>L</kbd>                  | Step Into                   |
| <kbd>CMD</kbd>+<kbd>H</kbd>                  | Step Out                    |
| <kbd>CMD</kbd>+<kbd>J</kbd>                  | Step Over                   |
| <kbd>CMD</kbd>+<kbd>K</kbd>                  | Run to Cursor               |

</details>

<details>
<summary>
<strong>Errors / Warning</strong>
</summary>

| Keyboard Shortcut                             | Description                        |
| --------------------------------------------- | ---------------------------------- |
| <kbd>OPT</kbd>+<kbd>P</kbd>                   | Tool Windows -> Problems           |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>P</kbd>  | Run Rust External Linter           |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>I</kbd>  | Inspect Code with Editor Settings  |
| <kbd>CMD</kbd>+<kbd>E</kbd>                   | Next Highlighted Error             |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>E</kbd>  | Previous Highlighted Error         |
| <kbd>HYPER</kbd>+<kbd>CMD</kbd>+<kbd>J</kbd>  | Jump to Source                     |
| <kbd>HYPER</kbd>+<kbd>CMD</kbd>+<kbd>K</kbd>  | Jump to Navigation bar             |

</details>


<details>
<summary>
<strong>Auto Complete</strong>
</summary>

| Keyboard Shortcut                             | Description                     |
| --------------------------------------------- | ------------------------------- |
| <kbd>OPT</kbd>+<kbd>,</kbd>                   | Cyclic Expand Word Backward     |
| <kbd>OPT</kbd>+<kbd>.</kbd>                   | Cyclic Expand Word              |
| <kbd>CTRL</kbd>+<kbd>Space</kbd>              | Basic                           |
| <kbd>CTRL</kbd>+<kbd>SHIFT</kbd>+<kbd>Space</kbd> | Type Matching           |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>Enter</kbd>  | Complete Current Statement  |
| <kbd>TAB</kbd>                                | Insert Inline Proposal          |

</details>

<details>
<summary>
<strong>Code Generations</strong>
</summary>

| Keyboard Shortcut                             | Description         |
| --------------------------------------------- | ------------------- |
| <kbd>OPT</kbd>+<kbd>O</kbd>                   | Override Methods    |
| <kbd>OPT</kbd>+<kbd>I</kbd>                   | Implement Methods   |
| <kbd>OPT</kbd>+<kbd>G</kbd>                   | Generate            |

</details>

<details>
<summary>
<strong>Quickly Jump from One Place to Another</strong>
</summary>

| Keyboard Shortcut            | Description                    |
| ---------------------------- | ------------------------------ |
| <kbd>OPT</kbd>+<kbd>Z</kbd>  | Activate / Cycle AceJump Mode  |

</details>


<details>
<summary>
<strong>Multi-Cursor</strong>
</summary>

| Keyboard Shortcut                            | Description                                  |
| --------------------------------------------- | -------------------------------------------- |
| <kbd>CMD</kbd>+<kbd>]</kbd>                   | Find Next / Move to Next Occurrence          |
| <kbd>CMD</kbd>+<kbd>[</kbd>                   | Find Previous / Move to Previous Occurrence |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>]</kbd>  | Unselect Previous Occurrence                |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>[</kbd>  | Add Selection for Next Occurrence           |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>\\</kbd> | Select All Occurrence                       |

</details>


<details>
<summary>
<strong>GoTo</strong>
</summary>

| Keyboard Shortcut                                       | Description                    |
| ------------------------------------------------------- | ------------------------------ |
| <kbd>CMD</kbd>+<kbd>U</kbd> or <kbd>gd</kbd> (Vim)      | Go to Declaration or Usages    |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>U</kbd>            | Find Usages                    |
| <kbd>CMD</kbd>+<kbd>I</kbd>                             | Go to Implementations          |
| <kbd>CMD</kbd>+<kbd>Y</kbd>                             | Go to Super Method             |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>Y</kbd>            | Go to Declaration Type         |
| <kbd>SHIFT</kbd>+<kbd>K</kbd> (Vim)                     | Quick Definition               |
| <kbd>F1</kbd>                                           | Quick Documentation            |
| <kbd>CMD</kbd>+<kbd>G</kbd>                             | Go to by Reference actions     |

</details>



<details>
<summary>
<strong>All About Files Search, Opening</strong>
</summary>

| Keyboard Shortcut                           | Description       |
| ------------------------------------------- | ----------------- |
| <kbd>CMD</kbd>+<kbd>F</kbd>                 | Find              |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>F</kbd>| Find in Files     |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>U</kbd>| Find Usages       |
| <kbd>CMD</kbd>+<kbd>P</kbd>                 | Search Everywhere |
| <kbd>CMD</kbd>+<kbd>O</kbd>                 | Go to Type        |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>P</kbd>| Go To Files       |
| <kbd>CTRL</kbd>+<kbd>O</kbd>                | Open Files        |

</details>


<details>
<summary>
<strong>Bookmarks</strong>
</summary>

| Keyboard Shortcut                            | Description                    |
| -------------------------------------------- | ------------------------------ |
| <kbd>CMD</kbd>+<kbd>M</kbd>                  | Go to Mnemonic                 |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>M</kbd> | Toggle Bookmark Mnemonic       |
| <kbd>CMD</kbd>+<kbd>B</kbd>                  | Show Bookmarks                 |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>B</kbd> | Toggle Bookmark / Mnemonic     |

</details>



<details>
<summary>
<strong>OPT (SHIFT) [H,J,K,L]</strong>
</summary>

#### Selection
| Keyboard Shortcut                            | Description                |
| -------------------------------------------- | -------------------------- |
| <kbd>OPT</kbd>+<kbd>H</kbd>                  | Shrink Selection           |
| <kbd>OPT</kbd>+<kbd>L</kbd>                  | Expand Selection           |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>H</kbd> | Show History for Selection |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>L</kbd> | Surround with              |

#### Moving Up and Down
| Keyboard Shortcut                            | Description         |
| -------------------------------------------- | ------------------- |
| <kbd>OPT</kbd>+<kbd>J</kbd>                  | Move Line Down      |
| <kbd>OPT</kbd>+<kbd>K</kbd>                  | Move Line Up        |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>J</kbd> | Move Statement Down |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>K</kbd> | Move Statement Up   |

</details>



<details>
<summary>
<strong>Moving Panes on Splits</strong>
</summary>

| Keyboard Shortcut                        | Description        |
| ---------------------------------------- | ------------------ |
| <kbd>CTRL</kbd>+<kbd>H</kbd>             | Move to Left Pane  |
| <kbd>CTRL</kbd>+<kbd>J</kbd>             | Move Down Pane     |
| <kbd>CTRL</kbd>+<kbd>K</kbd>             | Move to Right Pane |
| <kbd>CTRL</kbd>+<kbd>L</kbd>             | Move Up Pane       |

</details>


<details>
<summary>
<strong>Easy Tab Switching</strong>
</summary>

| Keyboard Shortcut                | Description       |
| -------------------------------- | ----------------- |
| <kbd>CMD</kbd>+<kbd>[1-9]</kbd>  | Select Tab [1-9]  |

</details>


<details>
<summary>
<strong>Comments Folding</strong>
</summary>

| Keyboard Shortcut                              | Description                |
| ---------------------------------------------- | -------------------------- |
| <kbd>CMD</kbd>+<kbd>/</kbd>                    | Comment with Line Comment  |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>/</kbd>   | Comment with Block Comment |
| <kbd>CMD</kbd>+<kbd>(-)</kbd>                  | Folding Collapse           |
| <kbd>CMD</kbd>+<kbd>(+)</kbd>                  | Folding Expand             |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>(-)</kbd> | Collapse All               |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>(+)</kbd> | Expand All                 |

</details>


<details>
<summary>
<strong>Type Hinting, Quick Fixes</strong>
</summary>

| Keyboard Shortcut                             | Description                          |
| --------------------------------------------- | ------------------------------------ |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>.</kbd>  | Parameter Info                       |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>I</kbd>  | Type Info                            |
| <kbd>CMD</kbd>+<kbd>.</kbd>                   | Show Context and Show Quick Fixes    |

</details>


<details>
<summary>
<strong>File Manipulation</strong>
</summary>

| Shortcut Keys                                  | Description       |
| ---------------------------------------------- | ----------------- |
| <kbd>CMD</kbd>+<kbd>N</kbd>                    | New File          |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>N</kbd>   | New Directory     |
| <kbd>OPT</kbd>+<kbd>N</kbd>                    | New Rust File     |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>N</kbd>   | New Crate         |

</details>



<details>
<summary>
<strong>Snippets</strong>
</summary>

| Shortcut Keys                          | Description                 |
| -------------------------------------- | --------------------------- |
| <kbd>OPT</kbd>+<kbd>F1</kbd>           | Insert Live Template        |
| <kbd>OPT</kbd>+<kbd>F2</kbd>           | Surround with Live Template |
| <kbd>OPT</kbd>+<kbd>F3</kbd>           | Save as Live Template       |

</details>

<details>
<summary>
<strong>Copy / Paste / Undo / Redo</strong>
</summary>

| Shortcut Keys                                 | Description |
| --------------------------------------------- | ----------- |
| <kbd>CMD</kbd>+<kbd>S</kbd>                   | Save all    |
| <kbd>CMD</kbd>+<kbd>X</kbd>                   | Cut         |
| <kbd>CMD</kbd>+<kbd>V</kbd>                   | Paste       |
| <kbd>CMD</kbd>+<kbd>Z</kbd>                   | Undo        |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>Z</kbd>  | Redo        |

</details>


<details>
<summary>
<strong>Copilot</strong>
</summary>

| Shortcut Keys                                 | Description                                    |
| --------------------------------------------- | ---------------------------------------------- |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>H</kbd>  | Show Previous Completions                      |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>J</kbd>  | Apply Next line of Completion to Editor        |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>K</kbd>  | Apply Next Word of Completion to Editor        |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>L</kbd>  | Show Next Completion                           |

</details>


<details>
<summary>
<strong>Notifications</strong>
</summary>

| Keyboard Shortcut                             | Description                  |
| --------------------------------------------- | ---------------------------- |
| <kbd>CMD</kbd>+<kbd>F12</kbd>                 | Tool Windows -> Notification |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>\\</kbd> | Clear all Notifications      |

</details>


<details>
<summary>
<strong>Context Menus</strong>
</summary>

| Keyboard Shortcut                             | Description          |
| --------------------------------------------- | -------------------- |
| <kbd>OPT</kbd>+<kbd>T</kbd>                   | External Tools       |
| <kbd>OPT</kbd>+<kbd>Q</kbd>                   | Select In            |
| <kbd>OPT</kbd>+<kbd>E</kbd>                   | Recent Files         |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>E</kbd>  | Recent Locations     |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>S</kbd>  | Replace in Files     |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>D</kbd>  | Debug                |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>C</kbd>  | Show Color Picker    |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>N</kbd>  | New Cargo Crate      |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>X</kbd>  | Copy Refactor        |
| <kbd>OPT</kbd>+<kbd>SHIFT</kbd>+<kbd>M</kbd>  | Show Context Menu    |

</details>


## Customizing IdeaVim Keys

check list of Actions we can bind with .IdeaVim to our Keys

```sh
:actionlist
```

We can add custom bindings to our `~/.ideavimrc`

```sh
nmap <leader>v :action Tool_External Tools_gvim<cr>
```

## Custom Keymap to Invoke External CLI Commands

This is useful e.g. , We wanna add <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>X</kbd> to format RSX in rust with Dioxus CLI

<details>
<summary>See How To do It</summary>

Open settings with CMD + ,

Go to Tools -> External Tools

Then Click (+) Sign to Create new External Tool

![Alt text](external-tools.png)

To Get the Path of Command Use which e.g.

which dx , outputs: /Users/uriah/.cargo/bin/dx

also we need to check what arguments we can use

we can run `dx --help`

```sh
dx --help
Build, Bundle & Ship Dioxus Apps

Usage: dx [OPTIONS] <COMMAND>

Commands:
  build      Build the Rust WASM app and all of its assets
  translate  Translate some source file into Dioxus code
  serve      Build, watch & serve the Rust WASM app and all of its assets
  create     Init a new project for Dioxus
  clean      Clean output artifacts
  bundle     Bundle the Rust desktop app and all of its assets
  version    Print the version of this extension
  fmt        Format some rsx
  check      Check the Rust files in the project for issues
  config     Dioxus config file controls
  help       Print this message or the help of the given subcommand(s)

Options:
  -v               Enable verbose logging
      --bin <BIN>  Specify bin target
  -h, --help       Print help
  -V, --version    Print version
```

Get `dx fmt` argurments

```sh
dx fmt --help
Format some rsx

Usage: dx fmt [OPTIONS]

Options:
  -c, --check        Run in 'check' mode. Exits with 0 if input is formatted correctly. Exits with 1 and prints a diff if formatting is required
  -r, --raw <RAW>    Input rsx (selection)
  -f, --file <FILE>  Input file
      --bin <BIN>    Specify bin target
  -h, --help         Print help
```

in order to format a file we need to use -f parameter

to get the filepath we can get it with Insert Macro

Just Click the Plus sign as shown on the image below.

![Alt text](macro.png)

We got `$FilePath$`

![Alt text](create_tool.png)

Click Insert then Go Bind the KeyMap

![Alt text](bind-dx-fmt.png)

</details>


#### Setting  Up Linear

1. Go to Settings -> Tools -> Tasks -> Server 
2. Add Server 
3. Pick Linear
4. Set:
	- Team ID e.g (COD)
	- API Key (Workspace API)
	- Workspace ID (codeitlikemiley)
5. Click Test

| Linear Keys                 | Description |
| --------------------------- | ----------- |
| <kbd>CMD</kbd>+<kbd>\\</kbd> | Open Tasks  |


<details>
<summary>
<strong>Pieces</strong>
</summary>

| Keyboard Shortcut                             | Description            |
| --------------------------------------------- | ---------------------- |
| <kbd>CMD</kbd>+<kbd>SHIFT</kbd>+<kbd>S</kbd>  | Save to Pieces         |
| <kbd>CMD</kbd>+<kbd>F9</kbd>                  | Tool Windows -> Pieces |

</details>






