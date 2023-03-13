Для демонстрації використання патерну Прототип була створена демо-програма "Калькулятор для ресторану", 
що розраховує суму загальної оплати з врахуванням % чайових, які бажає оплатити клієнт.
Програму реалізовано на JavaScript.
Використання шаблону Prototype дозволяє нам визначати методи та властивості на об'єкті-прототипі, які можуть бути спільно
використані всіма екземплярами об'єкта, не визначаючи їх окремо для кожного екземпляра. Це, як правило, призводить до більш
ефективного використання пам'яті та спрощення обслуговування коду.
У коді програми об'єкт BaseBill, з методами calculateTotalBill та clone, визначено за допомогою паттерну Прототип, з методами calculateTotalBill та clone, визначеними на його об'єкті-прототипі. Ці методи можуть використовуватися будь-яким екземпляром об'єкта BaseBill, не визначаючи їх окремо для кожного екземпляра.

Наприклад, коли користувач натискає кнопку "Calculate Bill", створюється новий екземпляр об'єкта BaseBill, використовуючи метод clone. Потім метод calculateTotalBill може бути викликаний на цьому екземплярі для розрахунку загальної вартості рахунку, на основі введення користувача.

Використання шаблону Prototype таким чином дозволяє легко створювати нові екземпляри об'єкта BaseBill з різними властивостями, не визначаючи методи calculateTotalBill та clone окремо для кожного екземпляра.
