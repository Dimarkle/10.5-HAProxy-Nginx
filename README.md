# 10.5 Балансировка нагрузки. HAProxy/Nginx


# Задание 1

Балансировка нагрузки — это процесс распределения нагрузки на  сервера. Применяется для масштабируемости и отказоустойчивости.

# Задание 2
Отличаются по способу распределения запросов распределяются  на сервера.  

Round Robin  Запросы распределяются по пулу  сервером последовательно. Если в пуле все сервера одинаковой мощности, то этот алгоритм скорее всего подойдет идеально. 

Weighted Round Robin имеет дополнительное свойство — вес сервера. С его помощью мы можем указать балансировщику, сколько трафика отправлять на тот или иной сервер. Так сервера помощнее будут иметь больший вес, соответственно, обрабатывать больше запросов, чем другие сервера.

# Задание 3


![э](https://user-images.githubusercontent.com/118626944/209704019-ef6ff6e9-9ac7-4c07-ad71-f18131d3c313.jpg)


# Задание 4
![э](https://user-images.githubusercontent.com/118626944/209704392-d0856ce0-5e33-4515-a49e-16f80759a2de.jpg)

# Задание 5



