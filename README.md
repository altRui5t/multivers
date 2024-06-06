Сервис желаний.
# Наименование - "Мультиверс" 

# Девиз "Открой свой мир."

# Предназначение сервиса - оповещение участников сервиса о собственных желаниях и возможностях.
# Монетизация сервиса - в порядке общего оповещения.
# Требуемые ресурсы - мультиверс.рф, серверные мощности, файлохранилище.
# Теги - "Ограничения гармоничны." "Загадай желание." "Краткость - с.т." 
# Преимущества - минимализм, свобода, открытость.
# Ограничения - регистрация через официальный сервис подтверждения личности.

# Архитектура
    Главные сущности
        Пользователь.
        Юнит (связка желания и возможностей).
        Связь (между пользователями).
    Графический интерфейс.
        Интерфейс списка юнитов.
        Интерфейс дерева связей.
        Интерфейс информации об участнике.
    База данных:
        Таблица связей.
        Таблица юнитов.
        Таблица пользователей.
    Ограничение выдачи
        По локации
        По фильтрам видимости
        По связям


## Модули:
        Клиент базы данных.
        Модуль авторизации.
        Модуль построения дерева связей. 
        Модуль отображения списка.
        Модуль отображение дерева.
        Модуль фильтрации.
        Модуль определения положения. 
        Модуль карты.
        Модуль оповещения.
        Модуль диалога между участниками.
        Модуль балансировки.
        Модуль расчёта ограничений.
        Модуль смарт-контрактов.

    

  Один юнит - два поля:  я умею делать - могу, чтобы я хотел получить - "хочу". Только общие формулировки - поле 9 символов UTF возможность короткой ссылки или короткой ссылкой на райдер. 
  Любые услуги - от вынести мусор, до перетащить велоспид на балконе или помощь с ремонтом. Стоимость любая, может быть даже не в деньгах, а в других объявлениях =).
  
  Добавить  длительность  желаемого и длительность могу.  Для трудовых отношений предложить сразу формировать пакет документов и рассказывать, сколько за подобный райдер хотели другие участники. Плюс если в желаниях есть сумма в деньгах - предложить оформить документы по данным юнита.  В текст подстановки в полях юнита попадают чужие желания и возможности чем чаще поле юнита встречается у других юнитов. Тебе никто ничего не гарантирует. А может отсутствовать. Регистрация через госуслуги. И давать возможность видеть другим дерево связей того, кому собираешься помочь и того, кто предлагает помощь. Не просто  отзывы и оценка, а откуда эта оценка пошла. Монетизация по тому же  принципу - чего бы хотели создатели. Регистрация только через госуслуги. Задаваемое ограничение видимости по расстоянию от пользователя в виде ползунка регулирующего дальность - от дома, до страны и всего мира, Интерфейс - три колонки : "хочу" колонка с именем юнита, колонка "могу". А потом можно для отзывов также оставить только короткое поле или ссылку на развёрнутый отзыв. Минимализм, счастье, заебись, если взлетит. Минимальные затраты на разработку базовой функциональности. Плюс поисковые машины не будут грузить основной прод, так как там только ссылки и короткие слова. ТАким образом получается дорабатывать проект прямо на ходу, не привлекая сторонних инвестиций. Любые данные присутствующие на площадке должны быть оформлены как такие, которые не попадают под законы о защите информации и праве на переписку. Добавить возможность получить согласие на публикацию личных/иных данных у человека. Можно добавлять метки к юниту. Кто угодно, но такие же короткие. И в целом - можно и нужно эти ограничения вводить от меньшего к большему - увеличивать локально, если локально часто забивают под завязку определять вероятностно от количества упоминаний. ВОзможность убрать из выдачи все запросы от автора юнита. Максимальное количество юнитов на пользователя определять также по сигмоиде от количества юнитов. На ограничении вывести - слишком много желаний и пусть удаляет какое-то неисполненное желание. Три статуса юнита. Озвучено. Принято. Исполнено. Можно менять местами поля юнитов в списке. У юнита может быть лимит на количество исполнителей. Также по сигмоиде от количества Исполненных. Юнит мечта идёт без поля могу. ПРодумать возможность интеграции с другими  подобными сервисами из других стран. У исполнено подтверждающих на 1 больше, чем количество исполнителей, чтобы все могли проголосовать. Чем больше проголосовало, тем более яркой становится кнопка. Желание тоже может быть на несколько человек - Мы хотим. И Мы можем. И Мы мечтаем. И постепенно от Мы хотим, Мы мечтаем, Мы можем переходить постепенно к "Все хотят", ..., если в указанном на ползунке регионе все подписались под этим юнитом***
