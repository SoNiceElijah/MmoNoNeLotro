# Предметы

Юзаем **Javascript**

## Version 0.0.1

```Javascript

let Ring = {
    name : "Единое кольцо",
    description : "Выковано в недрах Роковой горы",
    quality : "Immortal",
    quality_num : 100500,
    effect : {
        strength : +100,
        agility : +100,
        intelligence : +100,

        buffs : [
            "Моя прелес-с-сть!"
        ]
    },

    use : (target) => {

        this.GOD.AddBuff(target, "Инвиз");
        this.GOD.AddBuff(target, "Очко Сурона");

    },
}

```
