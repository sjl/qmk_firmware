# Configuration

Keymap files are in:

    sjl/*

Config files (e.g. to disable RGB Gamer Crud™) are in:

    keyboards/keebio/sinc/*

# Sinc Rev2 (Space Cadet)

    qmk compile -kb keebio/sinc/rev2 -km sjl
    qmk flash -kb keebio/sinc/rev2 -km sjl

# Sinc Rev3 (Godspeed)

    qmk compile -kb keebio/sinc/rev3 -km sjl

This will produce `keebio_sinc_rev3_sjl.uf2`.

Hold reset button on keyboard for 1s, and it will remount itself as a Raspberry
PI USB drive (lol).  Drag the `uf2` file onto it and it will notice and reboot
itself.
