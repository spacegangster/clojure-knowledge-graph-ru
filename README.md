# Clojure. Граф знаний на русском.
Clojure. Knowledge graph in Russian.

Очень лениво наполняемый граф со ссылками на разные учебные материалы и сообщества.

Всегда рад Вашим дополнениям ❤️

Навигация
=================

  * [Проба ClojureScript](#Проба-ClojureScript)
  * [Пути изучения Clojure](#Пути-изучения-Clojure)
  * [Сборники материалов](#Сборники-материалов)
  * [Книги](#Книги)
  * [Блоги](#Блоги)
  * [Видео](#Видео)
  * [Упражнения и курсы](#Упражнения-и-курсы)
  

## Проба ClojureScript
Один из легчайших путей попробовать сделать проект на ClojureScript – [shadow-cljs](http://shadow-cljs.org)


```
yarn global add shadow-cljs
lein new shadow-cljs your-project +reagent
lein new shadow-cljs your-project +om
lein new shadow-cljs your-project +rum
cd your-project

shadow-cljs watch dev

shadow-cljs cljs-repl dev
```

## Пути изучения Clojure
По мнению участников чата t.me/clojure_ru


##### Artur Dumchev, [9 Sep 2019 at 13:36:34]:
> Наверное, зависит еще от начального опыта.
> у меня было SICP -> Brave -> The Joy of Clojure -> Web Development with Clojure -> Miscoservices with Clojure и параллельно свой pet-project и разные сайты с задачками.
> Кому-то с опытом веба, наверное, не нужны были бы Web Development with Clojure и Miscoservices with Clojure
> Я бы начинал не с Кложи, а с js, java/kotlin (android) или swift (ios), чтобы можно было сразу что-то сделать и выложить, посмотреть, как твоим аппом пользуются. Иначе может мотивации не хватить.
> Еще можно рискнуть с флаттера начать (кросплатформенно), на нем ui попроще делать, но могут возникнуть проблемы, когда появится необходимость трогать нативные фичи девайсов — камеру, блутуз, смс и пр.
> Потом будет приятнее с этих языков на кложу переходить)


##### Mike Bohdan, [9 Sep 2019 at 13:21:19]:
> А чего там учить? 
> Brave->Code Wars->Clojure Applied
> Основные концепции понял, а дальше как и в предидущих н языках до этого.
> Можно даже без Applied первое время
> Есть ещё, если концепции нужно понять, Little Schemer


##### Alexey Golda
> https://github.com/netxor/sicp-clojure
> вот еще ресурс для начала если brave не зашел
> http://kimh.github.io/clojure-by-example/#about
> вот еще сойдет, с разными примерами и тп
> http://clojure-doc.org


##### Ivan Fedorov
> у меня в начале был этот туториал
> https://objectcomputing.com/resources/publications/sett/march-2009-clojure-functional-programming-for-the-jvm

Туториал древний 2009 года, но ещё достаточно релевантен и покрывает большое число тем.
Если где-то неясно как работает функция – можно обратиться к ClojureDocs
https://clojuredocs.org/clojure.core/dotimes


##### Anton Chikin, [9 Sep 2019 at 14:52:14]:
> Вообще есть мнение что sicp устарел немного
> Сами авторы sicp аргументируют тем, что фокус сместился с базовых знаний о алгоритмах и структурах данных к библиотекам и архитектуре
> Есть кстати курс от Стюарта Сиерры
> https://player.oreilly.com/videos/9781491961544


##### Vyacheslav Mikushev, [31 May 2020, 12:56:15]:
> Practical Common Lisp, On Lisp и Let over Lambda. Перечислил от простого к сложному.
> Но это всё для Common Lisp. Для кложи я не читал ничего по метапрограммированию на макросах. Такое метапрограммирование не любят тут. 😁


##### Mikhail Beliansky [8 May 2021]
Книги классные Programming Clojure, Getting Clojure и Professional Clojure


## Книги
* Иван Гришаев – Clojure в производстве. https://grishaev.me/clojure-in-prod/
* Brave Clojure – https://www.braveclojure.com/foreword/
* [Elements of Clojure](https://elementsofclojure.com/) (Zachary Tellman)
* SICP / [SICP Distilled (адаптация под Clojure)](http://www.sicpdistilled.com/)
* [Getting Clojure](https://pragprog.com/titles/roclojure/getting-clojure/)
* [Programming Clojure](https://pragprog.com/titles/shcloj3/programming-clojure-third-edition/)
* [Professional Clojure](https://www.wiley.com/en-us/Professional+Clojure-p-9781119267270)
* [Clojure : the Essential Reference](https://www.manning.com/books/clojure-the-essential-reference)
* [The Little Schemer](https://mitpress.mit.edu/books/little-schemer-fourth-edition)

## Видео
* [Синтаксис и базовые понятия Clojure. Никита Прокопов](https://www.youtube.com/watch?v=3NPBbYPYzhs&ab_channel=MoscowClojureUserGroup)

## Сборники материалов
* [Все лекции Рича Хикки](https://github.com/tallesl/Rich-Hickey-fanclub)
* https://github.com/papers-we-love/papers-we-love
* https://www.infoq.com/architecture-design
* Хорошие примеры на все функции из ядра Clojure https://clojuredocs.org/clojure.core/dotimes


## Блоги
* Иван Гришаев https://grishaev.me/
* Zachary Tellman https://ideolalia.com/


## Online REPL
[repl.it](https://repl.it)

## Упражнения и курсы
* https://exercism.org/ – площадка с упражнениями которые вы сможете показать друзьям и нанимателю
* Бесплатный курс на русском – https://ru.code-basics.com/languages/clojure
* Учим re-frame https://www.learnreframe.com/ курс Jacek Schae

## Базы данных
* [Datomic](https://www.datomic.com) Clojure
* [Crux](https://opencrux.com/main/index.html) Clojure
* [datahike](https://github.com/replikativ/datahike) Clojure and ClojureScript
* [DataScript](https://github.com/tonsky/datascript) Clojure and ClojureScript

## Фронтэнд фреймворки
* [reagent](https://reagent-project.github.io/). reagent принято считать обёрткой над React. На деле, reagent больше чем обёртка. Он также даёт [FRP инструменты](https://en.wikipedia.org/wiki/Functional_reactive_programming) для работы с состоянием, которые настолько просты и круты, что Вы больше никогда не захотите возвращаться к чёртовым хукам и сетСтейтам.
* [re-frame](https://github.com/day8/re-frame). re-frame это как редакс, только редакс отстой, а после рефрейма думаешь – как же я раньше жил немытым.
* [fulcro](https://github.com/fulcrologic/fulcro)
* [Awesome ClojureScript](https://github.com/hantuzun/awesome-clojurescript) около сотни ClojureScript проектов, не только фронтенд.
