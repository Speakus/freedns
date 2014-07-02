freedns
=======

List of free DNS

| Сервис          | NS | limit domains, records | adv. records | TTL | way DDNS | comment                                                                                                                                            |
| :----------------: | :-: | :-----: | :---------------------: | :-: | :------: | :------------------------------------------------------------------------------------------------------------------------------------------------: |
| pdd.yandex.ru      | 2   | 50      | AAAA, SRV 	               | + | [api] (http://wanderer-mg.livejournal.com/300105.html) | Есть API                                                                                             |
| cloudflare.com     | 2   | inf     | AAAA, SRV, SPF, LOC       | + |          |                                                                                                                                                    |
| 2ns.info           | 4   | inf     | AAAA, SRV 	               | + |          | Есть экспорт. Показывает регистратора, дату регистрации домена, дату окончания регистрации, тИЦ                                                    |
| dns.he.net         | 5   | 50      | все                       | + | api      | NS доступны по IPv6.                                                                                                                               |
| netbreeze.net/dns  | 3   | 1       | AAAA, SRV                 | + |          | Есть API                                                                                                                                           |
| entrydns.net       | 3   | inf     | AAAA, SRV                 | + | free 3-rd level domain | REST-api                                                                                                                             |
| dnsever.com        | 3   | inf     | AAAA, SRV                 | + | [win, unix] (https://www.dnsever.com/index.html?selected_menu=aboutddns) |                                                                                    |
| cloudns.net        | 4   | 3       | AAAA, SRV, RP             | + |          | Есть API. NS доступны по IPv6, импорт/экспорт в BIND9 и TinyDNS-формате                                                                            |
| freedns.afraid.org | 4   | 20      | AAAA, SRV, LOC, RP, HINFO | + | [win, unix] (http://freedns.afraid.org/scripts/freedns.clients.php) | NS доступны по IPv6, free = [public] (http://habrahabr.ru/post/200986/#comment_6944678) |
| division120.com    | 4   | inf     | AAAA                      | + |          |                                                                                                                                                    |
| dnspod.com         | 3   | inf     | AAAA, SRV                 | + |          | Есть API                                                                                                                                           |
| 4freedns.net       | 4   | 5       | АААА                      | ? |          |                                                                                                                                                    |
| enabledns.com      | 4   | 5       | AAAA                      | + |          |                                                                                                                                                    |
| geoscaling.com     | 5   | inf     | все                       | + |          | Импорт BIND9                                                                                                                                       |
| system-ns.com      | 2   | 5       | AAAA, SRV                 | + |          | Импорт BIND9 и через AXFR. Имеются всякие социалочки и Android-клиент                                                                              |
| pointhq.com        | 5   | 1, 10   | AAAA, SRV, SSHFP, ALIAS   | + |          | Импорт BIND9. Рисует красивые графики, считает статистику                                                                                          |
| sitelutions.com    | 5   | inf     | AAAA, SRV                 | + |          |                                                                                                                                                    | 	
| luadns.com         | ?   | 3, 30   | ?                         | ? |          | бесплатно до 50k запросов в месяц. Управление записями через git(!) и конфигурация на lua(!!). Поддержка Amazon Route 53                           |
| dozens.jp          | 4   | inf, 12 | AAAA, SRV                 | + |          | Есть API. Большая часть интерфейса на японском                                                                                                     |
| ypdns.com          | 1 ?5 | 10     | AAAA, SRV                 | + |          | Полуживой-полумертвый сервис, а когда-то был хорошим. NS-серверов-то 5, но работает только 1                                                       |
| prosto.name        | 2   | inf     | only basic                | + |          |                                                                                                                                                    |
| freedns.ws         | 2   | inf     | AAAA, SRV                 | + |          | Публичные домены                                                                                                                                   |
| xname.org          | 3   | inf     | AAAA                      | + |          |                                                                                                                                                    |
