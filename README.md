
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![GitHub contributors](https://img.shields.io/github/contributors/fsystem88/brutePMA.svg)](https://GitHub.com/fsystem88/brutePMA/graphs/contributors/) ![repo-size](https://img.shields.io/github/repo-size/fsystem88/brutePMA)

# brutePMA
Brutforce PhpMyAdmin 

# Установка
    apt update && apt upgrade -y
    apt install git python3 python3-pip -y
    git clone https://github.com/FSystem88/brutePMA
    cd brutePMA
    python3 -m pip install -r req.txt

# Запуск
    usage: main.py [-h] [-t [TARGET]] [-u [USERNAME]] [-p [PASSWORD_LIST]]
                   [-r [RATE]]

    Instructions for using the program

    optional arguments:
      -h, --help            show this help message and exit
      -t [TARGET], --target [TARGET]
                            Link to admin panel phpmyadmin format:
                            http://site.ru/phpmyadmin
      -u [USERNAME], --username [USERNAME]
                            Database username.
      -p [PASSWORD_LIST], --password_list [PASSWORD_LIST]
                            The path to the file with passwords can be either
                            sexual or relative. There must be one password on one
                            line.
      -r [RATE], --rate [RATE]
                            The number of threads with which the program will
                            start working. The number of streams should not exceed
                            the number of passwords in your password list.
**Example:**

    python3 main.py -t https://example/phpmyadmin/ -u phpmyadmin -p ../passwords.txt -r 100

***Словари для брутфорса можно найти как в интернете, так и у меня на [Яндекс Диске](https://disk.yandex.ru/d/thBvec7hj3x6KA?w=1).***

***PSы: hashkiller-dict.7z самый большой, о нём я [написал в своём ТГ канале](https://t.me/FS88ch/307).***

# Обновить
    cd ~/brutePMA/ && git pull

<b>3. YANDEX MONEY:</b> https://money.yandex.ru/to/410015440700904<br>
<br>
<i>Free programmers also need to eat :)</i>
<br>
