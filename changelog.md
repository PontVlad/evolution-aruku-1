v1.3.0 12.12.23
+ Добавил дополнение "Жизненный Цикл" #feature
+ Теперь нельзя использовать отбрасывание хвоста на удильщика #bug
+ Теперь нельзя взять больше еды чем нужно используя свойство во время взаимодействия #bug

v1.2.1 28.12.22
+ Агрессия теперь работает против удильщика #bug
+ Агрессия теперь работает против мимикрии #bug
+ Интеллект теперь работает с зараженным #bug
+ Яйцекладущее теперь позволяет закончить ход #bug
+ Паралич теперь работает не только в первом ходу #bug
За тестирование спасибо https://vk.com/id615209602 

v1.2.0 22.12.22
+ Перешел на semver
+ Добавлено "Фанатское дополнение" #feature
+ Исправил https://github.com/ivan-work/evolution-web/issues/53 #bug

v1.1.10 16.12.22
+ Сообщения в глобальном чате теперь доступны всего 1 час #feature

v1.1.9 13.12.22
+ Мелкие исправления deprecated ошибок #fix
+ Таймеры комнаты теперь в секундах #feature
+ Комната теперь сохраняет свои настройки #feature
+ Поменял MOTD #feature

1.1.8 01.11.22
+ Обновлена версия ноды на 16 (заодно проверил что впринципе норм запускается на современном стеке)

v1.1.7 26.02.21
+ Fixed English translation (https://github.com/ivan-work/evolution-web/issues/125)
+ Поправлен Русский текст
+ Авторизация ВК снова работает
+ Тиканье на последних 4 секундах если временя хода меньше 30 секунд 

v1.1.6 26.02.21
+ Added English translation and language selectors

v1.1.5 19.08.20
+ Починен креш клиента с неоплазией и симбиозом #fix (Кстати первый фикс другим разработчиком, eee, спасибо, Ярославу https://github.com/yturovtsev)
+ Громкость тиканья на последних секундах уменьшена до 40% #feature
+ Теперь если время хода меньше 30 секунд таймер не тикает #feature 
+ Когда рекомбинация скидывает свойства игра пересчитывает количество необходимой еды #fix 

v1.1.4 13.07.20 (Экспериментально пишу список изменений в будущем времени)
+ Выключенная неоплазией или СК раковина включится если её подобрать с еды #fix
+ Мимикрия будет действовать только раз в ход потому что https://vk.com/topic-144914092_35603928?post=548 #fix
+ Если удильщик съест атакующего, игра не даст атакующему игроку взять еды #fix
+ Если удильщик съест атакующего, игра не будет думать что владелец удильщика уже ходил #fix
+ Метаморфоза сможет отбрасывать свойства с +х под неоплазией #fix
+ Хищник отбившийся от удильщика ЧО не сможет атаковать ещё раз #fix
+ Все животные в диалоговых окнах покажут еду #feature
+ Время для самоуничтожения комнаты станет 10 минут #feature
+ Улучшены описания карт свойств (спасибо Александру Иванову) #feature
+ System сменила ник на 0 #misc
+ Сообщения о том что хост АФК стали менее кринжовыми ;) #misc 

v1.1.3 09.06.20
+ Спячку можно отметаморфозить потому что https://vk.com/topic-36567706_26132044?post=6614 #fix
+ Неоплазия вырубает эдификаторов до того как они эдифицируют (но не в растениях!) #fix
+ Удильщика нельзя отметаморфозить #fix
+ Два живорождения, соединенные трематодами и которым нехватает 1 еды, не живорождают в фазу вымирания (как вы это нашли вообще!?) #fix
+ После атаки ЧО на удильщика его нельзя съесть в тот же ход #fix
+ Сервер сообщает когда он запущен в чат чтобы люди прикидывали когда следующая перезагрузка #feature

v1.1.2 17.05.20
+ Взаимодействие и теплокровное теперь не берут еду из воздуха если её мало #fix
+ Чутка переделана система ошибок внутри игры #feature
+ У Витука теперь есть "возможность нажать на засаду" #fix
+ Если рекомбинированная неоплазия убивает существо, его парные свойства убираются #fix
+ Добавлена костылина, чтобы норное не защищало от засады #fix
+ В комнате нельзя сделать нулевое время (если хотите бесконечного времени на ход, играйте через паузу) #fix
+ Рекомбинация под неоплазией дает карту и не дает животных #fix
+ Спячку нельзя отметаморфозить потому что https://vk.com/topic-36567706_26132044?post=6614 #fix

v1.1.1 03.05.20
+ Живорождение не активируется когда трематода умирает #fix
+ Рекомбинация не ворует еду #fix
+ Мимикрия на чернила корректно дает напасть ещё разок #fix  
+ Метаморфоза корректно отсоединяет специализацию #fix  

v1.1.0 28.04.20
+ Еда не показывает что она -1 #ui
+ Добавлено тикание когда осталось меньше 10 секунд #feature
+ Рекомбинация удаляет флаги с животных (спячка, пугливое, раковина) #fix
+ Растение-хищник нападающее на удильщика дает ему 1 еду #fix
+ Съеденная регенерация дает еду грибам #fix
+ Удильщик теперь иногда защитильщик #feature
+ Исправлены описания способностей #feature
+ Список людей онлайн доступен по наведению #feature 
+ Растения доступны всем #ui

v1.0.34 27.04.20
+ Улучшены шрифты в логе #ui
+ Показывается общее количество еды #ui
+ Добавлена команда /time #ui
+ Добавлена менюшка для разыгноривания #ui
+ Интеллект работает на растение раз в фазу #feature
+ Добавлена подсветка свойств в кулдауне #ui
+ Живорождение рожает при сбрасывании паразита или трематоды #fix
+ Игра выбирает первого игрока с учетом ливеров #fix

v1.0.33 14.04.20
+ Старый интерфейс убран, код почищен от скверны #ui
+ Яблочко на растениях выглядит повкуснее #ui
+ Добавлена посдказка что еда это еда, а убежище - это убежище #ui
+ Раковины теперь лежат рядом с растениями #bug
+ Починен креш при взятии раковины #bug
+ Отключена возможность бесконечно пропускать ход когда есть растение-паразит #bug
+ Специализация позволяет игнорировать лекарственность растения #bug
+ Интеллект позволяет игнорировать лекарственность и защитные свойства растений #bug

v1.0.32 13.04.20
+ Зеленый цвет оказался не оч, теперь у "официальных" аккаунтов есть иконка в списке игроков #ui
+ В растениях фото и термо синтез заменены на специализацию #feature

v1.0.31 12.04.20
+ Автоход уважает теплокровность, паразитов и хищные растения #bug
+ Автоход берет укрытия #bug
+ Починен креш в растениях когда топчешь после сотрудничества #bug
+ Убран лишний желтый цвет с некоторых свойств #bug
+ Имя комнаты позволяет - и _ #bug
+ У игроков, зашедших через ВК теперь зеленый никнейм #feature

v1.0.30 09.04.20
+ Добавлено самоуничтожение комнат #feature
+ Голосовалка работает #bug
+ Очки за "за ископаемые" теперь "за сброс" #bug
+ Добавлены абсолютно случайные очки за везение #feature
+ Окно показа финального счета сделано более надоедливым #bug
+ Зрители больше не видят защиты если заходят во время защиты #bug 

v1.0.29 29.03.20
+ Добавлено ограничение карт #feature
+ Съеденная из засады регенерация уходит домой #bug
+ Правильное ограничение максимума растений #bug
+ Убитая регенерация не может брать убежище #bug
+ Медонос не работает #bug
+ Паразит не умирает вместе с хостом #bug

v1.0.28 03.03.20
+ Растения rc2

v1.0.27 14.02.20
+ Растения доступны по команде /растения

v1.0.26 01.02.20
+ Растения rc0

v1.0.25 24.01.20
+ Добавлен крутой хелп по интерактивности (Принимаются предложения по улучшению текстов) #ui
+ Улучшены статусы у животных #ui
+ Чтобы заигнорить человека нужно нажать на ник в чате #ui
+ Тире и подчеркивания в никах #ui
+ Один из симбиозов переименован в симбионта #ui
+ Неафишируемые внутренние изменения, которые могут добавить новых багов #omg

v1.0.24 13.01.20
+ Сообщение об ошибке про уже занятый ник #ui
+ Добавлена прокрутка списка комнат и настроек в комнате #ui
+ Звук создания комнаты для сидящих в главном меню #ui
+ Звук захода в комнату для хоста #ui 
+ Комнаты теперь называются по имени игрока #ui 
+ Пользователи ВК могут менять имя в новой странице своего "профиля" #omg #yeah #wow #cool 

v1.0.23 28.08.19
+ Рекомбинированная неоплазия не включает свойства #bug
+ Подсказки по свойствам в новом интерфейсе #ui
+ Предположительно пофикшен креш ui в рекомбинации #ui #bug 

v1.0.22 11.07.19
+ Больше нельза защищаться незащитными свойствами #bug
+ Засада на себя отключена
+ Рекомбинация не убивает животных если у них есть неоплазия #bug 
+ Длинные слова не включают прокручивание чата по горизонтали #bug
+ Живорождение работает с рекомбинацией или паразитом
 

v1.0.21 21.06.19
+ баг с наведением на ракуху #bug
+ баг с едой в uiv3 #ui
+ удильщик под трематодой больше не защищает #bug

v1.0.20 19.06.19
+ UIv3.4 #ui

v1.0.19 16.06.19
+ Бесконечная раковина #bug

v1.0.18 16.06.19
+ Креш от интеллекта #bug
+ Креш от мимикрии #bug
+ Креш от фототермосинтезов #bug
+ Симбиоз с падальщиком его кормит #bug

v1.0.17 13.06.19
+ Бег с удильщиком съедающим всех хищников которые атакуют его подзащитного из засады #bug
+ Переписана система охоты #core
+ Растения rc0 выросли на сервере #core

v1.0.16 23.05.19
+ Счетчик зрителей #ui
+ Вышедшие игроки скрываются #ui

v1.0.15 22.05.19
+ Игнор пользователей #ui

v1.0.14 09.05.19
+ Баг с засадой на новом интерфейсе #ui #bug
+ UIv3 теперь по умолчанию #ui

v1.0.13 07.05.19
+ UIv3.3 + анимации #ui
+ Отключена возможность банить и кикать зрителей

v1.0.11 25.04.19
+ Пофикшен баг с жиром #bug

v1.0.10 23.04.19
+ UIv3.2 + интерактивность #ui

v1.0.9 08.04.19
+ UIv3.1 #ui

v1.0.8 01.04.19
+ Обработка ошибок на #ui
+ Баг с крешем юай при атаке #ui #bug

v1.0.7 28.03.19
+ UI v2.5: увеличен размер шрифтов #ui
+ мелкие изменения в UI #ui

v1.0.6 26.03.19
+ UI v2.5: Поправлен баг с пасанувшими #ui #bug
+ UI v2.5: Показывает счёт #ui #bug
+ Изменения в meta viewport #ui

v1.0.5 21.03.19
+ новый UI v2.5 #ui
+ новый экспериментальный UI v3 #ui

v1.0.4 31.07.18
+ мертвая регенерация не может брать раковину #bug
+ выровнял "Не использовать" по остальным свойствам #ui
+ регенерация теперь дизейблится если её нельзя трогать #ui
 
v1.0.3 20.03.18
+ починена авторизация через ВК #bug
+ поправлено описание рекомбинации #bug

v1.0.2 21.11.17
+ Если животное с регенерацией и р-стратегией погибло, ни карта за животное не дается ни два существа по р стратегии не выкладываются. #bug
+ Мелкая ошибка от метаморфозы. #bug
+ запись статистики игр #api

v1.0.1 06.08.17
+ Мгновенная смерть от неоплазии работает корректно на клиенте #bug

v1.0.0 31.07.17
+ Мертвая рекомбинация #bug
+ Рекомбинация жиринки #bug
+ Рекомбинация из-под неоплазии #bug
+ Мертвая регенерация теперь не защищает симбионта, а тот может кормиться из-под неё #bug
+ Интеллект на статическую защиту не сбрасывается #bug
+ Если в результате метаморфозы или рекомбинации над неоплазией не оказывается непарных свойств, она убивает существо мгновенно #bug
+ Убран алерт "сообщить об ошибке" и добавлен FAQ

v0.9.4 07.05.17
+ Убитые животные с регенерацией не могут использовать свойства #bug
+ Теперь комната и игра это одна страница #ui
+ Чуть изменено отображение животных #ui
+ Если игрок вылетел, он не может зайти в комнату как зритель (сверху есть кнопка "назад" которая вернет в игру) #ui

v0.9.3 07.05.17
+ r-Стратегия рождает ненакормленных #bug

v0.9.2 05.05.17
+ Когда карт нехватает, они раздаются по правилам (НЕ с первого игрока) #bug
+ r-Стратегия получает карты в начале хода #bug
+ СК выключают парные свойства #bug
+ Живорождение + Хищник при нападении на Отбрасывание хвоста + СК #bug
+ Убран автожир - животное с заполненным жиром умрет в конце хода если ему нехватает еды #bug
+ Жир заполняется сверху - защита от неоплазии #bug
+ Неоплазия убивает сразу #bug
+ Переписаны таймауты на все действия (мб добавлены новые баги, но и старые убраны, типа того когда игрок уходит в АФК на ммоент распределения сотрудничества) #bug

v0.9.1 29.05.17
+ Мелкие фиксы

v0.9.0 29.05.17
+ Переписаны ходы, сотрудничество и взаимодействие

v0.8.6 29.05.17
+ Пофикшен баг с засадой 

v0.8.5 26.05.17
+ Случайное расположение игроков #game
+ Добавлена полезная информация о том что делать в случае бага #ui
+ Накормленное животное не пытается взять еду по взаимодействию #bug
+ Фотосинтез снова работает #bug

v0.8.4 25.05.17
+ Добавлен подарочный набор
+ Зум только в окошке в котором мышка #ui
+ Засада корректно работает на цепочках взаимодействий #bug
+ СК снова работает (2) #ui #bug

v0.8.3 24.05.17
+ Баг с анимацией карт #bug #ui
+ Мимикрия теперь ограничена активацией

v0.8.2 24.05.17
+ Анимация смерти для зрителя #bug #ui
+ Статусы игроков #bug #ui
+ Засада действует по кругу #bug
+ Еда снова рандомна #bug
+ СК снова работает #bug
+ Кулдаун рекомбинации #bug
+ Сброс считается по количеству карт #bug
+ СК+ симбиоз #bug

v0.8.1 24.05.17
+ Добавлена анимация еды #ui

v0.8.0 24.05.17 Демократический Апдейт ^^
+ Добавлена Фаза засады #game
+ Раковина и ЧО теперь опциональны #game
+ Теперь можно выбрать Быстрое и СК как защиту #game
+ Старый интерфейс убран совсем #ui

v0.7.4 22.05.17
+ Неоплазия не влияет на выкладывание хищника на падальщика #bug
+ Интеллект уходит в кулдаун после статической защиты #bug

v0.7.3 22.05.17
+ Стрекательные клетки работают на быстром или ЧО #bug
+ цвет неоплазии #ui #bug
+ метаморфоз спячки #bug
+ трематода регенерации #bug

v0.7.2 22.05.17
+ Добавлены описания карт континентов
+ Уменьшены зоны прокрутки #ui
+ Экспериментально отключено изначальное автоуменьшение UI #ui
+ Рекомбинированный хищник сохраняет свои хищнические свойства #bug
+ Неактивированный удильщик приносит 2 очка в конце игры #bug
+ Исправлено сбрасывание неоплазии #bug
+ Неоплазия убивает существо раньше #bug
+ Переделаны неоплазия и стрекательные

v0.7.1 20.05.17
+ Исправлены паразиты и рекомбинация #bug

v0.7.0 20.05.17
+ Старый интерфейс убран почти совсем
+ Добавлено дополнение "Континенты"
+ Игра не выкладывает вначале карты за игроков #game
+ Tематода больше не стоит 5 очков, а корректные 3 #bug
+ Больше никаких 0.5 в ископаемых #bug


v0.6.5 15.05.17
+ Живорождение теперь не копирует последнюю карту в колоде, а корректно берет первую.
+ Улучшен новый UI. 
+ Теперь зум меняется колесиком мышки.

v0.6.4 12.05.17
+ Баг с удильщиком и живорождением
+ В названии комнаты можно писать ёЁ
+ Пиратство не может воровать в жир
+ UI: Переставлены игроки в новом UI
+ UI: Окошка чата в полную ширину
+ UI: Баг с горизонтальной прокруткой
+ UI: Игроки в новом интерфейсе теперь по кругу
+ UI: Новый интерфейс теперь стандартный
+ UI: раковина не занимает всю строчку
+ UI: Исправлена ширина животных

v0.6.3 05.05.17
+ Улучшен зум

v0.6.2 01.05.17
+ Животное в раковине нельзя съесть
+ Зум в новом UI
+ Баг с симбиозом в новом UI
+ Переделана ситуация когда кто-то заходит с двух вкладок.

v0.6.2 01.05.17
+ Красный удильщик защищает только простых животных.

v0.6.1 29.04.17
+ Баг с хищником на старом интерфейсе

v0.6.0 28.04.17
+ Пофикшен удильщик
+ Новый UI

v0.5.7 26.04.17
+ Обновлены библиотеки

v0.5.6 24.04.17
+ Улучшены тултипы
+ Интеллект теперь можно не использовать.

v0.5.5 20.04.17
+ Пауза
+ Если пропустил ход - следующий будет 10 секунд
+ Переделаны таймауты
+ Пределаны тултипы. И добавлены на животных, теперь можно навести на животное.
+ Хост может кикнуть и забанить зрителей
+ Клиент проверяет рекурсивную мимикрию

v0.5.4 17.04.17
+ Анти-АФК система
+ Хелпа по количеству карт
+ Баг со звуком начала игры
+ На начало голосования кидает в комнату

v0.5.3 15.04.17
+ Определение готовности игроков происходит не после старта игры, а до.
+ Как следствие, игра не крешится если кто-то не может играть.
+ Нотификация хосту когда комната полная

v0.5.2 13.04.17
+ Пофикшены несколько засад против одного
+ Пофикшена засада на ЧО
+ После того как существо съели, хозяин может ходить дальше
+ Краш клиента при отбрасывании хвоста с раковиной или ЧО

v0.5.1 12.04.17
+ Чат автоскроллится по дефолту
+ selectLink подсказывает что делать
+ полет+хищник+(защита) корректно умирает от удильщика
+ фавиконка

v0.5.0 12.04.17
+ Экспериментальная поддержка сенсорного экрана.

v0.4.7 12.04.17
+ Появилась группа ВКонтакте: https://vk.com/evolveonline
+ Раковину можно взять и после еды.
+ Удильщика нельзя посмотреть в логе игры (2)
+ Карты стали чуть красивее
+ Чят автоскроллится при масштабе < 100%
+ Неблокирующий выход из комнаты
+ Исправлены описания некоторых свойств
+ читабельные sourcemaps на продакшене
+ в имени комнаты нельзя писать проблемы по краям
+ лог стал более читабельный + добавлено время


v0.4.6 11.04.17
+ Интеллект не игнорит Отбрасывание Хвоста
+ Метаморфоза просто работает
+ Удильщика нельзя посмотреть в логе игры
+ Добавлены нолики в чат
+ Специализации нельзя положить друг на друга
+ На https://evo2.herokuapp.com работает вход через ВК
+ Проверка на Хищник-Падальщик и специализации на клиенте

v0.4.5
+ Галочка Время Летать видна всем
+ Комнаты с законченными играми не показываются. А остальные сортируются ещё и по времени создания.
+ Время в чяте теперь не в миллисекундах от начала дня :D
+ Кнопка справа вверху чтобы вы увидели этот файл
+ Нельзя сделать безымянную комнату
+ Трематоду нельзя откинуть хвостом
+ Еда подстраивается под количество игроков
+ Исправлена атака на ЧО (чернильное облако)

v0.4.4
- Атака на свое животное с удильщиком увечила логику
- Атака животным (Удильщик, интеллект, хищник) сбрасывала удильщика и интеллект в любом случае. Кек.

v0.4.3
+ Животные сами берут еду если таковая есть
+ Игра выкладывает за вас одну карту, если у игрока ничего нету на столе.
(Я знаю что это обязательно только в первый ход, но мне лень городить костыли для проверки первый это ход или нет. Да и вообще это абуз тащемто)

v0.4.2
+ Изменен порядок автосрабатывания свойств: Бег, Облако, отбрасывание, раковина, мимикрия
- Интеллект не игнорил Ядовитое
- Интеллект не игнорил Быстрое
- ЧО не работает после Интеллекта
+ Метаморфоза может откидывать свойства которые мешают покушать


v0.4.1
- Удильщика можно выложить как свойство

v0.4.0
+ Время летать

v0.3.8
+ Смайлики на животных.
+ Очки за парные свойства считаются правильно
+ Сотрудничество теперь работает правильно (2)
+ Поменял цвета у парных свойств.
+ Суть такая - взаимодействие берет зеленую еду и потому оно зеленое. Сотрудничество экспериментально синее.
+ Животные стали чуть ниже и шире.

v0.3.7
+ Исправил галочку в чекбоксе (aka отключена минификация css-loader'ом из /node_modules/)
+ Переделаны сотрудничество и взаимодействие

v0.3.6
+ В списке игроков у пасанувшего игрока ник красится в серый
+ Континент теперь зеленый только у активного игрока
+ Немного поменял настройки комнат
+ npm shrinkwrap