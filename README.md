# Курсовая работа

Выполнено:

1) Создано два вида оружия: лазер и сфера.
   
   Лазер:
   - наносит урон первому вражескому актору, попавшему под луч
   - количество наносимого урона зависит от времени наведения на цель (урон в секунду)
   - имеет максимальное расстояние нанесения урона
   - (**доп. задание**) имеет огранниченное число снарядов, после израсходования обоймы необходима перезарядка (перезарядить оружие можно даже если не все патроны израсходованы)
     
   Сфера:
   - накапливает заряд при зажатии лкм
   - при отпускании лкм наносит урон всем вражеским акторам, находящимся внутри сферы
   - количество урона и радиус его нанесения зависят от времени зарядки сферы
   - имеет ограничение по максимальному накопленному заряду
  
2) Настроены клавиши для управления:
   - лкм запускает активное оружие
   - 
   - переключение между режимами оружия при помощи колесика мыши
   - клавиша "1" активирует лазер
   - клавиша "2" актифирует сферу
   - клавиша "R" активирует перезарядку лазера
   - оружие не может быть переключено, если зажата кнопка выстрела

3) Созданы цели, которые могут получать урон.

   Коробка:
   - может получать урон, после того как уровень здоровья опустится ниже 0 - уничтожается
   - служит укрытием в бою
  
   Турель:
   - ищет ближайшего игрока, не спрятанного за укрытиями, в радиусе действия своего лазера и наносит ему урон
   - может получать урон, после того как уровень здоровья опустится ниже 0 - уничтожается
   - наносит урон только игрокам
  
   Игрок:
   - может получать урон, после того как уровень здоровья опустится ниже 0 - уничтожается
  
4) Когда все игроки погибают, уровень перезапускается

