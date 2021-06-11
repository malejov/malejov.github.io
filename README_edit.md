Jak editovat web?
=================

Markdown
--------

- Markdown je formát `.md` souborů, popř. je možný i HTML s většími možnostmi formátování.
- Online editor: https://markdown-editor.github.io
- Základy: https://www.markdownguide.org/cheat-sheet
- K vytištění: https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf


Jak editovat existující stránku?
-------------------------------

- Každá stránka má dole odkaz `Editovat tuto stránku`.
- Přesměruje na GitHub, kde je vpravo nahoře ikona tužky `Edit this file`. (Je třeba se přihlásit pokud není.)
- Nebo ji najít ručně v adresářové struktuře na  https://github.com/malejov/malejov.github.io.
- Editovat, případně je nahoře i `Preview changes`, a pak dole kliknout na `Commit changes`.


Jak přidat obrázek?
-------------------

- V grafickém editoru je třeba si nejdřív připravit obrázek.
    - Obrovské fotky zmenšit např. na velikost 1000 px.
    - Online editor je např. na https://www.photopea.com.
- V adresáři s obrázky https://github.com/malejov/malejov.github.io/tree/master/assets nebo v nějakém jeho podadresáři kliknout na `Add file` a `Upload files`.
- Do libovolné stránky se pak můžou přidat pomocí následujícího kódu.

```
![titulek](cesta k obrázku)

![Pozvánka na masopust](/assets/article_images/masopust.jpg)
```


Jak přidat novou stránku?
-------------------------

- Na https://github.com/malejov/malejov.github.io je vidět adresářová struktura, najít správné místo.
- Nahoře kliknout na `Add file`, `Create new file`. (Je třeba se přihlásit pokud není.)
- Nahoře zadat jméno souboru, většinou s příponou `.md`. 
- Vytvořit obsah. Nejjednodušší bývá přes schránku zkopírovat něco existujícího, co má podobnou strukturu a upravovat.
- Dole kliknout na `Commit new file`.


Jak přidat novinku?
-------------------

- Úplně stejně jako novou stránku.
- Jsou v adresáři https://github.com/malejov/malejov.github.io/tree/master/_posts.
- Jméno souboru má strukturu `YYYY-MM-DD-kratky-popis.md`, např. `2020-01-21-masopust.md`.
- Nahoře je hlavička a pak už jenom text, který se zobrazí.

```
---
layout: post
title:  Pozvánka na masopust
tags:   pozvánka
---

V. Fabiáno-Šebestiánský dětský masopust se bude konat v sobotu 15. 2. 2020.

![Pozvánka na masopust](/assets/article_images/masopust.jpg)
```
