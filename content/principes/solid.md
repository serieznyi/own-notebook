## SOLID

Пять основных принципов объектно-ориентированного 
программирования и проектирования

### Описание 

Програмная сущность - метод, класс, модуль

- The **S**ingle Responsibility Principle - Принцип единственной ответственности
    > Програмная сущность должна иметь одну и только одну причину для изменения. 
        
    Как добиться: 
    
    * Множество мелких сущностей каждая из которых выполняет лишь одну обязанность
    * В случае увеличениея кол-ва обязанностей существующей сущности - вынести 
      часть обязанностей в отдельную сущность
    
    
- [The **O**pen Closed Principle - Принцип открытости/закрытости](./solid/the_open_closed_principle.md)
    
- The **L**iskov Substitution Principe - Принцип подстановки Барбары Лисков

    > Производные классы должны быть заменяемы для своих базовых классов

    * Производные классы не должны ломать поведение заданное базовым классом
    * Подкласс не должен предоставлять вызывающему коду больше, чем базовый класс, и не 
      должен предоставлять вызывающему коду меньше, чем базовый класс

- The **I**ntefrace Segregation Principe - Принцип разделения интерфейса 
    
    > Много интерфейсов, специально предназначенных для клиентов, лучше, чем один интерфейс общего назначения
    
    * Программные сущности не должны зависеть от методов, которые они не используют.
    * Нельзя заставлять клиента реализовать интерфейс, которым он не пользуется.
    
- The **D**ependency Inversion Principe - Инверсия заивисмостей

    > Допустима зависимость от абстракции, а не от конкретной реализации
    
    * Зависьте от абстракций, а не от чего-то конкретного

### Источники
 - Мартин, Роберт (Дядя Боб). [Principles Of OOD](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod). butunclebob.com