<!-- Ako vygenerovat kluc cez terminal
namiesto emailu pisat svoj email, podla uloziska, napr github -->

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
<!-- treba 3x potvrdit enterom -->
<!-- otvorime si bash terminal  -->
eval $(ssh-agent -s)
<!-- tento prikaz spusti ssh agenta na pozadi -->
ssh-add ~/.ssh/id_rsa
<!-- prida svoj ssh sukromny kluc do ssh agenta -->
clip < ~/.ssh/id_rsa.pub
<!-- toto skopiruje ssh kluc do copy to clipboard -->
https://github.com/settings/keys
<!-- treba ist na web stranku kde je nase ulozisko, bud github, alebo bitbutcket a v settingoch svojho profilu vlozit svoj skopirovany kluc -->