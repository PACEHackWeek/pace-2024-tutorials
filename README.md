# pace-2024-tutorials

1. Open terminal
2. Day 1. First time
  ```
  cd ~
  git clone "https://github.com/PACEHackWeek/pace-2024-tutorials"
  ```
3. Day 2 or anytime the tutorials are updated.
  The following commands will get changes on GitHub. If you have made local changes, then you might get merge conflicts.
  ```
  cd ~/pace-2024-tutorials
  git pull
  ```

  If you get merge conflicts and want to wipe you your local changes, then use
  ```
  cd ~/pace-2024-tutorials
  git fetch --all
  git reset --force origin/main
  ```
