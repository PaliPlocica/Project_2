# Ako vygenerovat kluc cez terminal. Na miesto emailu pisat svoj email, podla uloziska, napr github 
1. prikaz (terminal): `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
2. treba 3x potvrdit enterom  <br>
3. otvorime si bash terminal a v nom zadame tento prikaz, ktory spusti ssh agenta na pozadi: `eval $(ssh-agent -s)`
4. tymto prikazom ssh sukromny kluc sa prida do ssh agenta: `ssh-add ~/.ssh/id_rsa`<!-- > v bashi -->
5. tymto prikazom sa skopiruje ssh kluc do copy to clipboard: `clip < ~/.ssh/id_rsa.pub`<!-- > v bashi, dam ctrl+v -->
6. treba ist na web stranku kde je nase ulozisko, bud github/gitlab, alebo bitbutcket a v settingoch svojho profilu vlozit svoj skopirovany kluc: [adresa kde pridam ssh kluc](https://github.com/settings/keys) <br>
#
## Skratky <br>
* crtl + shift + i - html
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

