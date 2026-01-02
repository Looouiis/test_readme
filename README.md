# Dependency
You can set up the development environment using either of the following methods:
1.  **Recommended**: Ensure you have **`nix-shell`** available in your environment, and enter the Nix shell directly.
    ```bash
    nix-shell
    ```
        > **Note**: You should run all subsequent commands within this shell environment.
2.  **Alternative**: Manually install the packages listed in `shell.nix`.

# Running the Project
The project uses `just` as a command runner. You can execute the following commands from any path within this project.

| Command | Description |
| :--- | :--- |
| `just run` | Builds and runs the project directly with QEMU. |
| `just gdb` | Launches a `tmux` session and starts the GDB CLI for debugging. |
