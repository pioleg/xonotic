# Config files for Xonotic

## Installation

Put files into:

| System   | Path                               |
| -------- | ---------------------------------- |
| Windowxs | %USERPROFILE%\Saved Games\xonotic\ |
| Linux    | $HOME/.xonotic/data/               |

## Execution

`autoexec/first-time-setup.cfg` will be automatically executed only on first game start after installation (further executions will be prevented by custom variable `first_setup_done`).

`autoexec/first-time-setup.cfg` runs files from `custom` folder in this order:

```
autoexec/first-time-setup.cfg
└── first-time-setup.cfg
    ├── profile.cfg
    └── setup.cfg
        ├── video.cfg
        ├── effects.cfg
        ├── audio.cfg
        ├── game.cfg
        │   ├── crosshair.cfg
        │   ├── hud.cfg
        │   ├── messages.cfg
        │   ├── models.cfg
        │   ├── view.cfg
        │   ├── weapons.cfg
        │   └── damage-text.cfg
        ├── input.cfg
        │   └── binds.cfg
        └── misc.cfg
```
