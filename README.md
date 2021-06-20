# frequent-styles  
### 📦 Набор часто используемых css-классов  
- [Margin и padding отступы](#id1)
- [Стили для текста](#id2)
- [Opacity](#id3)
- [Flex, позиционирование, размер](#id4)
- [Другие](#id5)

# Установка  📥 
**Npm**  
```
npm i frequent-styles  
```  
**Yarn**  
```  
yarn add frequent-styles  
```  
  
# <a id="id1">📍 Margin и padding отступы</a>
### Сокращения:  
 - `left` => `l`  
 - `right` => `r`  
 - `top` => `t`  
 - `bottom` => `b`  
 - `margin` => `m`  
 - `padding` => `p`  
### Значения:  
`5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 75, 100`  
### Примеры:  
  
| Класс               | Значение                                                      |  
| ------------------- | ------------------------------------------------------------- |  
| `mr-10 mb-50`    	  | `margin-right: 10px; margin-bottom: 50px;` 					  |  
| `m-25` 			  | `margin: 25px;` 										   	  |  
| `p-50` 			  | `padding: 50px;` 											  |  
| `pr-35 pl-100` 	  | `padding-right: 35px; padding-left: 100px;` 				  |  

# <a id="id2">📍 Стили для текста</a>
  
| Класс               | Значение                                                      |  
| ------------------- | ------------------------------------------------------------- |  
| `text-center`       | `text-align: center;`|  
| `text-capitalize`   | `text-transform: capitalize;`|  
| `text-uppercase`    | `text-transform: uppercase;`|  
| `text-lowercase`    | `text-transform: lowercase;`|  
| `text-truncate`     | `white-space: nowrap; overflow: hidden; text-overflow: ellipsis;`| 
| `fw-normal`    	  | `font-weight: normal;`|  
| `fw-bold`           | `font-weight: bold;`|  

# <a id="id3">📍 Opacity</a>

| Класс      | Значение      |
| ---------- | ------------- |
| `opacity-1`  | `opacity: 0.1;` |
| `opacity-2`  | `opacity: 0.2;` |
| `opacity-3`  | `opacity: 0.3;` |
| `opacity-4`  | `opacity: 0.4;` |
| `opacity-5`  | `opacity: 0.5;` |
| `opacity-6`  | `opacity: 0.6;` |
| `opacity-7`  | `opacity: 0.7;` |
| `opacity-8`  | `opacity: 0.8;` |
| `opacity-9`  | `opacity: 0.9;` |
| `opacity-1`0 | `opacity: 1;  ` |

# <a id="id4">📍 Flex, позиционирование, размер</a>

| Класс           | Значение                        |
| --------------- | ------------------------------- |
| `h100p          `| `height: 100%;                  `|
| `w100p          `| `width: 100%;                   `|
| `d-ib           `| `display: inline-block;         `|
| `d-if           `| `display: inline-flex;          `|
| `d-flex         `| `display: flex;                 `|
| `d-block        `| `display: block;                `|
| `justify-between`| `justify-content: space-between;`|
| `justify-around `| `justify-content: space-around; `|
| `justify-center `| `justify-content: center;       `|
| `align-center   `| `align-items: center;           `|
| `align-end      `| `align-items: flex-end;         `|
| `align-start    `| `display: inline-block;         `|
| `flex-column    `| `flex-direction: column;        `|
| `flex-row       `| `flex-direction: row;           `|
| `flex-wrap      `| `flex-wrap: wrap;               `|
| `flex-auto      `| `flex: 1 1 auto;                `|
| `flex           `| `flex: 1;                       `|
| `m-auto         `| `margin: auto;                  `|
| `ml-auto        `| `margin-left: auto;             `|
| `mr-auto        `| `margin-right: auto;            `|
| `text-center    `| `text-align: center;            `|
| `pos-r          `| `position: relative;            `|
| `pos-a          `| `position: absolute;            `|

# <a id="id5">📍 Другие</a>
| Класс           | Значение                        |
| --------------- | ------------------------------- |
| `cu-p            `| `cursor: pointer;               `|
