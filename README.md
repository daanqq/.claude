# .claude

My Claude Code configuration: instructions, settings, skills, hooks and statusline.

## Install

```sh
git clone git@github.com:daanqq/.claude.git ~/.claude
```

If `~/.claude` already exists, initialize git there and pull instead:

```sh
cd ~/.claude
git init
git remote add origin git@github.com:daanqq/.claude.git
git fetch origin
git checkout -f -b main --track origin/main
```

Machine-specific overrides go to `settings.local.json` (ignored).
