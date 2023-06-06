

![Romanian Dvorak Layout](https://raw.githubusercontent.com/thelightstain/tastatura-dvorak-romana/main/docs/assets/images/romanian-dvorak.png)

Dacă te dor degetele după sesiuni mai lungi de tastare, se poate să fie din următoarele motive:
- ai mâini mici (aia e, nu prea ai ce să faci)
- ai tehnică proastă de tastat (și eu, nu am făcut niciun curs)
- aranjamentul QWERTY nu este optim pentru tine

În cazul meu primele două se aplicau cu siguranță. Al treilea se numește masochism.

## Tastaturile pentru limba română

Împlementarea corectă a limbii române pentru tastaturi și software este încă problematică. În 2021 în România a fost lansata bancnota de 20 RON cu Ecaterina Teodoroiu. Ghicește ce e pe ea. Hai că îți spun eu: diacritice greșite.

Totul a început în era Windows XP când diacriticele românești
 - ăĂ (a cu căciulă), 
 - âÂ (a cu accent circumflex), 
 - îÎ (i cu accent circumflex), 
 - șȘ (s *virgulă dedesubt*), 
 - țȚ (t *virgulă dedesubt*) 
 au fost implementate incorect, folosind ce era deja disponibil. Da, çedilă despre tine e vorba, știu că se scrie sedilă.

## Dvorak pentru limba română

Această implementare este bazată pe aranjamentul tastaurii Dvorak simplificată și cel al tastaturii în limba română pentru programatori. Folosește modificatorul `Alt+Ctrl (AltGr)` pentru a produce caracterele specifice limbi române, în restul timpului comportându-se exact ca tastatura simplificată Dvorak americană.

### Aranjamentul normal al tastaturii Dvorak pentru limba română

![Romanian Dvorak normal](https://raw.githubusercontent.com/thelightstain/tastatura-dvorak-romana/main/docs/assets/images/ro-dv.png)

### Tastatura Dvorak pentru română cu tasta `Shift` apăsată

![Romanian Dvorak shift](https://raw.githubusercontent.com/thelightstain/tastatura-dvorak-romana/main/docs/assets/images/ro-dv-shift.png)

### Tastatura Dvorak în română cu tasta (sau combinația) `AltGr` apăsată

![Romanian Dvorak altgr](https://raw.githubusercontent.com/thelightstain/tastatura-dvorak-romana/main/docs/assets/images/ro-dv-altgr.png)

### Tastatura Dvorak în română cu `Shift+AltGr` apăsate

![Romanian Dvorak shift altgr](https://raw.githubusercontent.com/thelightstain/tastatura-dvorak-romana/main/docs/assets/images/ro-dv-shift-altgr.png)

Aranjamentul a fost creat folosind [Microsoft Keyboard Layout Creator (MSKLC) Version 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=102134) și se validează identic cu aranjamentul tastaturii în română pentru programatori livrat împreună cu Windows.

Important de observat este plasarea literei âÂ. Pe tastatura în română pentru programatori, această literă se obține prin apăsarea simultană a tastelor `AltGr+q`. În implementarea Dvorak pentru limba română, âÂ se obțin prin apăsarea combinației `AltGr+o`din următoarele motive:

 1. Păstrarea literei pe rândul principal (qQ este mai greu de tastat decât eE pe Dvorak)
 2. Ââ este o vocală și trebuie să se afle pe rândul principal în partea stângă împreună cu celelalte vocale
 3. oO se află lângă aA în Dvorak la fel cum qQ este lângă aA pe QWERTY
 3. În limba romănă oO nu are diacritice.

### Rândul principal al tastaturii Dvorak pentru romănă cu modificatorul `AltGr`

![Romanian Dvorak home row](https://raw.githubusercontent.com/thelightstain/tastatura-dvorak-romana/main/docs/assets/images/romanian-dvorak-altgr-homerow.png)

## Pot descărca și folosi acest aranjament?

Da, chiar te rog. Am creat această implementare deoarece am trecut la Dvorak și aveam nevoie să scriu în limba română (cu tot cu diacritice). Îl poți descărca gratuit. Dacă te ajută în vreun fel, nu ezita să dai o cafea (vezi butonul de mai jos).

## Ce urmează?

Pentru moment numai sistemul de operare Windows este suportat. Dacă ai nevoie de tastatura Dvorak în română pe alte sisteme de operare aș putea face implementarea cu mare plăcere pentru Linux sa familia BSD.

  <form id="paypal_button" action="https://www.paypal.com/donate" method="post" target="_top">
  <input type="hidden" name="business" value="9NQ3C668RVAC4" />
  <input type="hidden" name="no_recurring" value="0" />
  <input type="hidden" name="item_name" value="Deci îți place tastatura Dvorak? Și mie, măcar suntem doi. Mulțumesc pentru cafea!" />
  <input type="hidden" name="currency_code" value="RON" />
  <input type="image" src="https://raw.githubusercontent.com/thelightstain/tastatura-dvorak-romana/main/docs/assets/images/buy-me-a-coffee.png" width="100" height="30" border="0" name="submit" title="PayPal - modul sigur și ușor de a plăti online!" alt="Donează cu butonul PayPal" />
  <img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
  </form>
Noroc,

*Radu*

