Завдання 1. Уявімо, що у нас є список студентів та їх оцінок з різних предметів.
Нам потрібно обчислити середній бал кожного студента та вивести на екран список
студентів і їх середніх оцінок. // Список студентів та оцінок Напишіть дві
функції, перша для обчислення середнього балу, друга для виведення списку
студентів та їх середніх оцінок

```js
const students = [
  { name: 'John', grades: [90, 87, 93, 88] },
  { name: 'Jane', grades: [78, 82, 80, 85] },
  { name: 'Mike', grades: [92, 89, 85, 78] },
  { name: 'Anna', grades: [75, 80, 92, 87] },
];
```

Завдання 2. Напиши функцію slugify(string) яка отримує рядок та повертає
URL-slug Рядок складається лише з букв та пробілів

Для перевірки використовуйте

```js
console.log(slugify('Top 10 benefits of React framework'));
console.log(slugify('Azure Static Web Apps are Awesome'));
console.log(slugify('Technical writing tips for non-native English speakers'));
```
