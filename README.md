## General Key Bindings
Key bindings that work in MacOS/browsers
Happen to be same as Emacs (some website like Gmail overwrite with own shortcuts)
```
Lines
C-a             beginning-of-line
C-e             end-of-line
C-n             next-line
C-p             previous-line
C-k             kill-line
C-o             open-line
Cmd DEL         Delete to beginning of line

Words
⌥ f             forward-word
⌥ b             backward-word
⌥ d             kill-word
⌥ DEL           backward-kill-word

Characters
C-f             forward-char
C-b             backward-char
C-d             delete-char
DEL             delete-backward-char
C-t             transpose-chars

Undo
Cmd-u

⌥ = Alt = Meta
```
## VS Code Shortcuts
```
⌥ z             Toggle wrap-lines
```
### Pylance Import Problems
In `.vscode` set `"python.analysis.useImportHeuristic": true`

Alternative: add `"python.analysis.extraPaths": ["./sources"]` with link to path with modules.

## Favourite browser extensions
- **Vimium**: enables browser navigation by keyboard

## MacOS productivity tools
- **Paste**: provides searchable clipboard history 

## Fish setup on Mac
- Switch iTerm color profile: https://stackoverflow.com/a/43018512/7483211
- Set Fish as default:
```
echo /usr/local/bin/fish | sudo tee -a /etc/shells
chsh -s /usr/local/bin/fish
```
- Install `fisher`
- Read https://switowski.com/blog/favorite-cli-tools

- Copy over .config files

- Settings:
    - AWS off
    - Ayu mirage as theme
    - Starship prompt
    - iTerm Pastel > better is snazzy
    - brew tap homebrew/cask-fonts
    - brew install --cask font-fira-code-nerd-font
    - fzf
    - gitalias: https://github.com/GitAlias/gitalias
    - fd
    - ripgrep
    - glances
    - https://switowski.com/blog/favorite-cli-tools


