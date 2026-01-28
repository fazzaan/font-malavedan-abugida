## Changelog

_28th January 2026_

### v 0.950

[Download v0.950 release](https://github.com/fazzaan/font-malavedan-abugida/releases/tag/F0.950-K1.3)  

_Important change in typing method:_
* Added feature for typing Vowel Letter using lowercase keyboard key IF the letter is the first of the word. This feature can be disabled by disabling the font's ligature feature, called "liga" in some software. I have tested this feature in many ways but there may be bugs.
-- If you want to type the vowel diacritics as a demonstration, you have two options: 1. disable the ligatures feature. 2. use the "circledotted" character before the vowel diacritic, unicode char value u25cc.
* Added placeholder glyphs for the non-straight quote marks which apps and phones often auto-substitute while typing.

### v 0.940 
_Rename font to match the tribal name._

___

_28th January 2026_

### v 0.931 

[Download release v0.931](https://github.com/fazzaan/font-malavedan-abugida/releases/tag/F0.931-K1.3)  

_Minor Bugfix_
* Fixed glyph class for ha2.
* Fixed anchors for wide nja and sha2.

### v 0.930 
_Symbols and OpenType logic_
* Fixed a load of OpenType issues and made some new code logic. All sensible key sequences should now be supported. There are a few seqences (such as multiple back-to-back vowels) which don't work but honestly I think that's rarely gonna happen, and the "proper" typing method (i.e. Shift+Vowel) prevents this from happening anyway. The new OpenType features are actually intended to make it possible to avoid pressing Shift for the base vowel letters.
* Added all the standard symbols of the typical keyboard, and the Rupee.

### v 0.921 
_Numbers, & letter stroke thickness_
* I was rushing last night and I managed to write the class logic wrongly and thus broke all the OpenType script (this is quite a weakness of OpenType tbh, it's all one block of script so one single mistake breaks the entire script sheet). Anyway I've fixed it now.
* Also making some letter brush strokes thicker, especially in letters with several horizontal lines.
* Also I've put the ss01 glyphs (na, nja and sha2) on [P]. [Y] and [X] respectively.

### v 0.920 
_Numbers_
* Minor version bump because I added numbers but not yet symbols.

___

_26th January 2026_

### v 0.901 

[Download release of v0.901](https://github.com/fazzaan/font-malavedan-abugida/releases/tag/F0.901-K1.2)  

_Bugfix_
* Changed the R diacritic key - I got the wrong R letter before. Now it's the Shift+R letter/key.
* Updated the vowel diacritic OpenType logic.

### v 0.900 
_Major update_
* Put all glyphs into classes, so now I can programme the OpenType features efficiently.
* the AI vowel is positioned before its base consonant. This is now reflected in the typing method: you type N+W and the visual output is [wn]. This allows for typing to follow the pronunciation sequence. This feature can be disabled in a future update if you don't like it and if you would prefer people to type the AI vowel before the base consonant.
* Various other fixes and improvements. Wide vowel marks should now take up the correct horizonal space when typed.
* Wide versions of nja, na and sha2 should now be accessible by activating Stylistic Set 1 (ss01) in the font display settings, if your app supports it. If you prefer them, I can set them as the default letter forms instead.

### v 0.804
Added initial OpenType code for r diacritic using the overring sequence, consonant + overring + [ra]. Just to test, not finished because I haven't made the consonant classes in the Features code yet.

### v 0.803
* Fixed O diacritic situation with good clean logic. Key layout is back to the original one, O is no longer ane exception.
* Added a bunch of OpenType calt logic for replacing vowel sequences with diacritics and/or letters. This logic is based on my assumptions about the con-script's orthography, so may have to be updated in the future. Also I've only tested it programmatically, and not in praxis, so it might be awful for real-world usage.

### v 0.802
* O diacritics: Added both glyphs and OpenType rules. Attached to keys [o] and [O]. Moved letters "O" to key [w], "au" to key [W], and "ai" to key [q].
* Swapped all vowels around, with lowercase [key] holding diacritic and uppercase [key] holding whole letter:
- [a] is 'a' diacritic, [A] is letter 'A',
- [e] is 'e' diacritic, [E] is letter 'E',
- [i] is 'i' diacritic, [I] is letter 'I',
- [o] is 'o' diacritic, [O] is 'long o',
- [u] is 'u' diacritic, [U] is letter 'U',
- [w] is letter 'O', [W] is letter 'au',
- [q]/[Q] is letter 'ai'.
!! Note that O is an exception, due to it being composed of two diacritics. In this version of the font, it doesn't make a difference, because I haven't worked out how to use OpenType to replace "oo" with two diacritics yet; but I'd rather design the QWERTY layout as if it already works so that the people using the font don't have to change their typing habits in the future.

### v 0.800 status
* All base consonants are done.
* All base vowels are done.
* All vowel diacritics are done.
* All diacritic anchors are done (I think).
* O diacritic is not done, this is a two-part diacritic which I need to work out how to code in OpenType.
* All consonants and vowels are also attached to the Latin QWERTY layout.
* A few numbers are done.
