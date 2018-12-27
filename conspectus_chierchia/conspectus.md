---
title: Конспект 'Logic in grammar' Г. Кьеркиа
author: Алексей Кошевой
date: 31 декабря 2018
...

# Теория импликатур.

Кьеркия предложил теорию (на самом деле еще в ранних работах), которая описывает
те проблемные случаи, которая (нео-)грайсианская прагматика описать не может --
например, вложенные импликатуры (если мы считаем, что импликатуры порождаются после
семантической деривации, то тогда вложенные импликатуры невозможны -- потому что непонятно,
когда они успевают породится).

## Исчерпывание альтернатив

Одна из главных идей Кьеркия в том, что скалярные импликатуры порождаются с помощью скрытого грамматического оператора
исчерпывания альтернатив O, который работает следующим образом:

(@) $Alt = \{x, y, z\}$

    $O_{Alt}(x) = x \land \neg y \land \neg z$

Т.е. с помощью оператора O (скрытого only), выбирается одна альтернатива из множества. Рассмотрим конкретный пример:

(@) Joe or Bill will show up

    ALT = {$B_s(\text{show up}(j) \vee \text{show up}(b))$, $B_s(\text{show up}(j) \land \text{show up}(b))$}

    $B_s(O_{ALT}(\text{show up}(j) \vee \text{show up}(b))) = B_s(\text{show up}(j) \vee \text{show up}(b)) \land \neg B_s(\text{show up}(j) \land \text{show up}(b))$

В данном случае говорящий породил импликатуру с инклюзивным or. Также он предлагает и другие скрытые операторы, например (D-оператор, соотвествующий
английскому *each*) для предложений типа *John and Mary hit a pole*, для того, чтобы пораждать импликатуры типа -- "они оба ударились в один столб" / "каждый из них ударился о столбы (различные)"

## Релевантность