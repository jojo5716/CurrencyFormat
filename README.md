GitHub Markup
=============

Is a tiny JavaScript library, providing simple and advanced money and currency formatting

1. Each currency is formatted depending on the locale

Installation
-----------

```html
<script type="text/javascript" src="path/to/file/js/currency-format.js"></script> 
```

Usage
-----

```javascript
var price = currencies.formatMoney();
// € 0.00
var price = currencies.formatMoney(2000.65, 'EUR');
// € 2,000.65
var price = currencies.formatMoney(2000.65, 'EUR', 'es_ES');
// 2.000,65 €
var price = currencies.formatMoney(2000.65, 'EUR', 'en_EN');
// 2.000,65 EUR
var price = currencies.formatMoney(2000.65, 'EUR', 'es_ES', 3, ',');
// 2,000,650 €
var price = currencies.formatMoney(2000.65, 'EUR', 'es_ES', 3, ' ', '.');
// 2 000.650 € 
```

