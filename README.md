# bin

Personal utility scripts

---
Some of these scripts may be useful to others, such as `picnote`, or
`pdfselect`, whereas some of these are somewhat specific to my setup, such as
the handy `fixmouse`.

### Notification
Usually ran as cron jobs.  Provide some form of feedback.

* `batt-notify`: Calculates the remaining battery power percentage left on a
  two-battery system

### Settings 
Modify the configuration of the system.

* `extscreen`: A simple wrapper around xrandr to work easily with external displays
* `fixmouse`: Reapplies desired mouse behavior when it mysteriously changes
* `mirror-update`: Filter Arch Linux mirrorlist for only US mirrors, then finds the 6 fastest
* `toggle-jack`: Start or stop
  [JACK](https://wiki.archlinux.org/index.php/JACK_Audio_Connection_Kit) with a
given audio device.
* `toggle-syn`: Disables/Enables a Synaptics touchpad and moves the cursor to the
bottom-left corner of the display
* `wacom-init`: Sets up Wacom tablet to my liking.

### Launching
Starts a program.  Usually mapped to a keyboard combination shortcut.

* `mimelaunch`: Launches a [rofi](https://davedavenport.github.io/rofi/) window
  populated with files from specified directories, then launches them with
default app.
* `pdfselect`: Finds all PDFS in the given locations and feeds the files
to [rofi](https://davedavenport.github.io/rofi/) for fast, easy, launching.
* `picnote`: Begins an interactive screengrabbing box with scrot and then displays the 
image in a minimal view.  Good for quick temporary graphical references