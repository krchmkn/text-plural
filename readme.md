# text-plural
Plural text format

## Installation

```
 npm i text-plural
```

## Usage

```
var plural = require('text-plural');
 
// Russian text
plural(2, 'чашка', 'чашки', 'чашек'); // чашка
plural(10, 'чашка', 'чашки', 'чашек'); // чашек

// English text
plural(1, 'cup', 'cups', 'cups'); // cup
plural(10, 'cup', 'cups', 'cups'); // cups
```