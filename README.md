As the name implies, DarkIce is a dark theme with an icy color scheme. Gradients are plentiful, and textures abound in this non-flat theme. This theme is based on DarkCold, but has diverged enough to be considered a different theme because of reworked art and many additions. Stay tuned, the best rendition of this theme is yet to come. I'll keep adding to this theme, so suggestions & criticism are welcome as are Pull Requests if you're a developer. If requests become frequent enough, I'll start a list of upcoming features for requests I'm working on adding.


DarkIce GTK2 & GTK3 theme
========================
Version: 1.1
Recommended GTK+ 3 version: >=3.20
Tested on: Arch Linux w/ gtk3 3.24.4 on XFCE 4.13.x
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
Copy extracted DarkIce folder to ~/.themes

Gecko-based Browser Compatibility:
===============================
Copy the userContent.css file inside the theme directory into your browser's chrome directory.
If your browser's profile directory is missing the chrome subdirectory, create it and put the userContent.css file in there.

For Firefox:
userContent.css -> ~/.mozilla/firefox/"ReplaceThisWithTheRandomProfileName"/chrome

For Palemoon:
userContent.css -> ~/.moonchild productions/pale moon/"ReplaceThisWithTheRandomProfileName"/chrome




Changes from DarkCold:
====================
+ Subtle scrollbar animations for GTK >=3.20
+ Scrollbar artwork reworked for additional contrast/clarity (i.e., GTK+ 2 & 3)
+ Added new images and code for pressed (i.e., ACTIVE) scrollbars and buttons (i.e., steppers)
+ Cleaned some typos in CSS and gtkrc files
+ Changed switch on/off to 0/1 and added gradients (i.e., I am reworking these again for transition animations)
+ Halved the size of the slider for better GTK+ 3.20 compatibility
+ Scale slider active (i.e., pressed) states added with transition effects
+ Transition effects added to existing hover graphics
+ Pressed states added to GTK+ 2
+ xfwm theme now integrated and included
+ xfwm title text shadow frame added and title text recolored for further contrast improvements

Known Issues:
=============
- GTK+ 3 is missing textures used for GTK+ 2; I'm not yet sure what's capable of being ported
- GTK+ 2 has no transition animations; I'm not yet sure what's capable of being backported
- Gnome/Xfce terminal scrollbar steppers aren't arranged properly, I might have to add program-specific CSS (if that's possible for the terminals). Budgie panel seems to have specific CSS for the Vertex theme; I might try to adapt that.