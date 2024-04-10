# detect-unsaved-vim-files-in-git

detect unsaved vim buffers in a git repo

use as pre-commit hook:
```yaml
repos:
  - repo: https://github.com/zerwes/detect-unsaved-vim-files-in-git
    rev: v24.4.2
    hooks:
      - id: unsaved-vim-files
        fail_fast: true
```
