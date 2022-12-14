# Введение в язык ассемблера

> Информация по [языку ассемблера](https://ru.wikipedia.org/wiki/Язык_ассемблера) в [википедии](https://ru.wikipedia.org).
> 
> Также есть информация по ассемблеру GAS в [википедии](https://ru.wikipedia.org/wiki/GNU_Assembler).

Каждое электронное устройство на земле имеет процессор, который управляет арифметической, логической и управляющей деятельностями устройства.

Каждое семейство процессоров имеет свой собственный набор инструкций для выполнения различных операций, таких как получение ввода с клавиатуры, отображение информации на экране и так далее. Этот набор инструкций называется инструкциями машинного языка.


# Обучение

Нам нужно:
* Компьютер или ноутбук, с архитектурой Intel x86
* ОС с ядром Linux
* Ассемблер NASM

Мы выбрали ассемблер NASM, тк. он:
* бесплатный
* открытый (можно посмотреть исходный код)
* хорошо задокуменирован (по нему можно найти много информации в интернете)
* прост в использовании

# Установка NASM

Для пользователей Android Termux: pkg install nasm

Для пользователей Arch Linux: sudo pacman -S nasm

Для пользователей Alpine Linux: sudo apk add nasm

Для пользователей CentOS: yum install nasm

Для пользователей Debian(-подобных): sudo apt install nasm

Для пользователей Fedora / RedHat(-подобных): sudo dnf install nasm

Для пользователей \*BSD: pkg install nasm

Для пользователей Gentoo: emerge --ask --verbose dev-lang/nasm

Для пользователей macOS: brew install nasm

Для пользователей MS Windows/Scoop: scoop install nasm

Для пользователей Microsoft Windows: скачайте [установщик](https://www.nasm.us/pub/nasm/releasebuilds/2.15.05/win64/nasm-2.15.05-installer-x64.exe) с оффициального сайта, и запустите от админинстратора

Для пользователей MS Windows/Choco: choco install nasm

Для пользователей Cygwin/Msys2: pacman -S mingw-w64-x86_64-nasm

Если установка прошла без ошибок, проверите есть ли NASM следующей командой Unix:
```bash
[ "$(whereis nasm)" -ne "nasm:" ] && echo "Нету" || echo "Есть"
```

Если выведет "Есть", значит все хорошо


<br/>
<p align="center">
Навигация:
  <div align="left">
    ⇜ <a>Прошлая страница</a>
  </div>
  <div align="right">
    <a href="syntax.md">Следующая страница</a> ⇝
  </div>
</p>
