---
title: Learn About Permutations
localeTitle: Узнайте о перестановках
---
_Пермутация_ - это математический термин для количества способов, с помощью которых группа объектов может быть собрана в набор. Это похоже на другой математический термин, _комбинация_ , за исключением одного ключевого различия: с перестановками порядок itmes в наборе имеет значение.

Например, скажем, вы вытаскивали цифры из шляпы и считали разные комбинации трех чисел. В этом случае оба `[1,2,3]` и `[3,2,1]` будут комбинацией `1` , `2` и `3` и будут считаться одной комбинацией.

Однако, если вы считали перестановки чисел, они учитывались бы как два разных экземпляра, потому что числа в каждом наборе находятся в другом порядке.

Перестановки можно рассчитать одним из двух способов, в зависимости от того, разрешены ли повторяющиеся значения или нет. Чтобы вычислить количество перестановок `n` объектов без повторов, вы просто вычисляете `n!` , или `n * (n-1) * (n-2) ... * 1` . Это имеет смысл, потому что если вы выберете один номер из шляпы и не вернете его, прежде чем выбрать следующий номер, на выбор будет меньше.

Чтобы вычислить только часть общего количества перестановок (например, чтобы найти количество перестановок из трех цифр от 1 до 10 без повторов), вам нужно только умножить на столько вариантов, сколько вы делаете. В случае трех цифр вам нужно будет умножить `10 * 9 * 8` . Точно так же, если повторы разрешены (то есть, вы помещаете число обратно в шляпе после получения), вы бы умножить `10 * 10 * 10` .