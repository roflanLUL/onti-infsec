# Information security final

#### Задание 1.

Проанализировав дамп tcp-трафика (полученный за час до конца соревнования, потому что как оказалось у нас не работал агент, который должен работать), полученный путем использования команды "tcpdump -i ens224 -v", мы заметили, что tcp-трафик происходит между клиентами с ip-адресами 192.168.1.2; 10.0.5.14 с портами 53 и 9999, который управлялся вредоносным приложением; 10.0.2.12 с портами 22, а запущен на порте 5555; 10.0.2.13 с портами 22, 53, 80, 8888; 



#### Задание 4.

После исследования zip-архива, в котором было видно только 4 файла, нами был обнаружен скрытый пятый файл, который можно было достатть с помощью вспомогательных программ (мы воспользовались 010 editor). Также обнаружили 3 слова: "enc:", "serpent", "twofish", которые обозначают блочные виды шифрования serpent и twofish. После объявления жюри, что цифры перед словами имеют какое-то значение, мы подумали, что они могут обозначать порядок шифрования данных, которые даны в файлах.
