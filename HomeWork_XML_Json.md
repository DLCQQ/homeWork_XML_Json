Задача №1: проверить XML на Well formed:

<req>

    <surname>Иванов</surname>

    <name>Иван</name>

    <patronymic>Иванович</patronymic>

    <birthdate>01.01.1990</birthdate>

    <birthplace>Москва</birthplace>

    <phone>8 926 766 48 48</phone>
</req

Задача №2: проверить JSON на Well formed:

{

    "surname": "Иванов"

    "name": "Иван"

    "patronymic": "Иванович"

    "birthdate": "01.01.1990"

    "birthplace": "Москва"

    "phone": "8 926 766 48 48"
}

Задача №1:

Первая задача **not well formed** так как в  закрывающем теге req **нет закрывающей скобки >**

код XML и его ветви выглядят так:

![Задача1](Задача1.png)

Для *решения проблемы* достаточно **дописать закрывающую скобку** в теге /req


![Задача1_1](Задача1_1.png)
