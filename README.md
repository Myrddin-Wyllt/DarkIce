DarkIce GTK2 & GTK3 theme
========================
![](./logo.png)

DarkIce is a dark theme with an icy color scheme. Gradients & textures abound in this non-flat theme. The theme is based on DarkCold, but has diverged enough to be considered a different theme because of reworked art and many additions. Stay tuned, the best rendition of this theme is yet to come. I'll keep adding to DarkIce, so suggestions & criticism are welcome as are Pull Requests if you're a developer. If suggestions become frequent enough, I'll start a list of upcoming features for requests I'm working on adding.

NB: For those who are updating, you should overwrite the old userContent.css in your browser's chrome folder.

**Version: 1.3**

+ Minimum GTK 3 version: >=3.20
+ Maximum xfwm font size: 12
+ Tested on: Arch Linux, gtk3.24.8, & XFCE4.13.x

Based on: http://gnome-look.org/content/show.php/DarkCold?content=143165

Git: git clone https://github.com/Myrddin-Wyllt/DarkIce.git

Installation per-user:
==================
Download

Extract

If ~/.themes is absent from your Home directory, create it

Copy extracted DarkIce folder to ~/.themes

Installation system-wide:
======================
Download
Extract
Copy extracted DarkIce folder to /usr/share/themes

Gecko-based Browser Compatibility:
===============================
Copy the userContent.css file inside the theme directory into your browser's chrome directory.
If your browser's profile directory is missing the chrome subdirectory, create it and put the userContent.css file in there.

For Firefox:
userContent.css -> ~/.mozilla/firefox/"ReplaceThisWithTheRandomProfileName"/chrome

For Palemoon:
userContent.css -> ~/.moonchild productions/pale moon/"ReplaceThisWithTheRandomProfileName"/chrome


NB: If updating, you should overwrite the old userContent.css


Changes from DarkCold:
====================
+ Transition effects added to hover graphics and the new pressed states for buttons/scrollbars in GTK 3
+ Scrollbar artwork reworked for additional contrast/clarity (i.e., GTK 2 & 3)
+ Added new images and code for pressed scrollbars and buttons (i.e., GTK 2 & 3)
+ Cleaned & refactored many typos/deprecations in CSS and gtkrc files
+ Changed switch on/off to 0/1 and added gradients with transition effect
+ Halved the size of the scale slider for better GTK 3.20 compatibility
+ Scale slider (i.e., volume slider) pressed states added with transition effects
+ Removed legacy (i.e., GTK 3 <3.20) GTK 3 code
+ Refactored userContent.css for improved website compatibility in Gecko-based browsers
+ xfwm theme now integrated and included
+ xfwm title text shadow frame added and title text recolored for further contrast improvements
+ xfwm titlebar top is now resizable across the entire width (NB: Font size cannot be greater than 12)


Known Issues:
=============
- GTK 3 is missing textures used in GTK 2; I'm not yet sure what's capable of being ported
- GTK 2 has no transition animations; Unresolvable
- Gnome/Xfce terminal scrollbar steppers aren't arranged properly, I might have to add program-specific CSS (if that's possible for the terminals). Budgie panel seems to have specific CSS for the Vertex theme; I might try to adapt that.
- Spinbutton alignment is skewed in GTK 3 (i.e., a pixel or two too high)
