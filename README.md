# goit-node-hw-01

1. Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
   node index.js --action="list" https://monosnap.com/file/b7O0ouYCQow6lUSMusyU3DlFrqK6F5

2.Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" https://monosnap.com/file/zu5HkgPO1jndfeV760DzhFwd8ywuiO

3. Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
   node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22 https://monosnap.com/file/OSFyihtKkxA0IbScJ7c83W0jKptjcM

4.Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH https://monosnap.com/file/dWtjoTrs3uVPWKqxoQEaRCOSCQYbKl
