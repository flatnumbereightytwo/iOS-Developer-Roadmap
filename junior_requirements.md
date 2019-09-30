По поводу джунов, могу таким пониманием поделиться.
Ну для начала, у всех контор свои требования к кандидатам. И эта градация размыта.

Но если ищешь вакансию джуна, то вот требования которые я бы выставил. У меня просто была ситуация когда надо было найти помощника. 
Чтобы я не тратил время на обучение, а мог давать простые задачки:

- Управление памятью mrc/arc. Хотя бы в теории надо четко рассказать. Ну и понимать когда может произойти утечка.
- Работа с асинхронным кодом (GCD минимум). NSOperationQueue и Threads можно в теории понимать, плюс остальные способы многопоточности. 
  Потому что в 99% используется GCD.
- Автолейаут и верстка форм. Понимать как работают сайзклассы. Уметь верстать сториборды. Уметь верстать через UIStackView. И иметь представление 
  как кодом создаются констрейнты (на самом деле верстать кодом не сложнее, а иногда проще особенно если используешь обертки. SnapKit например).
- Cocoapods (уметь создать проект, прописать либу, загрузить ее и в проекте использовать)
- Работа с сетью (понимание что такое json и как его получать и парсить).
- по сети еще надо уметь через URLSession отправить запрос и получить ответ и обработать ошибки.
- Понимание основных паттернов (синглтон, фасад, стратегия... ну можно почитать про них и хотя бы на коцептуальном уровне понимать что это.)
- Знать как работает делегат и как его можно реализовать (протоколы, замыкания)
- Знать жизненный цикл контроллера, приложения.
- Знать как работает таблица, коллекция и уметь с self sizing-ом нарисовать таблицу.
- знать как работает навигация в приложении (без заумий и кастомных переходов)
- работа с гитом (обычно спрашивают отличие мердж от ребейз). Но надо просто уметь с ним работать. Делать ветки, изменения кидать в стеш,
коммиты переделывать. Это не сложно, но нужна практика. Так же уметь создавать пулл реквесты. Это не сложно, надо просто это попробовать сделать 1-2 раза и посмотреть что как.
- Понимать отличие структур от классов. Так же уметь создавать enum и расширять их поведение.
- Понимать как примерно устроены дженерики.
- Знать и использовать протоколы
- Понимать схему устройства основных архитектур MVC, Viper, MVVM. Хорошо понимать и знать как работает MVC.
- Принципы ООП, SOLID (и прочие DRY,WET, KISS etc) это по сути аббривиатуры, надо просто понимать что это и зачем. А ООП знать обязательно. Также хотя бы знать расшифровку SOLID.
- Знать что-то о базах данных (realm или core data) и уметь создавать простые модельки. Без многопоточности и миграций.
- Основы тестирования (уметь хотя бы чисто технически создать класс unit test)
- Основы деббага: создать точку прерывания и посмотреть что за объекты в данном скопе лежат и их доступные свойства.