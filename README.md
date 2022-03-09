# Git
- *date >> README.md*
- *git add README.md*
## Git add
### работает одинаково из любой директории, добавляет всю рабочую область
-*git add :/*
### путь относительно корневой директории
-*git add :/path/to/files/*
### работает только в текущей директории
-*cd test*
-*git add .*
### эквивалентно этому:
-*git add :/test*
### путь относительно текущей директории
-*cd test*
-*git add ./path*
### эквивалентно этому:
-*git add :/test/path*
###
- *git commit -m "added date"*
- *git push*

## git remote -v

- *origin  https://github.com/sendelufa/tutorial-ssh.git (fetch)*
- *origin  https://github.com/sendelufa/tutorial-ssh.git (push)*

### HTTPS to SSH
## git remote rm origin
- *git remote add origin git@github.com:sendelufa/tutorial-ssh.git* 

9 мар 2022 г. 23:50:58
