# Millionaire

omg-your-a-millionaire.herokuapp.com

Требования к интерфейсу:
 - На стартовом экране есть кнопка «Начать игру». (Сделано)
 - На экране игры показывается вопрос и 4 варианта ответа. (Сделано)
 - На финальном экране игры нужно показать, что игра окончена и вывести счет за игру. (Сделано) 
 - Возможность как-то начать игру заново, не перезагружая страницу. (Сделано) 
 - Когда показывается вопрос, на экране идет таймер — дать ответ нужно успеть за 30 секунд. Если таймер окончился, а ответа не выбрано, подвсечивается правильный ответ и игра заканчивается. (Сделано)
 - За одну игровую сессию может быть задано не больше 15 вопросов. Если на каком-то вопросе игрок ошибся или не уложился в отведенное время, то игра останавливается после этого вопроса. (Сделано)
 - Счет за игру равен количеству правильных ответов, умноженному на 10 + количество секунд, которые остались в каждом вопросе. Если игрок ответил на какой-то вопрос за 12 секунд из 30 возможных, то к его счету прибавляется 28 очков: 10 за правильный ответ и 18 за оставшееся время. Если ответил неправильно, то ничего не прибавляется и игра окончена. (Вместо этого реализованы несгораемые суммы)
 
 - Если пользователь выбирает неправильный ответ, то игра показывает, подсвечивая зеленым, какой ответ был правильный (важно выбор игрока тоже как-то показывать, чтобы он знал, что правильный такой, а выбрал он другой). Правильный ответ показывается какое-то время, чтобы успеть его прочитать, не сразу завершение игры отображать. (Сделано) 
 - Если пользователь выбрал правильный ответ, нужно подсветить его зеленым и переключить на следующий вопрос. (Сделано) 
 - Если закончилось 15 вопросов и пользователь на все ответил правильно, нужно вывести на экран поздравление и итоговый счет. (Сделано) 

## Подсказки. 
Кроме вопроса и вариантов ответа, на экране отображаются кнопки подсказок: 50/50 и Звонок другу.
 - Подсказка 50/50. При нажатии на эту кнопку, два неправильных варианта убираются. (Сделано) 
 - Подсказка Звонок другу. При нажатии на эту кнопку, на экране появляется «совет от друга», который советует случайный пункт, с несколько повышенной вероятностью выбрать правильный ответ. (Сделано)

## Под звездочкой
* Реализовать счет за игру также, как в оригинальной игре: разная стоимость вопросов и несгораемые суммы. (1 звезда) (Сделано) 
* Вопросов должно быть написано больше 15 и они должны быть ранжированы по сложности и 15 из них должны выбираться случайным образом для каждой игры. Например, первые три вопроса — простые и для них есть 6 вариантов простых вопросов, из которых вопросы для конкретной игровой сессии выбираются случайно. (1 звезда) (Сделано) 
* Подсказка «помощь зала». После нажатия на эту кнопку, строится столбчатая диаграмма того, как якобы проголосовал зал. В этой диаграмме может быть любое распределение голосов, но правильный ответ должен перевешивать в любом случае. (1 звезда) (Сделано) 
* Вероятность того, что зал выберет правильный ответ зависит от сложности вопроса. Для простых вопросов почти весь зал выбирает правильно. Для сложных зал может ошибиться. (2 звезды) (Сделано)

