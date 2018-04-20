# Symfony 4 Product application 

тестовое задание на знание фрейморка 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software

```
mysql
php7.1
```

### Installing

you need to configure sql connection in .env file
than run commands

```
composer install
composer recreate
```

than you can run server

```
php bin/console server:run
```
##  Задача

Проект должен состоять из 3-х страниц:
- Главная: site.com.
- Страница категории: http://site.com/category/name/
- Страница товара: http://site.com/item/name/

1.1 На главной странице отображаться все товары из БД.
В правой колонке на главной странице отображается блок ссылок на категории товаров. Переходя по которой отображаются товары из данной категории.

1.2 Категории хранятся в таблице с 2 полями: id(primary key), name.

1.3 Товары хранятся в таблице с полями: id(primary key), name

1.4 Между таблицами товаров и категорий действуют отношение Many-to-Many

1.5 Структура таблиц должна описываться в анатационном формате

1.6 Запросы должны выполняться с помощью ORM Doctrine

1.7 Код должен соответствовать стандарту PSR-2


## Built With

* [Symfony](http://www.symfony.com/) - The web framework used



## Authors

* **Maxim Yalagin** - *Initial work* -
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details




