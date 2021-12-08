

![Romanian Dvorak Layout](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/romanian-dvorak.png)


## Romanian keyboards

Keyboard layouts and software that implement Romanian are still problematic. A new bancnote was released in 2021 in Romania and guess what? Wrong diacritics!

It all started in the Windows XP era when the Romanian diacritics 
 - ăĂ (a breve), 
 - âÂ (a circumflex), 
 - îÎ (i circumflex), 
 - șȘ (s *comma below*), 
 - țȚ (t *comma below*) 
 were badly implemented using what was available, I am looking at you, çedilla.

## Romanian Dvorak

This implementation is based on the simplified Dvorak keyboard layout and on Romanian Programmers layout. It uses the `Alt+Ctrl (AltGr)` modifier to output the specific characters, the rest of the time is just like US Simplified Dvorak.

### Normal layout for Romanian Dvorak

![Romanian Dvorak normal](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/ro-dv.png)

### Romanian Dvorak with `Shift` key pressed

![Romanian Dvorak shift](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/ro-dv-shift.png)

### Romanian Dvorak with `AltGr` pressed

![Romanian Dvorak altgr](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/ro-dv-altgr.png)

### Romanian Dvorak with `Shift+AltGr` pressed

![Romanian Dvorak shift altgr](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/ro-dv-shift-altgr.png)

The layout has been created with [Microsoft Keyboard Layout Creator (MSKLC) Version 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=102134) and validates the identically to the Romanian Programmers layout supplied with Windows.

'''
 WARNING: ^ (U+005e) is already defined more than once on the keyboard (on VK_6, ShiftState 'Shift' and VK_3, ShiftState 'Ctl+Alt').
    WARNING: The character ș (U+0219) exists in the entry for VK_S, ShiftState 'Ctl+Alt' of the layout table and is not in the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The character Ș (U+0218) exists in the entry for VK_S, ShiftState 'Shift+Ctl+Alt' of the layout table and is not in the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The character ț (U+021b) exists in the entry for VK_T, ShiftState 'Ctl+Alt' of the layout table and is not in the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The character Ț (U+021a) exists in the entry for VK_T, ShiftState 'Shift+Ctl+Alt' of the layout table and is not in the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: ` (U+0060) is already defined more than once on the keyboard (on VK_OEM_3, ShiftState 'Base' and VK_7, ShiftState 'Ctl+Alt').
    WARNING: ~ (U+007e) is already defined more than once on the keyboard (on VK_OEM_3, ShiftState 'Shift' and VK_1, ShiftState 'Ctl+Alt').
    WARNING: The dead key ^ (U+005e) when combined with e (U+0065) returns ê (U+00ea), but ê (U+00ea) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ^ (U+005e) when combined with u (U+0075) returns û (U+00fb), but û (U+00fb) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ^ (U+005e) when combined with E (U+0045) returns Ê (U+00ca), but Ê (U+00ca) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ^ (U+005e) when combined with U (U+0055) returns Û (U+00db), but Û (U+00db) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with a (U+0061) returns à (U+00e0), but à (U+00e0) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with e (U+0065) returns è (U+00e8), but è (U+00e8) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with u (U+0075) returns ù (U+00f9), but ù (U+00f9) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with i (U+0069) returns ì (U+00ec), but ì (U+00ec) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with o (U+006f) returns ò (U+00f2), but ò (U+00f2) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with A (U+0041) returns À (U+00c0), but À (U+00c0) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with E (U+0045) returns È (U+00c8), but È (U+00c8) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with U (U+0055) returns Ù (U+00d9), but Ù (U+00d9) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with I (U+0049) returns Ì (U+00cc), but Ì (U+00cc) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ` (U+0060) when combined with O (U+004f) returns Ò (U+00d2), but Ò (U+00d2) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ¨ (U+00a8) when combined with i (U+0069) returns ï (U+00ef), but ï (U+00ef) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ¨ (U+00a8) when combined with y (U+0079) returns ÿ (U+00ff), but ÿ (U+00ff) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ¨ (U+00a8) when combined with I (U+0049) returns Ï (U+00cf), but Ï (U+00cf) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
    WARNING: The dead key ¨ (U+00a8) when combined with Y (U+0059) returns Ÿ (U+0178), but Ÿ (U+0178) is not on the default system code page (1250) of the Romanian (Romania) language you specified. This may cause compatibility problems in non-Unicode applications.
```
