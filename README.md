# `git-worktree` Scripts Repository

Welcome to the `git-worktree` repository! This repository contains two handy Bash scripts for managing Git worktrees in a more efficient and user-friendly way. Below is an overview of each script and instructions on how to use them.

## Scripts

1. **gwt (Git Worktree Add/Remove)**

   This script provides a convenient way to add or remove Git worktrees. It handles the creation of new branches and worktree paths, and also offers an option to forcefully remove worktrees and associated branches.

   ### Usage:
   ```
   ./gwt [add|remove] [branch_name] [option]
   ```

   - `add` or `remove`: Command to either add or remove a worktree.
   - `[branch_name]`: The name of the branch associated with the worktree.
   - `[option]`: Optional flag (`--force`) to forcefully remove a worktree.

   ### Features:
   - Automatically handles the creation and deletion of worktrees and branches.
   - Supports branch names with slashes.
   - Validates the existence of the `.git` directory and the Git repository's root.

2. **gwts (Git Worktrees Status)**

   This script lists all your worktrees along with their respective branches and the current status of each worktree.

   ### Usage:
   ```
   ./gwts
   ```

   ### Features:
   - Displays each worktree's path and associated branch name.
   - Shows the `git status -s` (short status) for each worktree.

## Installation

1. Clone this repository or download the scripts.
2. Make the scripts executable:
   ```
   chmod +x gwt gwts
   ```
3. Optionally, move the scripts to a directory in your PATH for easy access.

## Requirements

- Bash
- Git

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Your feedback and contributions are welcome!


Enjoy more efficient Git worktree management!
