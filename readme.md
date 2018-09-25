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
var a = plural(2, 'чашка', 'чашки', 'чашек'); // чашка
var b = plural(10, 'чашка', 'чашки', 'чашек'); // чашек

// English text
var c = plural(1, 'cup', 'cups', 'cups'); // cup
var d = plural(10, 'cup', 'cups', 'cups'); // cups
```
