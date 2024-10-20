## Установка
1. Разархивируйте папку.
2. Для того чтобы запустить сборку откройте от имени администратора bat-файл preset_russia.
3. Для того чтобы добавить zapret в автозагрузку откройте от имени администратора bat-файл service_install.
4. Для того чтобы убрать из автозапуска zapret откройте от имени администратора bat-файл service_uninstall.
5. Для того чтобы через zapret проходили только нужные вам сайты используйте bat-файл с припиской autohostlist
## https://github.com/VayuL/Zapret_X64_X86/archive/refs/heads/main.zip - Ссылка на файл
## Решение проблем
- Проверьте, запускаете ли вы файлы от **ИМЕНИ АДМИНИСТРАТОРА**
- Не запускаются bat файлы? Попробуйте запустить **`service_uninstall.bat`** от **ИМЕНИ АДМИНИСТРАТОРА**
  * Также отключите программы, которые могут мешать созданию сервиса *(Антивирусы, клинеры с доп. защитой)*.
- <p style="text-align: left;">
    <img src="https://cdn-icons-png.flaticon.com/16/3670/3670147.png" alt="discord" style="vertical-align: middle;"/>
    Не работает <strong>Youtube</strong>? Попробуйте найти ответ здесь - 
    <a href="https://github.com/Flowseal/zapret-discord-youtube/discussions/251">Обсуждение YouTube</a>
  </p>
- <p style="text-align: left;">
    <img src="https://cdn-icons-png.flaticon.com/16/906/906361.png" alt="discord" style="vertical-align: middle;"/>
    Не работает <strong>Discord</strong>? Попробуйте найти ответ здесь - 
    <a href="https://github.com/Flowseal/zapret-discord-youtube/discussions/252">Обсуждение Discord</a>
  </p>
##
- Не работает вместе с **VPN**? Отключите функцию **TUN** (Tunneling) в настройках VPN.
- Попробуйте обновить бинарники с оригинального репозитория.

### Остановка и удаление обхода
Для этого запустите **`service_uninstall.bat`**.
- Если WinDivert так и не удалился, узнайте его название с помощью команды `driverquery | find "Divert"` в cmd, а затем удалите данными командами (заместо WinDivert введите название, которые вы узнали):
```
sc stop WinDivert
sc delete WinDivert
```
## Linux
В оригинальном репозитории [zapret](https://github.com/bol-van/zapret/) имеется достаточно информации для того, чтобы начать пользоваться обходом блокировок, но и стоит понимать, что нажатием одной кнопки ничего не заработает. \
Достаточно следовать следующим инструкциям и всё внимательно читать:
- [zapret/docs/quick_start.txt](https://github.com/bol-van/zapret/blob/master/docs/quick_start.txt)
- [zapret/docs/readme.txt](https://github.com/bol-van/zapret/blob/master/docs/readme.txt)
  * https://github.com/Flowseal/zapret-discord-youtube/issues/7
> [!WARNING]
> Если вы открываете Issue *(в этом репозитории)* с проблемой в использовании на **Linux**, то, как бы это не звучало, это ошибка. Все вопросы по работе на Linux нужно открывать в **[ОРИГИНАЛЬНОМ](https://github.com/bol-van/zapret/)** репозитории. Следовательно, задавайте вопросы [тут](https://github.com/bol-van/zapret/issues/).

## Support

Вы можете поддержать проект, поставив :star: (сверху справа репозитория)!  
Также, вы можете поддержать разработчика [оригинального репозитория zapret](https://github.com/bol-van/zapret/issues/590) тут - https://github.com/bol-van/zapret/issues/590
* Many thanks to [bol-van](https://github.com/bol-van/), creator of original [zapret](https://github.com/bol-van/zapret/) repository.
