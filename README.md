# CreatDataSQL
**Основные понятия**

Реляционная модель баз данных определяет способ представления данных (структуру данных), методы защиты данных (целостность данных), и операции, которые можно выполнять с данными (манипулирование данными). Эта модель лежит в основе всех реляционных баз данных до настоящего времени.

**Основные принципы реляционных баз данных:**

Все данные на концептуальном уровне представляются в виде объектов, заданных в виде строк и столбцов, называемых отношением, более распространенное название – таблица;
в пересечение строки и столбца таблицы можно занести только одно значение;
все операции выполняются над целыми отношениями и результатом этих операций является отношение.

https://github.com/Krassilnikov-AV/CreatDataSQL/blob/master/CreateDataBaseSQL/images/creatSQL.PNG

- **отношение**  – это структура данных целиком, набор записей (в обычном понимании – таблица) , в  примере –это Сотрудник;

- **кортеж** – это каждая строка , содержащая данные (более распространенный термин – запись ), например, <001, Борин С.А, 234-01-23, программист>, все кортежи в отношении должны быть различны;

- **мощность** – число кортежей в таблице (проще говоря, число записей), в данном случае 3, мощность отношения может быть любой (от 0 до бесконечности), порядок следования кортежей - неважен;

-**атрибут** – это столбец в таблице (более распространенный термин – поле ), в примере – Табельный номер, Фамилия И.О., Телефон, Должность)

- **размерность** – это число атрибутов в таблице, в данном случае – 4; 
размерность отношения должна быть больше 0, порядок следования атрибутов существенен;

- **домен атрибута** – это допустимые значение (неповторяющиеся), которые можно занести в поле , например для атрибута Должность домен – {инженер, программист}.
