# latex_note
latex_note_zh_CN

### commit with gpg

      gpg --full-generate-key
      gpg --list-secret-keys --keyid-format LONG
      gpg --armor --export 3AA5C34371567BD2  #id
Adding a new GPG key to your GitHub account

      git config --global user.signingkey 3AA5C34371567BD2
      git config --global commit.gpgsign true #每次都开启
