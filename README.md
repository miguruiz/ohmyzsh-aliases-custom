# espanso-and-aliases plugin

This is a copy of ohmyzsh plugin [@aliases](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aliases) with additional customization for displaying espanso text expander shorcuts and adding some aliases.

# Aliases cheatsheet

To use it:

1. git clone https://github.com/miguruiz/ohmyzsh-espanso-and-aliases.git $ZSH_CUSTOM/plugins/espanso-and-aliases
2. add `espanso-and-aliases` to the plugins array in your zshrc file:
```zsh
plugins=(... espanso-and-aliases)
```

Requirements: 
- Python needs to be installed.
- [Espanso](https://espanso.org/) 

## Usage

- `als`: show all aliases by group

- `als -h/--help`: print help message

- `als <keyword(s)>`: filter and highlight aliases by `<keyword>`

- `als -g <group>/--group <group>`: show only aliases for group `<group>`. Multiple uses of the flag show all groups

- `als --groups`: show only group names

  ![screenshot](https://github.com/ohmyzsh/ohmyzsh/assets/66907184/5bfa00ea-5fc3-4e97-8b22-2f74f6b948c7)

  ## TODO
  - `make espanso optional`