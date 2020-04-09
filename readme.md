# What is this?

This is new build of suckless' dynamic window manager (dwm). 
It has a a lot of unessential patches and customisation (including pywal support) to make my life easier and is, dare I say, in a way bloated.
The default dwm is fine and can be found at https://dwm.suckless.org/

## Dependencies

* pywal *(colour and theme)* **Note:** you need to run before dwm pywal in your .xinitrc to run as no colour array is defined in config.h
* `Compton / picomp` (or `xcompmgr`) *(transparency)*
* `libxft-bgra` *(colour emoji)*

## Currently applied patches:

* `Alpha` *(transparency)*
* Autoresize
* Bottomstack
* Center
* Combo
* Cyclelayouts
* Fakefullscreen
* Gaps
* Master
* Maximize_vert_horz
* Movestack
* Nopatch
* Pertag
* Swallow
* UrgentBorder
