
# Pehmis Sofle V2 case

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

### A 3D printed, seamless case with magnetic wrist rests for the Sofle V2 keyboard

![](_Images/sofle1.png)


---

### --> [Original Sofle keyboard repository](https://github.com/josefadamcik/SofleKeyboard)
### --> [Original Elmo Case Repository](https://github.com/kb-elmo/SofleCase)

Please note that only the v2 layout versions are compatible with this case.

---

Assembly materials needed:
---

- **10x** m2x10mm screws for the cases.
- **20x** m2x4mm screws for the plates (If you bought a sofle kit these should be included).
- **10x** m2x8mm standoffs for the pcbs (If you bought a sofle kit these should be included).
- **16x** 8mm rubber bumpons (optional).
- **8x** 8x3mm magnets to attach wrist rests (optional).

Changes to Elmo's original case:
---
- Added magnetically attached wrist rests.
- Raised the top of the case by 1mm to look nicer with cherry profile caps.
- Moved usb port holes and made more space inside to fit a socketed regular pro micro instead of elite-c.
- Changed to "tray mount" style to allow use with a normal plate from a sofle kit instead of a printed one.
- Removed rgbled-strip channels on the bottom. Depending on the size of your strips you might still be able to fit some under the pcb.
- Modified knob to work with raised case and plum style encoder shaft.
- Enlarged reset button holes.
- Enlarged rubber bumpon pads to fit 8mm bumpons.




Please note:  
---

- The two case halves are not symmetrical!  
Just using one of the files and mirroring it in your slicer will not work.  
The holes for the TRRS and usb cables are in slightly different locations on the two sides.
- The reset switch on both sides of the board should ideally be mounted on the bottom of the PCB.  
That way you can press the button through the hole in the bottom of the case without having to disassemble the entire board.
- The included knob is designed for the Alps EC11 encoder with a 15mm tall plum shaft.  [Such as this one.](https://www.aliexpress.com/item/1005002767327743.html)
If you are using a different model you might have to use a different knob for your board.
- Red colored faces in the files indicate suggested build orientation. Red toward bed.



Special Thanks to
---

- Josef Adamcik for designing the original Sofle keyboard and making the project open source.
- kb-elmo for making the original version of this case and sharing the step files.

---

These files are meant for 3D printing only! 

They are not suitable for CNC machining and trying to use them for that will most likely result in unusable parts.

---
Exploded view
---

![](_Images/render1.png)

---
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
