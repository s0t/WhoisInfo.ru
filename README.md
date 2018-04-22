# [WhoisInfo.ru](https://whoisinfo.ru)

## Главное
WHOIS (от англ. who is — «это кто?!») — сетевой протокол прикладного уровня, который работает на основе TCP. **Основное применение - получение информации о владельце доменных имён, IP-адресов и автономных систем**.

Протокол работает по схеме "клиент-сервер" и используется для получения информации у публичных баз-данных регистраторов доменных имён и IP-адресов. Текущая версия работы описана в RFC 3912. Чаще всего, WHOIS работает через клиенты (консоли) на ПК или в виде веб-решений (публичных Whois-сервисов, типа [WhoisInfo.ru](https://whoisinfo.ru)). 

Изначально целью WHOIS - было дать возможность сис.админам искать информацию (или компромат) о других админах IP-адресов или доменных имён для связи с ними по любым вопросам (от сугубо технических до сексуальных). У WHOIS есть аналог — стандарт протокола RWhois (который нигде не используется и существует "ЧТОБЫ БЫЛО").

## О проекте
Эта веб-форма (далее "скрипт") работает на PHP и посылает запросы напрямую к Whois-серверам различных регистраторов и автономных систем. Ответ возвращается в теч. одной секунды (реально). Скрипт очень лёгкий и работает даже на самих ПК с поддержкой PHP. Если у Вас [обычный хостинг с PHP](https://www.scalets.com) - всё будет работать исправно.

### Требования
Серверная часть:
- PHP 5.4.* или больше
- **Установленный Composer**

Клиентская часть:
- Браузер с поддержкой CSS, JS, PHP

### Основа проекта
- Bootstrap 4.0
- jQuery 3.3.*
- PHP (чистый)

Актуальные ссылки на скрипты - предоставлены [XenCDN.com](https://www.xencdn.com)

### Контрибуция

![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

Произведение «WhoisInfo.ru» созданное и поддерживаемое независимыми разработчиками, публикуется на условиях лицензии ["Creative Commons" С указанием авторства - С сохранением условий / 4.0 Всемирная](https://creativecommons.org/licenses/by-sa/4.0/deed.ru).

#### Детали контрибуции
Если Вы взяли за основу этот проект для коммерческого использования - имейте совесть оставить копирайт со ссылкой на Гитхаб. Этот проект публикуется на "open source" основе. Если не хотите видимый копирайт - укажите ссылку в формате кода: `<!-- Whois-script provided by WhoisInfo.ru (https://abcd.tools & https://whoisinfo.ru) -->`

Уважайте работу разработчиков и указывайте ссылки на проект.
