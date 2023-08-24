PHILOSOPHERS
============

Проблема об обедающих философах - это классическая задача в области многопоточности и синхронизации.  

Имеется пять философов, сидящих вокруг круглого стола. На каждом месте философа расположен тарелка с едой, а между каждыми двумя тарелками находится вилка.  
Философ может находиться в двух состояниях: он может либо есть, либо размышлять.  
Проблема заключается в том, чтобы разработать алгоритм, который позволит каждому философу поочередно есть и размышлять, при условии, что каждый философ требует двух вилок для того, чтобы начать есть. Таким образом, возникает риск взаимной блокировки, если все философы одновременно возьмут вилки справа от себя.

# Версия на С
Компиляция: `gcc -Wall -Wextra -Werror`  
Либо воспользуйтесь мейкфайлом: `make`  

Программа принимает на вход от 4 до 5 аргументов:  
- количество философов
- время бездействия, через которое филосов умирает
- время, за которое он поест
- время, которое ему нужно поспать
- необязательно: количество раз, которое каждый философ должен поесть

Запуск: `./a.out` + аргументы.

# Версия на Python

Небольшой проект, знакомство с потоками в Python.  
Взята тематика культового сериала "Доктор Кто".  
Всего 5 докторов на 5 отвёрток, смерти и ограничений по времени нет.  
Запуск: `python doctors.py`

# О проектах
Были выполнены и сданы на отлично в рамках учебных программ школ программирования Ecole 42 и School 21.  
Все файлы .c были проверены школьным линтером - Norminette. Весь проект на С был проверен на утечки памяти.
