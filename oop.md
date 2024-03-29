[Вопросы для собеседования](README.md)

# ООП
+ [Что такое _ООП_?](#Что-такое-ООП)
+ [Назовите основные принципы _ООП_.](#Назовите-основные-принципы-ООП)
+ [Что такое _«инкапсуляция»_?](#Что-такое-инкапсуляция)
+ [Что такое _«наследование»_?](#Что-такое-наследование)
+ [Что такое _«полиморфизм»_?](#Что-такое-полиморфизм)
+ [Что такое _«абстракция»_?](#Что-такое-абстракция)
+ [Расскажите про основные понятия ООП: _«класс»_, _«объект»_, _«интерфейс»_.](#Расскажите-про-основные-понятия-ООП-класс-объект-интерфейс)
+ [Что подразумевают в плане принципов ООП выражения _«является»_ и _«имеет»_?](#Что-подразумевают-в-плане-принципов-ООП-выражения-является-и-имеет)
+ [В чем разница между _композицией_ и _агрегацией_?](#В-чем-разница-между-композицией-и-агрегацией)
+ [Что такое _статическое_ и _динамическое связывание_?](#Что-такое-статическое-и-динамическое-связывание)

## Что такое _ООП_?
__Объектно-ориентированное программирование (ООП)__ — методология программирования, в которой программа представляется в виде объектов, каждый из которых является экземпляром класса, а классы образуют иерархию наследования.

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## Назовите основные принципы _ООП_.
+ _Инкапсуляция_ - сокрытие реализации.
+ _Наследование_ - создание новой сущности на базе уже существующей.
+ _Полиморфизм_ - возможность иметь разные формы для одной и той же сущности.
+ _Абстракция_ - набор общих характеристик.

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## Что такое _«инкапсуляция»_?
__Инкапсуляция__ – объединение данных и методов, работающие с ними, в классе и сокрытие реализации от пользователя, открыв только то, что необходимо при последующем использовании.

Цель инкапсуляции — предоставить точки взаимодействия с классом, сокрыв реализацию, чтобы малейшее изменение в классе не влекло за собой изменение внешнего поведения класса.

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## Что такое _«наследование»_?
__Наследование__ – создание нового класса на основе уже существующего с частично или полностью заимствующейся функциональностью.

Класс, от которого производится наследование, называется _предком_, _базовым_, _суперклассом_ или _родительским_. Новый класс – _потомком_, _наследником_ или _производным_ классом.

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## Что такое _«полиморфизм»_?
__Полиморфизм__ – это свойство системы использовать объекты с одинаковым интерфейсом без информации о типе и внутренней структуре объекта.

Преимуществом полиморфизма является то, что он помогает снижать сложность программ, разрешая использование одного и того же интерфейса для задания единого набора действий. Выбор же конкретного действия, в зависимости от ситуации, возлагается на компилятор языка программирования. Отсюда следует ключевая особенность полиморфизма - использование объекта производного класса, вместо объекта базового (потомки могут изменять родительское поведение, даже если обращение к ним будет производиться по ссылке родительского типа).

>Любое обучение вождению не имело бы смысла, если бы человек, научившийся водить, скажем, ВАЗ 2106 не мог потом водить ВАЗ 2110 или BMW X3. С другой стороны, трудно представить человека, который смог бы нормально управлять автомобилем, в котором педаль газа находится левее педали тормоза, а вместо руля – джойстик.

>Всё дело в том, что основные элементы управления автомобиля имеют одну и ту же конструкцию, и принцип действия. Водитель точно знает, что для того, чтобы повернуть налево, он должен повернуть руль, независимо от того, есть там гидроусилитель или нет.
Если человеку надо доехать с работы до дома, то он сядет за руль автомобиля и будет выполнять одни и те же действия, независимо от того, какой именно тип автомобиля он использует. По сути, можно сказать, что все автомобили имеют один и тот же интерфейс, а водитель, абстрагируясь от сущности автомобиля, работает именно с этим интерфейсом. Если водителю предстоит ехать по немецкому автобану, он, вероятно выберет быстрый автомобиль с низкой посадкой, а если предстоит возвращаться из отдалённого маральника в Горном Алтае после дождя, скорее всего, будет выбран УАЗ с армейскими мостами. Но, независимо от того, каким образом будет реализовываться движение и внутреннее функционирование машины, интерфейс останется прежним.

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## Что такое _«абстракция»_?
_Абстрагирование_ – это способ выделить набор общих характеристик объекта, исключая из рассмотрения частные и незначимые. Соответственно, __абстракция__ – это набор всех таких характеристик.

>Представьте, что водитель едет в автомобиле по оживлённому участку движения. Понятно, что в этот момент он не будет задумываться о химическом составе краски автомобиля, особенностях взаимодействия шестерёнок в коробке передач или влияния формы кузова на скорость (разве что, автомобиль стоит в глухой пробке и водителю абсолютно нечем заняться). Однако, руль, педали, указатель поворота он будет использовать регулярно.

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## Расскажите про основные понятия ООП: _«класс»_, _«объект»_, _«интерфейс»_.
__Класс__ – описание сущности

__Объект (экземпляр)__ – это отдельный представитель класса

__Интерфейс__ – это набор методов класса, доступных для использования. Интерфейсом класса будет являться набор всех его публичных методов в совокупности с набором публичных атрибутов. По сути, интерфейс специфицирует класс, чётко определяя все возможные действия над ним.

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## Что подразумевают в плане принципов ООП выражения _«является»_ и _«имеет»_?
__«является»__ подразумевает наследование.
__«имеет»__ подразумевает ассоциацию (связь между объектами) (агрегацию или композицию).

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## В чем разница между _композицией_ и _агрегацией_?
Ассоциация обозначает связь между объектами. Композиция и агрегация — частные случаи ассоциации «часть-целое».

Агрегация предполагает, что объекты связаны взаимоотношением «part-of» (часть). Композиция более строгий вариант агрегации. Дополнительно к требованию «part-of» накладывается условие, что экземпляр «части» может входить только в одно целое (или никуда не входить), в то время как в случае агрегации экземпляр «части» может входить в несколько целых.

>Например, книга состоит из страниц, и мы не можем вырвать страницу из книги и вложить в другую книгу. Страницы четко привязаны к конкретной книге, поэтому это композиция.
В тоже время мы можем взять и перенести книгу из одной библиотеки в другую - это уже агрегация.

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

## Что такое _статическое_ и _динамическое связывание_?
Присоединение вызова метода к телу метода называется связыванием. Если связывание проводится компилятором перед запуском программы, то оно называется _статическим_ или _ранним связыванием (early binding)_.

Позднее связывание (late binding) - это связывание, проводимое непосредственно во время выполнения программы, в зависимости от типа объекта. Иначе говоря, компилятор не знает тип объекта, но механизм вызова методов определяет его и вызывает соответствующее тело метода.

Для всех методов Java используется механизм позднего (динамического) связывания, если только метод не был объявлен как `final`, `static` или `private` (приватные методы являются `final` по умолчанию).

[к оглавлению](README.md#вопросы-для-собеседований-на-позицию-developer) [наверх](#ООП)

# Источники
+ [DevColibri](https://devcolibri.com/%d1%87%d1%82%d0%be-%d1%82%d0%b0%d0%ba%d0%be%d0%b5-%d0%be%d0%be%d0%bf-%d0%b8-%d1%81-%d1%87%d0%b5%d0%bc-%d0%b5%d0%b3%d0%be-%d0%b5%d0%b4%d1%8f%d1%82/)
+ [Хабрахабр](https://habrahabr.ru/post/87119/)
+ [Википедия](https://ru.wikipedia.org/wiki/Объектно-ориентированное_программирование)

[Вопросы для собеседования](README.md)
