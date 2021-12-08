

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

This implementation is based on the simplified Dvorak keyboard layout and Romanian Programmers layout. It uses the `Alt+Ctrl (AltGr)` modifier to output the specific characters, the rest time behaving just like US Simplified Dvorak.

### Normal layout for Romanian Dvorak

![Romanian Dvorak normal](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/ro-dv.png)

### Romanian Dvorak with `Shift` key pressed

![Romanian Dvorak shift](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/ro-dv-shift.png)

### Romanian Dvorak with `AltGr` pressed

![Romanian Dvorak altgr](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/ro-dv-altgr.png)

### Romanian Dvorak with `Shift+AltGr` pressed

![Romanian Dvorak shift altgr](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/ro-dv-shift-altgr.png)

The layout has been created with [Microsoft Keyboard Layout Creator (MSKLC) Version 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=102134) and validates identically to the Romanian Programmers layout supplied with Windows.

One important thing to notice is the placement of âÂ. On Romanian programmers it was mapped to `AltGR+q`. In Romanian Dvorak I mapped âÂ to `AltGr+o` for the following reasons:

 1. Keep it on the home row (q is less reachable than e on Dvorak)
 2. Ââ is a vowel and it should be on home row, on the left hand side
 3. o is next to a in Dvorak just as q was next to a in QWERTY
 3. In Romanian O does not have diacritics.

### Romanian Dvorak home row normal mode and with `AltGr` modifier

![Romanian Dvorak home row](https://raw.githubusercontent.com/thelightstain/romanian-dvorak-keyboard-layout/main/docs/assets/images/romanian-dvorak-altgr-homerow.png)

## Can I use this layout?

Of course, be my guest. I made this layout because I switched to Dvorak and I also need to write in Romanian. I am sharing it with you for free. If it helps you in anyway, don't hesitate to buy me a coffee (button below).

## What's next?

Currently only Windows is supported. If there is a need for this layout to be ported to other OSes, I will happily do it for Linux and BSDs.

  <form id="paypal_button" action="https://www.paypal.com/donate" method="post" target="_top">
  <input type="hidden" name="business" value="9NQ3C668RVAC4" />
  <input type="hidden" name="no_recurring" value="0" />
  <input type="hidden" name="item_name" value="So, you want to use the Romanian Dvorak Keyboard layout, huh? That makes two of us! Thanks for the coffee, much obliged." />
  <input type="hidden" name="currency_code" value="EUR" />
  <input type="image" src="https://pics.paypal.com/00/s/NjJjMjBjMTEtYzFiOC00YTk3LTgxNmMtMDZiMDBiMjMzZWFm/file.PNG" width="100" height="30" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
  <img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
  </form>
Cheers,

Radu

