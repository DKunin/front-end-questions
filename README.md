# Верстка

- Есть верстка, ее надо превратить в горизонтальное меню
      
        ul
          li
            a(href='') Smth
          li
            a(href='') Smth 2         
          liы
            a(href='') Smth 3


- Если делать элементы float - что будет, если на ul есть фон?
- Если делать элементы inline, inline-block - схлопнуться ли все элементы?
- Как работают float элементы?
- В чем разница между id и классом?
- Какие Вы знаете селекторы?
- Есть два div - у обоих margin: 20px - какое между ними вертикальное расстояние                   
- Расскажите, как сверстать:
>   ![button](https://cdn.css-tricks.com/wp-content/uploads/2013/10/css-button.png)
- Расскажите свой подход к верстке:
>   ![gmailinterface](http://img-fotki.yandex.ru/get/5817/26435816.0/0_751b4_11aa18a7_orig)
- Перечислите способы центрировать объект на странице (вертикально и горизонтально)
- Пользуетесь ли препроцессорами(html,css), если да - то какими?
- Почему тэги `<link>` ставяться в начало документа, а `<script>` как правило в конец?
- Что такое спрайт и как его можно собрать?
- Какие есть возможности написания стилей строго под нужные устройства.
- В чем разница между relative, fixed, absolute и static?

# JS
- Во многих других языках есть системы классов - есть ли что-то такое в JS?
- Что такое замыкание?
- Как работает `this`?
- Какие типы объектов существуют в JS?
- Можно ли изменить контекст исполнения той или иной функции? Как?
- Что делает setTimeout? Как он это делает?
- Можно ли в JS вызвать 2 функции одновременно?
- Перечислите методы объекта массив.
- Как называется последняя итерация версии JS?
- Что Вы знаете о AMD и CommonJS - какие Ваши предпочтения?
- Назовите пару нововведений последней итерации.
- Зачем нужны анонимные функции?
- Что такое хойстинг?
- Чем отличаются `==` и `===`?
- Что такое тернарный оператор?
- Какие Вы знаете техники для отладки JS?
- Назовите отличия синхронной и асинхронной функции.
- Что выведеться в консоли?

          console.log('one');
          setTimeout(function() {
            console.log('two');
          }, 0);
          console.log('three');
- Напишите функцию которая будет работать следующим образом:
          
          duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]

- Напишите функцию которая будет работать следующим образом:
        
          summ(1)(3)(5) //9
          summ(10)(13)(0)(5) //28
          summ(2)(2)(n) // 4 + n где n - возможно бесконечная цепочка вызвов




# Работа JS и DOM
- Когда пользователь жмет на какой-то объект на странице - что происходит?
- Куда девается событие?
- Как повесить обработчик на событие (без $)?
- Пример с меню из верстки - как правильно повесить событие на нажатие каждого элемента?
- Что если элементы будут массово добавляться и удаляться?
- Что такое делегирование событий?

# Общие вопросы на логику и прочее

- Перечислите способы оптимизировать загрузку страницы?
- Какие типы программирования Вам известны?
- Как лучше всего подходить к выбору стэка технологий на новом проекте?
- Как Вы изучали JS?
- Есть ли у Вас собственные проекты?
- Какой самый интересный проект, над которым Вы работали в последнее время?
- Какие материалы Вы изучаете сейчас/на регулярной основе (откуда узнаете последние тенденции)?