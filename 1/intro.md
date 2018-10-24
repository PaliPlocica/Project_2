# Ako vygenerovat kluc cez terminal. Na miesto emailu pisat svoj email, podla uloziska, napr github 
1. prikaz (terminal): `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
2. treba 3x potvrdit enterom  <br>
3. otvorime si bash terminal a v nom zadame tento prikaz, ktory spusti ssh agenta na pozadi: `eval $(ssh-agent -s)`
4. tymto prikazom ssh sukromny kluc sa prida do ssh agenta: `ssh-add ~/.ssh/id_rsa`<!-- > v bashi -->
5. tymto prikazom sa skopiruje ssh kluc do copy to clipboard: `clip < ~/.ssh/id_rsa.pub`<!-- > v bashi, dam ctrl+v -->
6. treba ist na web stranku kde je nase ulozisko, bud github/gitlab, alebo bitbutcket a v settingoch svojho profilu vlozit svoj skopirovany kluc: [adresa kde pridam ssh kluc](https://github.com/settings/keys) <br>
#
## Skratky <br>
* ctrl + / = `comments`
* windows + space = `change languages`
* ctrl + +/- = `zoom`
* ctrl + B = `open/close window on the left side`
* ctrl + shift + M = `open or close TERMINAL`
* ctrl + shift + V = `visual view`
* cd_nazov priecinku = `open folder` <!-- v terminale iba v danom priecinku: cd ./Fico je kkt -->
* cd_.. = `out from the folder`
* cd + TAB = `open folder, which I want`
* ls = `show what´s in the folder`
* mkdir_nazov priecinku = `create new folder`
* rmdir_nazov priecinku = `delete folder`
* ctrl + z/y = `back/front`
* echo_"text", ktory chcem vlozit do filu, musi byt oznaceny uvodzovkami + sipka do prava (>) + nazov.typ filu (.md, .txt) = `insert text`

## markdown 
[info](https://cs.wikipedia.org/wiki/Markdown?fbclid=IwAR1NQRssgvX1-xJSZG8HNADYcqovBGpcd_3b__DZg6HJ2QXeUcONkyAJtBg)

Hlavní nadpis <br>
==========
<!-- hviezdicka pred textm prida odsek -->
* toto
* je
* seznam

Menší podnadpis
---------------

1. toto 
2. se čísluje
1. ale na číslech nezáleží

# Hlavní nadpis jinak

## Menší nadpis jinak

### Ještě menší nadpis jinak

Odstavce se oddělují
prázdným řádkem. Na délce řádků nezáleží

Udělám nový odstavec. Ještě odkaz na 
[dokumentaci](http://daringfireball.net/projects/markdown/syntax)

Horizontální oddělovač:
---

Vlastnosti textu _kurzíva_, *kurzíva*, __tučně__, **tučně**, `neproporcionální`.

<p>Dle libosti <em>můžu používat</em> html</p>

Nebo obrázek 
![Alt text](https://commons.wikimedia.org/wiki/File:Markdown-mark.svg)

[odstavec]: http://cs.wikipedia.org/wiki/odstavec

Konec řádku uprostřed [odstavce][odstavec]      
se udělá  
pomocí několika mezer na konci řádku.

<http://cs.wikipedia.org>


## bash
[info](https://sk.wikipedia.org/wiki/Bash?fbclid=IwAR33XvqNdXTsIYB2elGVcG8AC2kCpe7eKKSMXQ8N37D4_qxi9Udx1rnMIik)

<!-- ? PRE LUKASA!!! -->
