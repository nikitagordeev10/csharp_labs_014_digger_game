# Платформа: ulearn
## Курс: Основы программирования
### Тема: 12 Наследование
#### Практика «Земля и Диггер»
##### Решено 02 декабря 2022 в 21:46

Когда-то Digger был одной из самых продвинутых и интересных компьютерных игр. 

Наполнил готовую заготовку игровыми элементами. Каждый элемент умеет:
- Возвращать имя файла, в котором лежит соответствующая ему картинка (например, "Terrain.png")
- Сообщать приоритет отрисовки. Чем выше приоритет, тем раньше рисуется соответствующий элемент, это важно для анимации.
- Действовать — возвращать направление перемещения и, если объект во что-то превращается на следующем ходу, то результат превращения.
- Разрешать столкновения двух элементов в одной клетке.

Сделан класс Terrain, реализован ICreature так, чтобы он ничего не делал.

Сделан класс Player, реализован ICreature.

Сделано так, чтобы диггер шагал в разные стороны в зависимости от нажатой клавиши со стрелкой (Game.KeyPressed). Диггер не покидает пределы игрового поля.

Сделано так, чтобы земля исчезала в тех местах, где прошел диггер.

В методе Game.CreateMap мы можем менять карту, на которой будет запускаться игра. 