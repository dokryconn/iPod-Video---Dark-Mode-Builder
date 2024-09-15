(Modding by Kingstone)

.:TODO LIST:.
New stylish and improve UI design.

.:WHAT'S NEW:.
=Thanks for goPod developers on the volume hack machnism=

#1.3#
(06/25/2007)
* Added command table in layout tab (not entirely finished but has some stuff)
* Added save/load all resources
* Improved resource searching in layout tab
* You can change color of fonts easily
* Fixed common error -1 on 5.5g
* File saving system improved
* Remember last mode used
* Added preferences tab with lots of stuff:
  * Tip of the day: tips for ipodwizard
  * Faster firmware loading by disable previews
  * Switch between index systems
  * Check for updates of iPodWizard program
* Theme previewer - see how your themes turn out before you write them to your iPod!
  * Create theme screens using simple text file scripting
  * Show specific layouts/menus drawed
* MultiLoad/Save glyph in OTF fonts
* Fixed many bugs (memory/stuff)
* Added small improvements in dialogs
* Theme tab updated:
  * A theme now is a zip file in disguise (.ipw extension). You just have all the pics, fonts, resources, strings in a zip which makes it more comfortable.
  * All resource formats are supported in themes.

#1.2d#
(02/26/2007)
*A new tab is added to Firmware Editor tab called Layout.
 3 Resource types:
 1. Scheme Layouts
 2. Menus
 3. Font types
 4. Command table (not supported atm)
*Fixed many bugs/crashes.
*Added drag and drop feature for pictures! Just drag a file to the picture area to change it or drag a whole theme folder there it will load all files.
Also you can now check for the old saving system if you like.
*A Fix checksum function. Got a broken firmware? Modded your firmware out of iPodWizard? Go and fix your checksum. Right click in the list of checksums on the line you want to fix and fix it.

#1.2#
(03/25/2006)
* New 5G font support (a bit different then regular one and not totally perfect yet).
* Theme file fixes and format.
* Auto associate .iPW theme files with iPodWizard and when opened, auto open iPodWizard and load them.
* New string language blocks which allows editing all languages and strings appearing on the iPod with ability to extend or shorten the strings.
* Regular font fixes.
* Added IDs in pictures for accurance.
* iPod firmware on the fly editing support. This will solve the problem for iPodLinux/Rockbox users who wants to mod their Apple firmware too. Also you can backup themes currently on your iPod. This editing is done without updating with an updater.
* Fixed many small bugs.

#1.1e#
(11/27/2005)
* Fixed big memory bug.
* Fixed nano graphics bug.
* Added a whole new theme system which allows you to make and load themes (one .ipw theme file).
* Added an updater manager which allows to extract/load (delete soon) firmware binaries from the updater (similar to Resource Hacker).
* Fixed minor bugs.

#1.1d#
(11/14/2005)
* Added jump to hex address.
* Added string filter mechanism.
* Added built-in firmware volume hacking.
* Fixed scrollbars for font zoom window.
* Added zooming sizes changing and grid option.
* Added ability to change strings using hex codes for the 'Save Changes' to remember all changes.
* Fixed minor bugs.

#1.1c#
(11/06/2005)
* Fixed save all feature for 5g model.
* Discovered more pictures for 5g/nano plus fixed a few photo pics.
* Added scrollbars to font picture/font zoom view/strings listbox.
* Added unicode support for the whole program plus UTF8 support for strings (changing/viewing etc).
* Added save/load string changes (All the changes you've made using 'Change String' since you loaded the firmware).
* Updated string list item after changing a string.
* Added wilcard find method for strings (much easier in many cases).
* Added direct firmware (inside the iPod hdd) volume uncapping feature (with ability to recap). 
[Thanks for goPod developers for this one, source code taken from goPod and integrated into iPodWizard.]
* Changed iPod detection method (who wants this ugly stupid dll anyway?).
* Fixed help button drawing for non XP style users.


#1.1#
(09/24/2005)
* Added support for iPod nano and 5g (Note: for nano, only firmware 2005-09-23 and above will work correctly)
* Added help button (? in titlebar) which tells you valuable information about iPodWizard and your firmware/iPod (+Find out what is your iPod generation).
* Improved string hex editing.
* Upgraded firmware list which now doesn't show shuffle and shows iPod names instead of firmware resource names.
* Auto load updater after Write method.
* Added warning for changing correct "iPod" string (which if not changed in the right place, can ruin your iPod).
* Fixed minor bugs.

#1.0.7.2#
(09/17/2005)
* Added string hex editing into iPodWizard. (Press '?' to check if the string can be changed good)
* Added new metrics file method which saves you work (not official .IFM type).
* Added installed firmware version changer (SysInfo buildID changer).
* Added tweaks for iPod listed as:
 - Voltage meter
 - CPU usage meter
 - Deep sleep mode
 - Cache disabler.
* Fixed message "unable to open file" (firmware) in program init because of firmware file path changed.

.:COPYING:.

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either
version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.

.:DISCLAIMER:.

iPod Wizard is a program that allows you to change the graphics, font
and strings on your iPod, iPod mini and iPod Photo

We can't be held responsible for the use you make with this program
or any damage it could cause to you iPod.

iPod Wizard is not in any way affiliated with Apple Computer, Inc.

Apple(tm) iPod(tm) are trademarks of Apple Computer, Inc.