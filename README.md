## VS Code Setup (Extensions + Requirements)

### Requirements
- **Neovim (required for VSCode Neovim)**
  - Install on macOS (Homebrew):
    ```bash
    brew install neovim
    ```
  - Verify it’s installed:
    ```bash
    nvim --version
    ```
  - My config points VS Code to Neovim here:
    - `/opt/homebrew/bin/nvim`

> Tip: If your `nvim` lives somewhere else, update:
> `vscode-neovim.neovimExecutablePaths.darwin`

---

### Installed Extensions
- **C/C++** (Microsoft)  
  IntelliSense, debugging, and C/C++ language support.

- **CMake Tools** (Microsoft)  
  CMake configure/build integration inside VS Code.

- **C/C++ Themes** (Microsoft)  
  UI themes that complement the C/C++ extension.

- **C/C++ Extension Pack** (Microsoft)  
  Bundle of popular C++ development extensions.

- **Live Share** (Microsoft)  
  Real-time collaborative editing / sharing sessions.

- **Tokyo Night Dark** (Andrew X. Shah)  
  Color theme (VS Code appearance).

- **VSCode Neovim** (Alexey Svetliakov)  
  Uses Neovim as the editing engine inside VS Code (requires `nvim` installed).

---

### Key Settings I Use (Optional)
- Hide tabs + disable preview tabs (reduces UI clutter)
- Disable minimap
- Autosave after a short delay
- Zen Mode tweaks (centered layout, hide status bar)
- `jk` in insert mode: **escape + save** (via vscode-neovim composite keys)
