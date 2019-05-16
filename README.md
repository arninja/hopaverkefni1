# Hópverkefni 1


Unnið af:
- Arnari Inga Njarðarsyni
    - (ain1@hi.is)
- Árna Frey Magnússyni
    - (afm7@hi.is)
- Braga Arnarsyni
  - (bra26@hi.is)

[Hér má sjá verkefnið okkar á heimasvæði háskólans](https://notendur.hi.is/bra26/vefforritun/Hopverkefni1/)

# Verkefnalýsing
---
---
Í pages möppunni er að finna HTML fyrir allar fjórar síðurnar;
- `Index.html`
- `Products.html`
- `Staff.html`
- `Cart.html`


Á sama máta má finna scss skrár fyrir allar síðurnar;
- `Index.scss`
- `Products.scss`
- `Staff.scss`
- `Cart.scss`

Í .scss möppunni ásamt `config.scss` sem skilgreinir breytur og `header.scss` og `footer.scss` sem eiga við staðlaðan haus og fót allra síðnanna.



Allar síðurnar nota sama `styles.scss` sem sækir allar hinar `.scss`  skrárnar og breytir í `.css` skrá með `npm script` að nafni `sass`


Kóðinn í html er eins upp settur á öllum síðum, skiptist í header, main og footer.
Í main er öllu raðað með flexbox og þ.a.l. skipt í viðeigandi hópa í html og stýrt með css.


Grunnstærð leturs er `16px` og litapallettan er `#000000`, `#ffffff`, `#afb281`, `#cee8ff`, `#fcffd2` og `#cc9694` og við útbjóum breytur fyrir hvern lit í sass; `$black`, `$white`, `$green`, `$lightblue`, `$yellow` og `$pink`
Öll bil eru margfeldi af `20px` og það grunnbil er skilgreint með `$gutter`


Allar myndir eru geymdar í möppuni `img` og allur texti er geymdur í `efni` möppunni.

### Haus og fótur
---
Haus og fótur eru eins á öllum síðum, bæði HTML og með sér `.scss` skrár hvor fyrir sig.


Hausinn samanstendur af titli, hlekkjum á forsíðu/vörur/starfsfólk og körfu
Hausinn skalar í `560 px` vídd og fer þá karfan undan hlekkjunum og fer í sömu línu með hinum hlekkjunum.


Fóturinn samanstendur af 4 hlekkjahópum, hver með sinn titil. Allir raða þeir sér eins innbyrðis og verða ýmist 1, 2 eða fjórir í línu í viðeigandi vídd.  `>500 px og >800 px`

### Forsíða
---
Forsíða eða index, samanstendur af tveimur hópum, hver samanstendur af mynd og lýsingu. Hóparnir raðast í röð en hver hópur raðar innbyrðis hópum í súlu þegar víddin er lítil `>800px`.
Lýsingarnar gefur stutta lýsingu á vörusíðunni ásamt hlekk á vörusíðuna eins vegar og lýsingu og hlekk á starfsmannasíðuna hins vegar.
Í lýsingunni er titill, texti og takki, titill situr efst og takkinn neðst.


### Vörur
---
Vörur eða products, er síða sem sýnir allar þær fallegu vörur sem Vöruhúsið býður upp á.
Síðan samanstendur af sex hópum, hver með mynd og lýsingu og hópunum er raðað í röð; 1,2 eða 3 í röð við viðeigandi vídd.
Í hverri lýsingu er titill, texti og form ásamt tveimur tökkum með körfumerki á.


### Starfsfólk
---
Stafsfólk eða staff, er síða sem sýnir flotta starfskraft Vöruhússins.
Síðan samanstendur af fjórum hópum sem eru mynd en ef músin er höfð yfir skreppur myndin saman og sýnir í stað nafn og lýsingu viðeigandi starfsmanns.
Hóparnir raðast í röð og eru 1 eða tveir hópar í hverri röð, fer eftir vídd.

### Karfa
---
Karfa eða cart, er síða sem sýnir þær vörur sem notandi hefur sett þangað og tekur inn greiðslupplýsingar og sendingarupplýsingar.
Síðan samanstendur af tveimur stórum hópum, vörur og upplýsingar.

Í vörum eru tveir hópar, mynd og lýsing og í lýsingu eru tveir hópar, haus og fótur lýsingarinnar. Hausinn inniheldur titil eða heiti vörunnar ásamt textalýsingu og fóturinn inniheldur verð og textaform ásamt tveimur tökkum með körfumerki.

Í upplýsingum eru tveir hópar, greiðsluupplýsingar og sendingarupplýsingar sem hvor inniheldur þrjú form ásamt merkingu. Í sendingarupplýsingum er beðið um nafn, heimilisfang og póstfang. Póstfangið inniheldur öll íslensk póstnúmer ásamt staðsetningu þess í valmyndarlista.
Í greiðsluupplýsingum er beðið um nafn korthafa, kortanúmer og gildistíma.
