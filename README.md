### rid.us

При 1 уровне вложенности *сложных* блоков использовать селектор дочернего элемента
```
.b > .elem
```
а не
```
.b .elem
```
(в случае если в такой блок будет включен подобный, стили `.elem` не будут перебиты).
В случае простых блочков это можно не делать.

