# Компонент чекбокса `ui-checkbox`

Компонент чекбокса является одним из составляющих компонента формы `ui-form`, и как правило не используется без него.

## Пример использования

```html
<ui-checkbox
	:name="are_you_agree"
	value="Я согласен"
	label="Я согласен продать свою почку на помощь нуждающимся в почке"
	:default-value="Согласен на все!"
	:rules= "{
		required: true,
	}"
	:checked="true"
	:hide-native="true"
	:disabled="true"
/>
```

## Параметры компонента

- `disabled` - если `true`, то чекбокс будет недоступен для нажатия
- `name` - системное имя чекбокса для отправки в форму. Принимает строку.
- `value` - значение чекбокса для отправки в форму. Строка
- `label` - Подпись к чебоксу. Строка
- `default-value` - значение чекбокса по-умолчанию. Если не указан value, будет отправлено это значение. По-умолчанию `Да`.
- `checked` - выбран ли чекбокс или нет.
- `hide-native` - Отображать нативный чекбокс, или спрятать его и сделать обертку над ним, которая будет более модифицируема.
- `rules` - правила для чекбокса. Принимает в обьекте следующие параметры:
	* `required` - обязателен ли чекбокс для заполнения.
