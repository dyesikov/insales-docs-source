# ui-product-sku
  Компонент выводит артикул товара.

## Пример использования

````html
<ui-product-sku
  instance-name="main"
  caption="{{ messages.label_article }}"
  delemiter=":"
>
</ui-product-sku>
````

## Параметры

Данный компонент поддерживает следущие параметры

* `instanceName` - Имя инстанса компонента продукта для связывания.
* `caption` - Текст перед артикулом.
* `delemiter` - Разделитель текста и артикула.

## Темизация
* `layout` - 
  - `reverse` - Меняет местами заголовок и артикул.
* `color-sheme`
  - `mono` - Окрашивает текст в оттенок цвета текста.