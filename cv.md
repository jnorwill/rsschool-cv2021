# Имя и фамилия
**Юлия Кухарчик**

## Контакты для связи
**Телефон:** [80336244777](tel:8033624777) **Электронная почта:** [julianorwill@gmail.com](mailto:julianorwill@gmail.com)

## Краткая информация о себе 
*Мне 18 лет, желаю найти род деятельности, который будет мне по душе. Стремительно развиваюсь в разных областях, учусь новому. Обладаю каммуникативными качествами, умею расположить к себе собеседника. Обладаю большим творческим потенциалом. Опыта работы не имею. Среднее образование. Уровень английского языка А1*

## Примеры кода
```
function warnTheSheep(queue) {
    let result = queue.findIndex(function(item, index, array){
    return item =='wolf'
    })
    if (result + 1 == queue.length) {
        return 'Pls go away and stop eating my sheep'
    } else {
        let N = ( queue.length - (result + 1) )
        return `Oi! Sheep number ${N}! You are about to be eaten by a wolf!`
    }
}
```