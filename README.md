# Cinnamon-Budgie-Linux-OS-18-based-19.04-Ubuntu-Pop требуется флешка на 4 гигабайта вес iso 3Гб 

Update Cinnamon-Budgie-Linux-OS-18-based-19.04-Ubuntu-Pop X64 Android + новое дополненное меню + my skel setting + Android

______________________________________________________________________________________________________________________

Скачать ISO дистрибутив Cinnamon Budgie OS 18 19.04 iso 3Гб https://drive.google.com/open?id=16PWanzg4lmgIzpQub5y82a_uhQlzBgdq  патч от тиринга убирает лишнее из xorg фаила который приводит к тирингу  https://github.com/Griggorii/linux_xorg_glamor_perfomance_uxa_tearing_fix_intel драивер glm будет работать только на установленной системе и даст прирост скорости в 3 - 4 раза больше чем вы видили ранее в других дистрибутивах , в live режиме glm glamor теперь будет работать. Скачайте так же пакет libsndio6.1_1.1.0-2_amd64.deb если вам нужен yuzu-canary

+ Если кому надо вот в придачу Android https://yadi.sk/d/Cc-bpsnqtk1b9w

После установки если опять заидёт в root там можно сменить пароль сразу в терминале это команда passwd не перезагружаясь выйдите верхнем самом правом углу нажмите на значек и выбирите budgie / cinnamon или что захотите , а по центру экрана увидите если там стоит воити как гость то нажмите и поменяйте на своего пользователя , cinnamon  или окружение которое до этого знали.

Ядро имеет glamoregl графику и на него нельзя ставить nvidia драивера там на этом драивере xorg glamoregl больше fps чем на nvidia и amd драиверах.

Для тех кто будет программировать на системе что бы не бояться что она поломается там установлен timeshift

После того что какие проблемы то читать в Читать.txt

Android cm-x86-14.1-r2.i686.rpm распаковать прямо от рута в корень / и обновить груб после перезагрузки можно загрузиться , документация в документы->Читать.txt столе читать расскажет как создать data.img

Понадобиться флешка с 4 гигабайтами для того что бы образ влез , 
можно взять флешку и не стирая её закинуть туда образ программой Ultra ISO , WinSetupFromUSB_1-0 
или программой (unetbootin не помню стирает она данные или нет перед прожигом) , 
точный пример без потери данных на флешке WinSetupFromUSB_1-0 выставив галки 
как на картинке https://imgur.com/a/7NugSRA , потому что не у всех есть флешка лишняя и так этот способ даст избежать лишних затрат на флешки , 
в play market тоже есть утилиты типа DriveDroid и другие с помощью которых можно 
даже с телефона установить по кабелю с ПК и установить образ со смартфона.
Для linux я использую https://unetbootin.github.io/linux_download.html просто делаете бинарник в свойствах
исполняемым и либо запускаете от админа или в терминал в той же папке руню рутирую и закидываю в его окно бинарь 
образ указываю предварительно смонтировав флешечку которая предварительно отформатирована не меньше чем fat32

Установка 

Flesh card / hdd / usb hdd / sdd / vhd / vhdx minimum size memory 16 gb

Как проверить любой дистрибутив , надо открыть настройки vlc плеера если вылетит значит не годится

Systemback также поможет восстановить систему и отремонтировать grub её и ваши фаилы не пропадут 
если они лежат именно в папке home , только пропадут программы которые установили после , это очень 
удобно на днях я попытался скомпилировать и разработать свой xorg-server в итоге ни клавиатура не 
мышь не работали и с помощью systemback я восстановил систему без всяких переустановок просто подмонтировал 
свой sd раздел в /mnt и включил восстановление системных файлов.

Про интернет соединение без роутера https://www.youtube.com/watch?v=mAUXs3WLuug у вас должно быть там всё на родном языке.
step 3: save правильнее , после step 3 yes ничего не делаем и выходим из терминала.
Потом у меня ниже на панели есть network-manager апплет зайдите щёлкнув на него либо лкм или пкм (потому что я не знаю как ваша мышь работает программно или настроена) изменить соединения и удаляете созданные проводное и Автоматический Ethernet и dsl соединение.

Затем жмёте + и создать из списка выбираете DSL/PPPoE

Соединение DSL 1 , 
предковый интерфейс enp2 , 

___________________________________________________________________________________________________________

/var/lib/ubiquity
