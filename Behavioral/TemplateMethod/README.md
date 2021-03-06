### Template Method

#### Type: Behavioral

#### What it is:
Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure.

![TemplateMethod]

```php

$game = new FootballGame;
$result = $game->play();
$this->assertTrue($result);


$game = new BasketballGame;
$result = $game->play();
$this->assertTrue($result);

```
_[ru][Ru TemplateMethod]_

[TemplateMethod]: https://github.com/olegre/DesignPatterns/blob/master/~images/TemplateMethod.png
[Ru TemplateMethod]: https://github.com/olegre/DesignPatterns/blob/master/~images/ru/TemplateMethod.png
