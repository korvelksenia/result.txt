# result.txt
### 1. Удалить все пустые строки

#### Заменила все \n\r вхождения на \0

 **До:**
 
![](https://raw.githubusercontent.com/korvelksenia/photo/master/Снимок%20экрана%20(199).png)

**После:**

![](https://raw.githubusercontent.com/korvelksenia/photo/master/Снимок%20экрана%20(201).png)

### 2. Найти всех князей и города, имя и название которых оканчивается на "слав". В выдаче должны быть такие слова как "Ярославля, Ростиславъ, Ростиславу, Переяславлъ" и т.п. Но не должно быть "славу, выславше" и т.п. 

![](https://raw.githubusercontent.com/korvelksenia/photo/master/Снимок%20экрана%20(204).png)

#### **Использовала регулярное выражение:** [А-Я]*?слав

#### **Всего упоминаний о князьях нашел:** 653


### 3. Найти все упоминания Новгорода. Учтите, что написание может быть разным . В выдаче должны быть такие слова как "Новѣгородѣ, Новъгородъ, Новгородцю, Новагорода, Новугороду". 

![](https://raw.githubusercontent.com/korvelksenia/photo/master/Снимок%20экрана%20(206).png)

#### **Использовал регулярное выражение:** Нов(Нов(ѣ|ъ|о|а|у)город(ѣ|а|у|е|ом|ъ|цю)
#### **Всего упоминаний Новгорода нашел:**  56

![](https://raw.githubusercontent.com/korvelksenia/photo/master/Снимок%20экрана%20(205).png)

#### **Использовал регулярное выражение:** Нов.?город(.|)*?
#### **Всего упоминаний Новгорода нашел:** 59 
