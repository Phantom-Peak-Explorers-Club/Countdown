# Phantom Peak countdown automatic handover

Upload `index.html` and the four new files in `Assets/` to the existing GitHub Pages repository.
Do not delete the existing Assets, icons or manifest files.

## Automatic behaviour

The current ticket countdown remains active until:

**00:01 London time — Tuesday 25 August 2026**

At that moment the same page automatically changes to the new Phantom Peak refurbishment view.

The new live countdown runs to:

**18:00 London time — Friday 4 December 2026**

At 18:00 the lower status automatically changes from **NO** to **YES**, the countdown is hidden, and the message becomes **PHANTOM PEAK IS REDONE!**

## Hidden testing

Before the handover, add:

`?preview=refurb`

to the end of your normal page URL to force the new view.

Use:

`?preview=tickets`

to force the existing ticket view.

Remove the query string to return to automatic mode.
