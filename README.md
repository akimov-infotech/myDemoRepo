# CleanArchRxJava
Demo Android приложение для получения обновлений и просмотра катировок акций https://finance.yahoo.com/. 

- Проект построен на основе Clean Architecture: 
    Presentation слой MVP: Viewer + Presenter
    Business(Domain) слой: Interactor
    Data слой:  Repository
- В качестве DI фреймворка используется Dagger2
- Для получения данных через REST API вызовы используется Retrofit2
- StorIO API для работы с SQLite
