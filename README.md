# crkbd-keymap
Custom keymap for my crkbd (corne) keyboard.

## setup
Make sure you have qmk. Run `qmk setup` to get the firmware repository.
Clone this repository in `keyboards/crkbd/keymaps` or symlink this repository
to that directory.

Set keyboard and keymap.
```
qmk config user.keyboard="crkbd"
qmk config user.keymap="jack-davidson"
```

## building
In qmk_firmware directory:
```
make crkbd:jack-davidson
```

## flashing
In qmk_firmware directory:
```
qmk flash
```
