_Rainbow Computer_ _Reverse engineering and recreation retro computer Rainbow_

#  Компьютер "Радуга" 
_Востановление информации о ретро компьютере_ 


Компьютер "Радуга" был разработан в Омском Авиационном Техникуме (ОМАВИАТ) и запущен в производство весной-летом 1988 года, собирался студентами в радиомонтажных мастерских. Этот компьютер не является значимым с точки зрения распространённости и популярности. Но все же заслуживает внимания из-за особенностей архитектуры. Данная ветка создана для того чтобы ознакомить интересующихся с этими особенностями.

## Кратко описание компьютера

Компьютер "Радуга" был разработан в Омском Авиационном Техникуме (ОМАВИАТ) и запущен в производство весной-летом 1988 года, собирался студентами в радиомонтажных мастерских. Этот компьютер не является значимым с точки зрения распространённости и популярности. Но все же заслуживает внимания из-за особенностей архитектуры. Данная ветка создана для того чтобы ознакомить интересующихся с этими особенностями.

Схема базируется на компьютере СПЕЦИАЛИСТ поэтому ниже приведена таблица различий. 

|                                  | СПЕЦИАЛИСТ                         | РАДУГА                           |
|---|---|---|
| **Процессор** | 580ИК80 | 580ИК80 |
| **Разрешение** | 384x256 | 384x256 |
| **Цветов** | 1 бит монохром | 16 цветов фона и 16 цветов изображения на каждые 8 пикселов | 
| **Бордюр** | нет | Один из 16 цветов | 
| **Палитра** | нет | 256 цветов |
| **Графическая память** | 12КБ | 24КБ видимая область |
|  |  | 4КБ цветной шрифт |
| **Дополнитьно**      |                            | Ускоритель копирования графики |
| **ОЗУ** | 48КБ | 64КБ |
|     |      | 48КБ Прямой доступ в память  |
|     |      | 16КБ (цвет) Косвенный доступ |
| **ПЗУ** | 2КБ | 6КБ (3x2КБ) |
| **Прерывания** | Нет | 50Hz |
| **Звук** | 1 битный, программируемый | 4 аппаратных канала |
|      |                           | 8 уровней громкости в канале |
|      |                           | 3 програмируемых таймера, 1 канал шума |
|      |                           | Доступен синтез звука изменением громкости |
| **Разьем расширения**      |  не специфицирован                          | 16 битный GPIO |
| **Количество микросхем** | 45 | 80 |

## Принципиальная Схема

Поэтапный процесс восстановления схемы описан [тут](storyboard/README.md)

Принципиальная схема в папке _sch_. 

**Версии:**

- Альфа версия схемы максимально соотвествует схеме оригинального компьютера. 
- Бета версия схемы может иметь незначительные изменения от оригинала.

