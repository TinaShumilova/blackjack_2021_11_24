## Игра "Blackjack"

Описание правил игры можно почитать на вот [тут](https://ru.wikipedia.org/wiki/%D0%91%D0%BB%D1%8D%D0%BA%D0%B4%D0%B6%D0%B5%D0%BA)

### Идея решения

В игре участвуют несколько игроков, для простоты можно взять двух игроков.
Каждый игрок по очереди отвечат на вопрос - "нужна ли Вам еще одна карта?". Если ответ утвердительный, то игроку выдается следующая карта из колоды. Если игрок ответил отрицательно, то у этого игрока больше не спрашиваем. Когда все игроки отказались от новых карт, то начинается подсчет очков. В результате определяется победитель.

Для начала надо определиться как мы будем работать с картами. Напомню, в задаче нельзя пользоваться ничем кроме массивов.
Также важно понять как производить итоговый подсчет очков у каждого игрока, то есть надо как-то узнать сколько очков дают за карты, которые находятся на руках у каждого из игроков.

Сама игра проходит так:

1. Создаем колоду карт.
2. Для игры нам необходима перемешанная колода, поэтому надо в случайном порядке перетасовать карты (или сделать какой-то механизм, чтобы менять порядок карт)
3. Фаза набора карт игроками. Каждый игрок берет по одной карте, до тех пока не скажет что ему больше карты не нужны. Карты выдаются по одной из перемешанной колоды.
4. Фаза подсчета очков. Нам необходимо узнать сколько очков у каждого игрока.
5. Определение победителя в этом раунде.
6. Можно продолжить играть и перейти к следующему раунду (шаг 3).

Попробуйте подумать над решением задачи. В соседней папке есть подсказки, но попробуйте день-два подумать над реализацией и только потом заглядывайте в подсказки. 

Обратите внимание - в подсказках только один из возможных вариантов решений, возможно, вы сможете придумать более интересный и красивый вариант)

Удачи с решением. Через несколько дней выложу еще подсказки, но надеюсь, что они не понадобятся)