
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 

Добро пожаловать на курс Python для сетевых инженеров!

В этой виртуальной машине уже установлены пакеты, которые нужны для курса
и создано виртуальное окружение pyneng-py3.

## Виртуальное окружение

Все модули, которые нужны в курсе, установлены в  [виртуальном окружении](https://natenka.gitbooks.io/pyneng/content/v/python3.6/book/01_intro/virtualenv.html) pyneng-py3.

Перейти в виртуальное окружение:
```
workon pyneng-py3
```

Выйти из виртуального окружения:
```
deactivate
```

## Репозиторий курса

В виртуальную машину скопирован репозиторий курса.
Можно попробовать запустить скрипт из примеров курса таким образом:
```
$ cd pyneng-online-sep-oct-2017/examples/05_control_structures/
$ python generate_access_port_config.py 
interface FastEthernet0/12
 switchport mode access
 switchport access vlan 10
 spanning-tree portfast
 spanning-tree bpduguard enable
interface FastEthernet0/17
 switchport mode access
 switchport access vlan 150
 spanning-tree portfast
 spanning-tree bpduguard enable
interface FastEthernet0/14
 switchport mode access
 switchport access vlan 11
 spanning-tree portfast
 spanning-tree bpduguard enable
interface FastEthernet0/16
 switchport mode access
 switchport access vlan 17
 spanning-tree portfast
 spanning-tree bpduguard enable
```

Или открыть этот файл в дереве файлов слева и нажать кнопку Run.


## Support & Documentation

Visit http://docs.c9.io for support, or to learn more about using Cloud9 IDE.
To watch some training videos, visit http://www.youtube.com/user/c9ide.
AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
####
#$$%
7777