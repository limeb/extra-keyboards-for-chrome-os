# Compose Key for Chrome OS

This extension turns the right Alt key (the trigger key is configurable) into a
Compose key on a variety of different English keyboard layouts including US,
Canadian, and UK.

The key sequences used are the same as
[Xlib](https://www.x.org/releases/current/doc/libX11/i18n/compose/en_US.UTF-8.html)
for the en_US.UTF-8 locale (though the built-in sequences currently do not
include the full set defined by Xlib).

## Configuration

Select the appropriate "Compose key" from the "Input method" options in the
Settings app. See https://support.google.com/chromebook/answer/1059492 for help
navigating to this area of the Settings app.

You can configure which key acts as the Compose key and add custom XCompose
sequences in the extension's Options page.

## How to use

1. Press and release the Compose key (default is right Alt).
2. Type the desired key sequence as defined below. The proper character will be
   displayed when a key sequence is matched.
3. You can abort compose mode any time after entering the mode by pressing the
   Escape key.

## Full list of built-in sequences

Output | Sequence | Comment
------ | -------- | -------
&nbsp; | "  " | nobreakspace # NO-BREAK SPACE (2 spaces)
¡ | !! | exclamdown # INVERTED EXCLAMATION MARK
¢ | &#124;c | CENT SIGN
¢ | c&#124; | CENT SIGN
¢ | c/ | CENT SIGN
¢ | /c | CENT SIGN
£ | L- | POUND SIGN
£ | -L | POUND SIGN
¤ | ox | currency # CURRENCY SIGN
¤ | xo | currency # CURRENCY SIGN
¥ | Y= | yen # YEN SIGN
¥ | =Y | yen # YEN SIGN
¦ | !^ | brokenbar # BROKEN BAR
§ | so | section # SECTION SIGN
§ | os | section # SECTION SIGN
© | oc | copyright # COPYRIGHT SIGN
© | oC | copyright # COPYRIGHT SIGN
© | Oc | copyright # COPYRIGHT SIGN
© | OC | copyright # COPYRIGHT SIGN
ª | ^_a | ordfeminine # FEMININE ORDINAL INDICATOR
« | << | guillemotleft # LEFT-POINTING DOUBLE ANGLE QUOTATION MARK
¬ | ,- | notsign # NOT SIGN
¬ | -, | notsign # NOT SIGN
® | or | registered # REGISTERED SIGN
® | oR | registered # REGISTERED SIGN
® | Or | registered # REGISTERED SIGN
® | OR | registered # REGISTERED SIGN
° | oo | degree # DEGREE SIGN
± | +- | plusminus # PLUS-MINUS SIGN
² | ^2 | SUPERSCRIPT TWO
³ | ^3 | SUPERSCRIPT THREE
µ | mu | MICRO SIGN
¶ | p! | paragraph # PILCROW SIGN
¶ | P! | paragraph # PILCROW SIGN
¶ | PP | paragraph # PILCROW SIGN
· | .- | MIDDLE DOT
• | .= | BULLET
… | .. | HORIZONTAL ELLIPSIS
¸ | ,, | cedilla # CEDILLA
¸ | ", " | cedilla # CEDILLA
¸ | " ," | cedilla # CEDILLA
¹ | ^1 | SUPERSCRIPT ONE
º | ^_o | MASCULINE ORDINAL INDICATOR
» | >> | guillemotright # RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK
¼ | 14 | VULGAR FRACTION ONE QUARTER
½ | 12 | VULGAR FRACTION ONE HALF
¾ | 34 | VULGAR FRACTION THREE QUARTERS
¿ | ?? | questiondown # INVERTED QUESTION MARK
À | `A | LATIN CAPITAL LETTER A WITH GRAVE
À | A` | LATIN CAPITAL LETTER A WITH GRAVE
Á | 'A | LATIN CAPITAL LETTER A WITH ACUTE
Á | A' | LATIN CAPITAL LETTER A WITH ACUTE
Â | ^A | LATIN CAPITAL LETTER A WITH CIRCUMFLEX
Â | >A | LATIN CAPITAL LETTER A WITH CIRCUMFLEX
Â | A> | LATIN CAPITAL LETTER A WITH CIRCUMFLEX
Ã | ~A | LATIN CAPITAL LETTER A WITH TILDE
Ã | A~ | LATIN CAPITAL LETTER A WITH TILDE
Ä | "A | LATIN CAPITAL LETTER A WITH DIAERESIS
Ä | A" | LATIN CAPITAL LETTER A WITH DIAERESIS
Å | oA | LATIN CAPITAL LETTER A WITH RING ABOVE
Å | *A | LATIN CAPITAL LETTER A WITH RING ABOVE
Å | A* | LATIN CAPITAL LETTER A WITH RING ABOVE
Å | AA | LATIN CAPITAL LETTER A WITH RING ABOVE
Æ | AE | AE # LATIN CAPITAL LETTER AE
Ç | ,C | LATIN CAPITAL LETTER C WITH CEDILLA
Ç | C, | LATIN CAPITAL LETTER C WITH CEDILLA
È | `E | LATIN CAPITAL LETTER E WITH GRAVE
È | E` | LATIN CAPITAL LETTER E WITH GRAVE
É | 'E | LATIN CAPITAL LETTER E WITH ACUTE
É | E' | LATIN CAPITAL LETTER E WITH ACUTE
Ê | ^E | LATIN CAPITAL LETTER E WITH CIRCUMFLEX
Ê | >E | LATIN CAPITAL LETTER E WITH CIRCUMFLEX
Ê | E> | LATIN CAPITAL LETTER E WITH CIRCUMFLEX
Ë | "E | LATIN CAPITAL LETTER E WITH DIAERESIS
Ë | E" | LATIN CAPITAL LETTER E WITH DIAERESIS
Ì | `I | LATIN CAPITAL LETTER I WITH GRAVE
Ì | I` | LATIN CAPITAL LETTER I WITH GRAVE
Í | 'I | LATIN CAPITAL LETTER I WITH ACUTE
Í | I' | LATIN CAPITAL LETTER I WITH ACUTE
Î | ^I | LATIN CAPITAL LETTER I WITH CIRCUMFLEX
Î | >I | LATIN CAPITAL LETTER I WITH CIRCUMFLEX
Î | I> | LATIN CAPITAL LETTER I WITH CIRCUMFLEX
Ï | "I | LATIN CAPITAL LETTER I WITH DIAERESIS
Ï | I" | LATIN CAPITAL LETTER I WITH DIAERESIS
Ð | DH | LATIN CAPITAL LETTER ETH
Ñ | ~N | LATIN CAPITAL LETTER N WITH TILDE
Ñ | N~ | LATIN CAPITAL LETTER N WITH TILDE
Ò | `O | LATIN CAPITAL LETTER O WITH GRAVE
Ò | O` | LATIN CAPITAL LETTER O WITH GRAVE
Ó | 'O | LATIN CAPITAL LETTER O WITH ACUTE
Ó | O' | LATIN CAPITAL LETTER O WITH ACUTE
Ô | ^O | LATIN CAPITAL LETTER O WITH CIRCUMFLEX
Ô | >O | LATIN CAPITAL LETTER O WITH CIRCUMFLEX
Ô | O> | LATIN CAPITAL LETTER O WITH CIRCUMFLEX
Õ | ~O | LATIN CAPITAL LETTER O WITH TILDE
Õ | O~ | LATIN CAPITAL LETTER O WITH TILDE
Ö | "O | LATIN CAPITAL LETTER O WITH DIAERESIS
Ö | O" | LATIN CAPITAL LETTER O WITH DIAERESIS
× | xx | MULTIPLICATION SIGN
Ø | /O | LATIN CAPITAL LETTER O WITH STROKE
Ø | O/ | LATIN CAPITAL LETTER O WITH STROKE
Ù | `U | LATIN CAPITAL LETTER U WITH GRAVE
Ù | U` | LATIN CAPITAL LETTER U WITH GRAVE
Ú | 'U | LATIN CAPITAL LETTER U WITH ACUTE
Ú | U' | LATIN CAPITAL LETTER U WITH ACUTE
Û | ^U | LATIN CAPITAL LETTER U WITH CIRCUMFLEX
Û | >U | LATIN CAPITAL LETTER U WITH CIRCUMFLEX
Û | U> | LATIN CAPITAL LETTER U WITH CIRCUMFLEX
Ü | "U | LATIN CAPITAL LETTER U WITH DIAERESIS
Ü | U" | LATIN CAPITAL LETTER U WITH DIAERESIS
Ý | 'Y | LATIN CAPITAL LETTER Y WITH ACUTE
Ý | Y' | LATIN CAPITAL LETTER Y WITH ACUTE
Þ | TH | LATIN CAPITAL LETTER THORN
ß | ss | ssharp # LATIN SMALL LETTER SHARP S
à | `a | LATIN SMALL LETTER A WITH GRAVE
à | a` | LATIN SMALL LETTER A WITH GRAVE
á | 'a | LATIN SMALL LETTER A WITH ACUTE
á | a' | LATIN SMALL LETTER A WITH ACUTE
â | ^a | LATIN SMALL LETTER A WITH CIRCUMFLEX
â | >a | LATIN SMALL LETTER A WITH CIRCUMFLEX
â | a> | LATIN SMALL LETTER A WITH CIRCUMFLEX
ã | ~a | LATIN SMALL LETTER A WITH TILDE
ã | a~ | LATIN SMALL LETTER A WITH TILDE
ä | "a | LATIN SMALL LETTER A WITH DIAERESIS
ä | a" | LATIN SMALL LETTER A WITH DIAERESIS
å | oa | LATIN SMALL LETTER A WITH RING ABOVE
å | *a | LATIN SMALL LETTER A WITH RING ABOVE
å | a* | LATIN SMALL LETTER A WITH RING ABOVE
æ | ae | ae # LATIN SMALL LETTER AE
ç | ,c | LATIN SMALL LETTER C WITH CEDILLA
ç | c, | LATIN SMALL LETTER C WITH CEDILLA
è | `e | LATIN SMALL LETTER E WITH GRAVE
è | e` | LATIN SMALL LETTER E WITH GRAVE
é | 'e | LATIN SMALL LETTER E WITH ACUTE
é | e' | LATIN SMALL LETTER E WITH ACUTE
ê | ^e | LATIN SMALL LETTER E WITH CIRCUMFLEX
ê | >e | LATIN SMALL LETTER E WITH CIRCUMFLEX
ê | e> | LATIN SMALL LETTER E WITH CIRCUMFLEX
ë | "e | LATIN SMALL LETTER E WITH DIAERESIS
ë | e" | LATIN SMALL LETTER E WITH DIAERESIS
ì | `i | LATIN SMALL LETTER I WITH GRAVE
ì | i` | LATIN SMALL LETTER I WITH GRAVE
í | 'i | LATIN SMALL LETTER I WITH ACUTE
í | i' | LATIN SMALL LETTER I WITH ACUTE
î | ^i | LATIN SMALL LETTER I WITH CIRCUMFLEX
î | >i | LATIN SMALL LETTER I WITH CIRCUMFLEX
î | i> | LATIN SMALL LETTER I WITH CIRCUMFLEX
ï | "i | LATIN SMALL LETTER I WITH DIAERESIS
ï | i" | LATIN SMALL LETTER I WITH DIAERESIS
ð | dh | LATIN SMALL LETTER ETH
ñ | ~n | LATIN SMALL LETTER N WITH TILDE
ñ | n~ | LATIN SMALL LETTER N WITH TILDE
ò | `o | LATIN SMALL LETTER O WITH GRAVE
ò | o` | LATIN SMALL LETTER O WITH GRAVE
ó | 'o | LATIN SMALL LETTER O WITH ACUTE
ó | o' | LATIN SMALL LETTER O WITH ACUTE
ô | ^o | LATIN SMALL LETTER O WITH CIRCUMFLEX
ô | >o | LATIN SMALL LETTER O WITH CIRCUMFLEX
ô | o> | LATIN SMALL LETTER O WITH CIRCUMFLEX
õ | ~o | LATIN SMALL LETTER O WITH TILDE
õ | o~ | LATIN SMALL LETTER O WITH TILDE
ö | "o | LATIN SMALL LETTER O WITH DIAERESIS
ö | o" | LATIN SMALL LETTER O WITH DIAERESIS
÷ | :- | DIVISION SIGN
÷ | -: | DIVISION SIGN
ø | /o | LATIN SMALL LETTER O WITH STROKE
ù | `u | LATIN SMALL LETTER U WITH GRAVE
ù | u` | LATIN SMALL LETTER U WITH GRAVE
ú | 'u | LATIN SMALL LETTER U WITH ACUTE
ú | u' | LATIN SMALL LETTER U WITH ACUTE
û | ^u | LATIN SMALL LETTER U WITH CIRCUMFLEX
û | >u | LATIN SMALL LETTER U WITH CIRCUMFLEX
û | u> | LATIN SMALL LETTER U WITH CIRCUMFLEX
ü | "u | LATIN SMALL LETTER U WITH DIAERESIS
ü | u" | LATIN SMALL LETTER U WITH DIAERESIS
ý | 'y | LATIN SMALL LETTER Y WITH ACUTE
ý | y' | LATIN SMALL LETTER Y WITH ACUTE
þ | th | LATIN SMALL LETTER THORN
ÿ | "y | LATIN SMALL LETTER Y WITH DIAERESIS
ÿ | y" | LATIN SMALL LETTER Y WITH DIAERESIS
Ā | _A | LATIN CAPITAL LETTER A WITH MACRON
Ā | A_ | LATIN CAPITAL LETTER A WITH MACRON
Ā | -A | LATIN CAPITAL LETTER A WITH MACRON
Ā | A- | LATIN CAPITAL LETTER A WITH MACRON
ā | _a | LATIN SMALL LETTER A WITH MACRON
ā | a_ | LATIN SMALL LETTER A WITH MACRON
ā | -a | LATIN SMALL LETTER A WITH MACRON
ā | a- | LATIN SMALL LETTER A WITH MACRON
Ă | UA | LATIN CAPITAL LETTER A WITH BREVE
Ă | bA | LATIN CAPITAL LETTER A WITH BREVE
ă | Ua | LATIN SMALL LETTER A WITH BREVE
ă | ba | LATIN SMALL LETTER A WITH BREVE
Ą | ;A | LATIN CAPITAL LETTER A WITH OGONEK
Ą | ,A | LATIN CAPITAL LETTER A WITH OGONEK
Ą | A, | LATIN CAPITAL LETTER A WITH OGONEK
ą | ;a | LATIN SMALL LETTER A WITH OGONEK
ą | ,a | LATIN SMALL LETTER A WITH OGONEK
ą | a, | LATIN SMALL LETTER A WITH OGONEK
Ć | 'C | LATIN CAPITAL LETTER C WITH ACUTE
Ć | C' | LATIN CAPITAL LETTER C WITH ACUTE
ć | 'c | LATIN SMALL LETTER C WITH ACUTE
ć | c' | LATIN SMALL LETTER C WITH ACUTE
Ĉ | ^C | LATIN CAPITAL LETTER C WITH CIRCUMFLEX
ĉ | ^c | LATIN SMALL LETTER C WITH CIRCUMFLEX
Č | cC | LATIN CAPITAL LETTER C WITH CARON
Č | <C | LATIN CAPITAL LETTER C WITH CARON
Č | C< | LATIN CAPITAL LETTER C WITH CARON
č | cc | LATIN SMALL LETTER C WITH CARON
č | <c | LATIN SMALL LETTER C WITH CARON
č | c< | LATIN SMALL LETTER C WITH CARON
Ď | cD | LATIN CAPITAL LETTER D WITH CARON
Ď | <D | LATIN CAPITAL LETTER D WITH CARON
Ď | D< | LATIN CAPITAL LETTER D WITH CARON
ď | cd | LATIN SMALL LETTER D WITH CARON
ď | <d | LATIN SMALL LETTER D WITH CARON
ď | d< | LATIN SMALL LETTER D WITH CARON
Đ | -D | Dstroke # LATIN CAPITAL LETTER D WITH STROKE
Đ | D- | Dstroke # LATIN CAPITAL LETTER D WITH STROKE
Đ | /D | Dstroke # LATIN CAPITAL LETTER D WITH STROKE
đ | -d | dstroke # LATIN SMALL LETTER D WITH STROKE
đ | d- | dstroke # LATIN SMALL LETTER D WITH STROKE
đ | /d | dstroke # LATIN SMALL LETTER D WITH STROKE
Ē | _E | LATIN CAPITAL LETTER E WITH MACRON
Ē | E_ | LATIN CAPITAL LETTER E WITH MACRON
Ē | -E | LATIN CAPITAL LETTER E WITH MACRON
Ē | E- | LATIN CAPITAL LETTER E WITH MACRON
ē | _e | LATIN SMALL LETTER E WITH MACRON
ē | e_ | LATIN SMALL LETTER E WITH MACRON
ē | -e | LATIN SMALL LETTER E WITH MACRON
ē | e- | LATIN SMALL LETTER E WITH MACRON
Ĕ | UE | LATIN CAPITAL LETTER E WITH BREVE
Ĕ | bE | LATIN CAPITAL LETTER E WITH BREVE
ĕ | Ue | LATIN SMALL LETTER E WITH BREVE
ĕ | be | LATIN SMALL LETTER E WITH BREVE
Ę | ;E | LATIN CAPITAL LETTER E WITH OGONEK
Ę | ,E | LATIN CAPITAL LETTER E WITH OGONEK
Ę | E, | LATIN CAPITAL LETTER E WITH OGONEK
ę | ;e | LATIN SMALL LETTER E WITH OGONEK
ę | ,e | LATIN SMALL LETTER E WITH OGONEK
ę | e, | LATIN SMALL LETTER E WITH OGONEK
Ě | cE | LATIN CAPITAL LETTER E WITH CARON
Ě | <E | LATIN CAPITAL LETTER E WITH CARON
Ě | E< | LATIN CAPITAL LETTER E WITH CARON
ě | ce | LATIN SMALL LETTER E WITH CARON
ě | <e | LATIN SMALL LETTER E WITH CARON
ě | e< | LATIN SMALL LETTER E WITH CARON
Ĝ | ^G | LATIN CAPITAL LETTER G WITH CIRCUMFLEX
ĝ | ^g | LATIN SMALL LETTER G WITH CIRCUMFLEX
Ğ | UG | LATIN CAPITAL LETTER G WITH BREVE
Ğ | GU | LATIN CAPITAL LETTER G WITH BREVE
Ğ | bG | LATIN CAPITAL LETTER G WITH BREVE
ğ | Ug | LATIN SMALL LETTER G WITH BREVE
ğ | gU | LATIN SMALL LETTER G WITH BREVE
ğ | bg | LATIN SMALL LETTER G WITH BREVE
Ģ | ,G | LATIN CAPITAL LETTER G WITH CEDILLA
Ģ | G, | LATIN CAPITAL LETTER G WITH CEDILLA
ģ | ,g | LATIN SMALL LETTER G WITH CEDILLA
ģ | g, | LATIN SMALL LETTER G WITH CEDILLA
Ĥ | ^H | LATIN CAPITAL LETTER H WITH CIRCUMFLEX
ĥ | ^h | LATIN SMALL LETTER H WITH CIRCUMFLEX
Ħ | /H | LATIN CAPITAL LETTER H WITH STROKE
ħ | /h | LATIN SMALL LETTER H WITH STROKE
Ĩ | ~I | LATIN CAPITAL LETTER I WITH TILDE
Ĩ | I~ | LATIN CAPITAL LETTER I WITH TILDE
ĩ | ~i | LATIN SMALL LETTER I WITH TILDE
ĩ | i~ | LATIN SMALL LETTER I WITH TILDE
Ī | _I | LATIN CAPITAL LETTER I WITH MACRON
Ī | I_ | LATIN CAPITAL LETTER I WITH MACRON
Ī | -I | LATIN CAPITAL LETTER I WITH MACRON
Ī | I- | LATIN CAPITAL LETTER I WITH MACRON
ī | _i | LATIN SMALL LETTER I WITH MACRON
ī | i_ | LATIN SMALL LETTER I WITH MACRON
ī | -i | LATIN SMALL LETTER I WITH MACRON
ī | i- | LATIN SMALL LETTER I WITH MACRON
Ĭ | UI | LATIN CAPITAL LETTER I WITH BREVE
Ĭ | bI | LATIN CAPITAL LETTER I WITH BREVE
ĭ | Ui | LATIN SMALL LETTER I WITH BREVE
ĭ | bi | LATIN SMALL LETTER I WITH BREVE
Į | ;I | LATIN CAPITAL LETTER I WITH OGONEK
Į | ,I | LATIN CAPITAL LETTER I WITH OGONEK
Į | I, | LATIN CAPITAL LETTER I WITH OGONEK
į | ;i | LATIN SMALL LETTER I WITH OGONEK
į | ,i | LATIN SMALL LETTER I WITH OGONEK
į | i, | LATIN SMALL LETTER I WITH OGONEK
ı | i. | LATIN SMALL LETTER DOTLESS I
ı | .i | LATIN SMALL LETTER DOTLESS I
Ĵ | ^J | LATIN CAPITAL LETTER J WITH CIRCUMFLEX
ĵ | ^j | LATIN SMALL LETTER J WITH CIRCUMFLEX
Ķ | ,K | LATIN CAPITAL LETTER K WITH CEDILLA
Ķ | K, | LATIN CAPITAL LETTER K WITH CEDILLA
ķ | ,k | LATIN SMALL LETTER K WITH CEDILLA
ķ | k, | LATIN SMALL LETTER K WITH CEDILLA
ĸ | kk | LATIN SMALL LETTER KRA
Ĺ | 'L | LATIN CAPITAL LETTER L WITH ACUTE
Ĺ | L' | LATIN CAPITAL LETTER L WITH ACUTE
ĺ | 'l | LATIN SMALL LETTER L WITH ACUTE
ĺ | l' | LATIN SMALL LETTER L WITH ACUTE
Ļ | ,L | LATIN CAPITAL LETTER L WITH CEDILLA
Ļ | L, | LATIN CAPITAL LETTER L WITH CEDILLA
ļ | ,l | LATIN SMALL LETTER L WITH CEDILLA
ļ | l, | LATIN SMALL LETTER L WITH CEDILLA
Ľ | cL | LATIN CAPITAL LETTER L WITH CARON
Ľ | <L | LATIN CAPITAL LETTER L WITH CARON
Ľ | L< | LATIN CAPITAL LETTER L WITH CARON
ľ | cl | LATIN SMALL LETTER L WITH CARON
ľ | <l | LATIN SMALL LETTER L WITH CARON
ľ | l< | LATIN SMALL LETTER L WITH CARON
Ł | /L | LATIN CAPITAL LETTER L WITH STROKE
Ł | L/ | LATIN CAPITAL LETTER L WITH STROKE
ł | /l | LATIN SMALL LETTER L WITH STROKE
ł | l/ | LATIN SMALL LETTER L WITH STROKE
Ń | 'N | LATIN CAPITAL LETTER N WITH ACUTE
Ń | N' | LATIN CAPITAL LETTER N WITH ACUTE
ń | 'n | LATIN SMALL LETTER N WITH ACUTE
ń | n' | LATIN SMALL LETTER N WITH ACUTE
Ņ | ,N | LATIN CAPITAL LETTER N WITH CEDILLA
Ņ | N, | LATIN CAPITAL LETTER N WITH CEDILLA
ņ | ,n | LATIN SMALL LETTER N WITH CEDILLA
ņ | n, | LATIN SMALL LETTER N WITH CEDILLA
Ň | cN | LATIN CAPITAL LETTER N WITH CARON
Ň | <N | LATIN CAPITAL LETTER N WITH CARON
Ň | N< | LATIN CAPITAL LETTER N WITH CARON
ň | cn | LATIN SMALL LETTER N WITH CARON
ň | <n | LATIN SMALL LETTER N WITH CARON
ň | n< | LATIN SMALL LETTER N WITH CARON
Ŋ | NG | LATIN CAPITAL LETTER ENG
ŋ | ng | LATIN SMALL LETTER ENG
Ō | _O | LATIN CAPITAL LETTER O WITH MACRON
Ō | O_ | LATIN CAPITAL LETTER O WITH MACRON
Ō | -O | LATIN CAPITAL LETTER O WITH MACRON
Ō | O- | LATIN CAPITAL LETTER O WITH MACRON
ō | _o | LATIN SMALL LETTER O WITH MACRON
ō | o_ | LATIN SMALL LETTER O WITH MACRON
ō | -o | LATIN SMALL LETTER O WITH MACRON
ō | o- | LATIN SMALL LETTER O WITH MACRON
Ŏ | UO | LATIN CAPITAL LETTER O WITH BREVE
Ŏ | bO | LATIN CAPITAL LETTER O WITH BREVE
ŏ | Uo | LATIN SMALL LETTER O WITH BREVE
ŏ | bo | LATIN SMALL LETTER O WITH BREVE
Ő | =O | LATIN CAPITAL LETTER O WITH DOUBLE ACUTE
ő | =o | LATIN SMALL LETTER O WITH DOUBLE ACUTE
Œ | OE | OE # LATIN CAPITAL LIGATURE OE
œ | oe | oe # LATIN SMALL LIGATURE OE
Ŕ | 'R | LATIN CAPITAL LETTER R WITH ACUTE
Ŕ | R' | LATIN CAPITAL LETTER R WITH ACUTE
ŕ | 'r | LATIN SMALL LETTER R WITH ACUTE
ŕ | r' | LATIN SMALL LETTER R WITH ACUTE
Ŗ | ,R | LATIN CAPITAL LETTER R WITH CEDILLA
ŗ | ,r | LATIN SMALL LETTER R WITH CEDILLA
Ř | cR | LATIN CAPITAL LETTER R WITH CARON
Ř | <R | LATIN CAPITAL LETTER R WITH CARON
Ř | R< | LATIN CAPITAL LETTER R WITH CARON
ř | cr | LATIN SMALL LETTER R WITH CARON
ř | <r | LATIN SMALL LETTER R WITH CARON
ř | r< | LATIN SMALL LETTER R WITH CARON
Ś | 'S | LATIN CAPITAL LETTER S WITH ACUTE
Ś | S' | LATIN CAPITAL LETTER S WITH ACUTE
ś | 's | LATIN SMALL LETTER S WITH ACUTE
ś | s' | LATIN SMALL LETTER S WITH ACUTE
Ŝ | ^S | LATIN CAPITAL LETTER S WITH CIRCUMFLEX
ŝ | ^s | LATIN SMALL LETTER S WITH CIRCUMFLEX
Ş | ,S | LATIN CAPITAL LETTER S WITH CEDILLA
Ş | S, | LATIN CAPITAL LETTER S WITH CEDILLA
ş | ,s | LATIN SMALL LETTER S WITH CEDILLA
ş | s, | LATIN SMALL LETTER S WITH CEDILLA
Š | cS | LATIN CAPITAL LETTER S WITH CARON
Š | <S | LATIN CAPITAL LETTER S WITH CARON
Š | S< | LATIN CAPITAL LETTER S WITH CARON
š | cs | LATIN SMALL LETTER S WITH CARON
š | <s | LATIN SMALL LETTER S WITH CARON
š | s< | LATIN SMALL LETTER S WITH CARON
Ţ | ,T | LATIN CAPITAL LETTER T WITH CEDILLA
Ţ | T, | LATIN CAPITAL LETTER T WITH CEDILLA
ţ | ,t | LATIN SMALL LETTER T WITH CEDILLA
ţ | t, | LATIN SMALL LETTER T WITH CEDILLA
Ť | cT | LATIN CAPITAL LETTER T WITH CARON
Ť | <T | LATIN CAPITAL LETTER T WITH CARON
Ť | T< | LATIN CAPITAL LETTER T WITH CARON
ť | ct | LATIN SMALL LETTER T WITH CARON
ť | <t | LATIN SMALL LETTER T WITH CARON
ť | t< | LATIN SMALL LETTER T WITH CARON
Ŧ | /T | LATIN CAPITAL LETTER T WITH STROKE
Ŧ | T/ | LATIN CAPITAL LETTER T WITH STROKE
Ŧ | T- | LATIN CAPITAL LETTER T WITH STROKE
ŧ | /t | LATIN SMALL LETTER T WITH STROKE
ŧ | t/ | LATIN SMALL LETTER T WITH STROKE
ŧ | t- | LATIN SMALL LETTER T WITH STROKE
Ũ | ~U | LATIN CAPITAL LETTER U WITH TILDE
Ũ | U~ | LATIN CAPITAL LETTER U WITH TILDE
ũ | ~u | LATIN SMALL LETTER U WITH TILDE
ũ | u~ | LATIN SMALL LETTER U WITH TILDE
Ū | _U | LATIN CAPITAL LETTER U WITH MACRON
Ū | U_ | LATIN CAPITAL LETTER U WITH MACRON
Ū | -U | LATIN CAPITAL LETTER U WITH MACRON
Ū | U- | LATIN CAPITAL LETTER U WITH MACRON
ū | _u | LATIN SMALL LETTER U WITH MACRON
ū | u_ | LATIN SMALL LETTER U WITH MACRON
ū | -u | LATIN SMALL LETTER U WITH MACRON
ū | u- | LATIN SMALL LETTER U WITH MACRON
Ŭ | UU | LATIN CAPITAL LETTER U WITH BREVE
Ŭ | bU | LATIN CAPITAL LETTER U WITH BREVE
ŭ | Uu | LATIN SMALL LETTER U WITH BREVE
ŭ | bu | LATIN SMALL LETTER U WITH BREVE
Ů | oU | LATIN CAPITAL LETTER U WITH RING ABOVE
Ů | *U | LATIN CAPITAL LETTER U WITH RING ABOVE
Ů | U* | LATIN CAPITAL LETTER U WITH RING ABOVE
ů | ou | LATIN SMALL LETTER U WITH RING ABOVE
ů | *u | LATIN SMALL LETTER U WITH RING ABOVE
ů | u* | LATIN SMALL LETTER U WITH RING ABOVE
Ű | =U | LATIN CAPITAL LETTER U WITH DOUBLE ACUTE
ű | =u | LATIN SMALL LETTER U WITH DOUBLE ACUTE
Ų | ;U | LATIN CAPITAL LETTER U WITH OGONEK
Ų | ,U | LATIN CAPITAL LETTER U WITH OGONEK
Ų | U, | LATIN CAPITAL LETTER U WITH OGONEK
ų | ;u | LATIN SMALL LETTER U WITH OGONEK
ų | ,u | LATIN SMALL LETTER U WITH OGONEK
ų | u, | LATIN SMALL LETTER U WITH OGONEK
Ŵ | ^W | LATIN CAPITAL LETTER W WITH CIRCUMFLEX
Ŵ | W^ | LATIN CAPITAL LETTER W WITH CIRCUMFLEX
ŵ | ^w | LATIN SMALL LETTER W WITH CIRCUMFLEX
ŵ | w^ | LATIN SMALL LETTER W WITH CIRCUMFLEX
Ŷ | ^Y | LATIN CAPITAL LETTER Y WITH CIRCUMFLEX
Ŷ | Y^ | LATIN CAPITAL LETTER Y WITH CIRCUMFLEX
ŷ | ^y | LATIN SMALL LETTER Y WITH CIRCUMFLEX
ŷ | y^ | LATIN SMALL LETTER Y WITH CIRCUMFLEX
Ÿ | "Y | LATIN CAPITAL LETTER Y WITH DIAERESIS
Ÿ | Y" | LATIN CAPITAL LETTER Y WITH DIAERESIS
Ź | 'Z | LATIN CAPITAL LETTER Z WITH ACUTE
Ź | Z' | LATIN CAPITAL LETTER Z WITH ACUTE
ź | 'z | LATIN SMALL LETTER Z WITH ACUTE
ź | z' | LATIN SMALL LETTER Z WITH ACUTE
Ž | cZ | LATIN CAPITAL LETTER Z WITH CARON
Ž | vZ | LATIN CAPITAL LETTER Z WITH CARON
Ž | <Z | LATIN CAPITAL LETTER Z WITH CARON
Ž | Z< | LATIN CAPITAL LETTER Z WITH CARON
ž | cz | LATIN SMALL LETTER Z WITH CARON
ž | vz | LATIN SMALL LETTER Z WITH CARON
ž | <z | LATIN SMALL LETTER Z WITH CARON
ž | z< | LATIN SMALL LETTER Z WITH CARON
ſ | fs | LATIN SMALL LETTER LONG S
ſ | fS | LATIN SMALL LETTER LONG S
ƀ | /b | LATIN SMALL LETTER B WITH STROKE
Ɨ | /I | LATIN CAPITAL LETTER I WITH STROKE
Ơ | +O | LATIN CAPITAL LETTER O WITH HORN
ơ | +o | LATIN SMALL LETTER O WITH HORN
Ư | +U | LATIN CAPITAL LETTER U WITH HORN
ư | +u | LATIN SMALL LETTER U WITH HORN
Ƶ | /Z | LATIN CAPITAL LETTER Z WITH STROKE
ƶ | /z | LATIN SMALL LETTER Z WITH STROKE
Ǎ | cA | LATIN CAPITAL LETTER A WITH CARON
ǎ | ca | LATIN SMALL LETTER A WITH CARON
Ǐ | cI | LATIN CAPITAL LETTER I WITH CARON
ǐ | ci | LATIN SMALL LETTER I WITH CARON
Ǒ | cO | LATIN CAPITAL LETTER O WITH CARON
ǒ | co | LATIN SMALL LETTER O WITH CARON
Ǔ | cU | LATIN CAPITAL LETTER U WITH CARON
ǔ | cu | LATIN SMALL LETTER U WITH CARON
Ǥ | /G | LATIN CAPITAL LETTER G WITH STROKE
ǥ | /g | LATIN SMALL LETTER G WITH STROKE
Ǧ | cG | LATIN CAPITAL LETTER G WITH CARON
ǧ | cg | LATIN SMALL LETTER G WITH CARON
Ǩ | cK | LATIN CAPITAL LETTER K WITH CARON
ǩ | ck | LATIN SMALL LETTER K WITH CARON
Ǫ | ;O | LATIN CAPITAL LETTER O WITH OGONEK
ǫ | ;o | LATIN SMALL LETTER O WITH OGONEK
ǰ | cj | LATIN SMALL LETTER J WITH CARON
Ǵ | 'G | LATIN CAPITAL LETTER G WITH ACUTE
ǵ | 'g | LATIN SMALL LETTER G WITH ACUTE
Ǹ | `N | LATIN CAPITAL LETTER N WITH GRAVE
ǹ | `n | LATIN SMALL LETTER N WITH GRAVE
Ȟ | cH | LATIN CAPITAL LETTER H WITH CARON
ȟ | ch | LATIN SMALL LETTER H WITH CARON
Ȩ | ,E | LATIN CAPITAL LETTER E WITH CEDILLA
ȩ | ,e | LATIN SMALL LETTER E WITH CEDILLA
Ȳ | _Y | LATIN CAPITAL LETTER Y WITH MACRON
ȳ | _y | LATIN SMALL LETTER Y WITH MACRON
ə | ee | LATIN SMALL LETTER SCHWA
ɨ | /i | LATIN SMALL LETTER I WITH STROKE
Ḑ | ,D | LATIN CAPITAL LETTER D WITH CEDILLA
Ḑ | D, | LATIN CAPITAL LETTER D WITH CEDILLA
ḑ | ,d | LATIN SMALL LETTER D WITH CEDILLA
ḑ | d, | LATIN SMALL LETTER D WITH CEDILLA
Ḡ | _G | LATIN CAPITAL LETTER G WITH MACRON
ḡ | _g | LATIN SMALL LETTER G WITH MACRON
Ḧ | "H | LATIN CAPITAL LETTER H WITH DIAERESIS
ḧ | "h | LATIN SMALL LETTER H WITH DIAERESIS
Ḩ | ,H | LATIN CAPITAL LETTER H WITH CEDILLA
Ḩ | H, | LATIN CAPITAL LETTER H WITH CEDILLA
ḩ | ,h | LATIN SMALL LETTER H WITH CEDILLA
ḩ | h, | LATIN SMALL LETTER H WITH CEDILLA
Ḱ | 'K | LATIN CAPITAL LETTER K WITH ACUTE
ḱ | 'k | LATIN SMALL LETTER K WITH ACUTE
Ḿ | 'M | LATIN CAPITAL LETTER M WITH ACUTE
ḿ | 'm | LATIN SMALL LETTER M WITH ACUTE
Ṕ | 'P | LATIN CAPITAL LETTER P WITH ACUTE
ṕ | 'p | LATIN SMALL LETTER P WITH ACUTE
Ṽ | ~V | LATIN CAPITAL LETTER V WITH TILDE
ṽ | ~v | LATIN SMALL LETTER V WITH TILDE
Ẁ | `W | LATIN CAPITAL LETTER W WITH GRAVE
ẁ | `w | LATIN SMALL LETTER W WITH GRAVE
Ẃ | 'W | LATIN CAPITAL LETTER W WITH ACUTE
ẃ | 'w | LATIN SMALL LETTER W WITH ACUTE
Ẅ | "W | LATIN CAPITAL LETTER W WITH DIAERESIS
ẅ | "w | LATIN SMALL LETTER W WITH DIAERESIS
Ẍ | "X | LATIN CAPITAL LETTER X WITH DIAERESIS
ẍ | "x | LATIN SMALL LETTER X WITH DIAERESIS
Ẑ | ^Z | LATIN CAPITAL LETTER Z WITH CIRCUMFLEX
ẑ | ^z | LATIN SMALL LETTER Z WITH CIRCUMFLEX
ẗ | "t | LATIN SMALL LETTER T WITH DIAERESIS
ẘ | ow | LATIN SMALL LETTER W WITH RING ABOVE
ẙ | oy | LATIN SMALL LETTER Y WITH RING ABOVE
Ẽ | ~E | LATIN CAPITAL LETTER E WITH TILDE
ẽ | ~e | LATIN SMALL LETTER E WITH TILDE
Ỳ | `Y | LATIN CAPITAL LETTER Y WITH GRAVE
ỳ | `y | LATIN SMALL LETTER Y WITH GRAVE
Ỹ | ~Y | LATIN CAPITAL LETTER Y WITH TILDE
ỹ | ~y | LATIN SMALL LETTER Y WITH TILDE
&puncsp; | " ." | PUNCTUATION SPACE (space period)
– | --. | EN DASH
— | --- | EM DASH
‘ | <' | LEFT SINGLE QUOTATION MARK
‘ | '< | LEFT SINGLE QUOTATION MARK
’ | >' | RIGHT SINGLE QUOTATION MARK
’ | '> | RIGHT SINGLE QUOTATION MARK
‚ | ,' | SINGLE LOW-9 QUOTATION MARK
‚ | ', | SINGLE LOW-9 QUOTATION MARK
“ | <" | LEFT DOUBLE QUOTATION MARK
“ | "< | LEFT DOUBLE QUOTATION MARK
” | >" | RIGHT DOUBLE QUOTATION MARK
” | "> | RIGHT DOUBLE QUOTATION MARK
„ | ," | DOUBLE LOW-9 QUOTATION MARK
„ | ", | DOUBLE LOW-9 QUOTATION MARK
‰ | %o | PER MILLE SIGN
› | .> | SINGLE RIGHT-POINTING ANGLE QUOTATION MARK
‹ | .< | SINGLE LEFT-POINTING ANGLE QUOTATION MARK
‽ | !? | INTERROBANG
⁰ | ^0 | SUPERSCRIPT ZERO
ⁱ | ^_i | SUPERSCRIPT LATIN SMALL LETTER I
⁴ | ^4 | SUPERSCRIPT FOUR
⁵ | ^5 | SUPERSCRIPT FIVE
⁶ | ^6 | SUPERSCRIPT SIX
⁷ | ^7 | SUPERSCRIPT SEVEN
⁸ | ^8 | SUPERSCRIPT EIGHT
⁹ | ^9 | SUPERSCRIPT NINE
⁺ | ^+ | SUPERSCRIPT PLUS SIGN
⁼ | ^= | SUPERSCRIPT EQUALS SIGN
⁽ | ^( | SUPERSCRIPT LEFT PARENTHESIS
⁾ | ^) | SUPERSCRIPT RIGHT PARENTHESIS
ⁿ | ^_n | SUPERSCRIPT LATIN SMALL LETTER N
₀ | _0 | SUBSCRIPT ZERO
₁ | _1 | SUBSCRIPT ONE
₂ | _2 | SUBSCRIPT TWO
₃ | _3 | SUBSCRIPT THREE
₄ | _4 | SUBSCRIPT FOUR
₅ | _5 | SUBSCRIPT FIVE
₆ | _6 | SUBSCRIPT SIX
₇ | _7 | SUBSCRIPT SEVEN
₈ | _8 | SUBSCRIPT EIGHT
₉ | _9 | SUBSCRIPT NINE
₊ | _+ | SUBSCRIPT PLUS SIGN
₌ | _= | SUBSCRIPT EQUALS SIGN
₍ | _( | SUBSCRIPT LEFT PARENTHESIS
₎ | _) | SUBSCRIPT RIGHT PARENTHESIS
₠ | CE | EURO-CURRENCY SIGN
₡ | C/ | COLON SIGN
₡ | /C | COLON SIGN
₢ | Cr | CRUZEIRO SIGN
₣ | Fr | FRENCH FRANC SIGN
₤ | L= | LIRA SIGN
₤ | =L | LIRA SIGN
₥ | m/ | MILL SIGN
₥ | /m | MILL SIGN
₦ | N= | NAIRA SIGN
₦ | =N | NAIRA SIGN
₧ | Pt | PESETA SIGN
₨ | Rs | RUPEE SIGN
₩ | W= | WON SIGN
₩ | =W | WON SIGN
₫ | d- | DONG SIGN
€ | C= | EuroSign # EURO SIGN
€ | =C | EuroSign # EURO SIGN
€ | c= | EuroSign # EURO SIGN
€ | =c | EuroSign # EURO SIGN
€ | E= | EuroSign # EURO SIGN
€ | =E | EuroSign # EURO SIGN
℠ | SM | SERVICE MARK
℠ | sM | SERVICE MARK
℠ | Sm | SERVICE MARK
℠ | sm | SERVICE MARK
™ | TM | TRADE MARK SIGN
™ | tM | TRADE MARK SIGN
™ | TM | TRADE MARK SIGN
™ | tm | TRADE MARK SIGN
← | <- | LEFTWARDS ARROW
→ | -> | RIGHTWARDS ARROW
≤ | <= | LESS-THAN OR EQUAL TO
≥ | >= | GREATER-THAN OR EQUAL TO
≠ | /= | NOT EQUAL TO
≠ | =/ | NOT EQUAL TO
⸘ | ?! | INVERTED INTERROBANG
〝 | \\ | REVERSED DOUBLE PRIME QUOTATION MARK (not defined by Xlib)
〞 | // | DOUBLE PRIME QUOTATION MARK (not defined by Xlib)
