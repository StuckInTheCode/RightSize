# System design (UML)


1. [Диаграмма вариантов использования](#1)<br>
	1.1 [Описание актеров](#1.1)<br>
2. [Варианты использования](#2)<br>
 	2.1. [Выбор пола](#2.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.1.1. [Поток событий](#2.1.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.1.2. [Диаграмма активности](#2.1.2)<br>
	2.2. [Изменение параметров](#2.2)<br>
		2.2.1 [Изменение параметра "Обхват шеи"](#2.2.1)<br>
		2.2.1.1 [Увеличение параметра "Обхват шеи"](#2.2.1.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;	2.2.1.1.1. [Поток событий](#2.2.1.1.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.1.1.2. [Диаграмма активности](#2.2.1.1.2.)<br>
		2.2.1.2 [Уменьшение параметра "Обхват шеи"](#2.2.1.2)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.1.2.1. [Поток событий](#2.2.1.2.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.1.2.2. [Диаграмма активности](#2.2.1.2.2.)<br>
		2.2.2 [Изменение параметра "Обхват груди"](#2.2.2)<br>
		2.2.2.1 [Увеличение параметра "Обхват груди"](#2.2.2.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.2.1.1. [Поток событий](#2.2.2.1.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.2.1.2. [Диаграмма активности](#2.2.2.1.2.)<br>
		2.2.2.2 [Уменьшение параметра "Обхват груди"](#2.2.2.2)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.2.2.1. [Поток событий](#2.2.2.2.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.2.2.2. [Диаграмма активности](#2.2.2.2.2.)<br>
		2.2.3 [Изменение параметра "Обхват талии"](#2.2.3)<br>
		2.2.3.1 [Увеличение параметра "Обхват талии"](#2.2.3.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.3.1.1. [Поток событий](#2.2.3.1.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.3.1.2. [Диаграмма активности](#2.2.3.1.2.)<br>
		2.2.3.2 [Уменьшение параметра "Обхват талии"](#2.2.3.2)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.3.2.1. [Поток событий](#2.2.3.2.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.3.2.2. [Диаграмма активности](#2.2.3.2.2.)<br>
		2.2.4 [Изменение параметра "Обхват бедер"](#2.2.4)<br>
		2.2.4.1 [Увеличение параметра "Обхват талии"](#2.2.4.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.4.1.1. [Поток событий](#2.2.4.1.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.4.1.2. [Диаграмма активности](#2.2.4.1.2.)<br>
		2.2.4.2 [Уменьшение параметра "Обхват талии"](#2.2.4.2)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.4.2.1. [Поток событий](#2.2.4.2.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.2.4.2.2. [Диаграмма активности](#2.2.4.2.2.)<br>
	2.3. [Расчет размера и типа фигуры](#2.3)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.3.1. [Поток событий](#2.3.1)<br>
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;2.3.2. [Диаграмма активности](#2.3.2)<br>
3. [Диаграмма последовательности](#3)<br>
4. [Диаграмма состояний](#4)<br>
5. [Диаграмма классов](#5)<br>
6. [Диаграмма развертывания](#6)<br>



## 1\. Диаграмма вариантов использования <a name = "1"></a>
![use_case_diagram](diagrams/use_case_diagram/use_case_diagram.PNG)
### 1.1\. Описание актеров <a name = "2.1"></a>
<b> Актер: </b> Пользователь .<br>
<b> Описание: </b> Человек, который использует данное приложение.<br>

## 2\. Варианты использования  <a name = "2"></a><br>
Сценарии выполнения вариантов использования описаны с помощью потоков событий и отображены в виде диаграмм активности.
### 2.1\. Выбор пола <a name = "2.1"></a>
<b> Описание: </b> Вариант использования "Выбор пола" позволяет пользователю выбрать пол для дальнейшего расчета.<br>
#### 2.1.1\. Поток событий <a name = "2.1.1"></a>
1. Пользователь нажал кнопку выбора пола;<br>
2. Отображение параметров для ввода, согласно выбранному полу;<br>
3. Конец.<br>

#### 2.1.2\. Диаграмма активности <a name = "2.1.2"></a>
![choose_gender](diagrams/activity_diagrams/choose_gender.PNG)

### 2.2\. Изменение параметров <a name = "2.2"></a>
В данном пункте описываются сценарии выполнение вариантов использования для различных параметров и способов изменения.

#### 2.2.1\. Изменение параметра "Обхват шеи"<a name = "2.2.1"></a>
##### 2.2.1.1\. Увеличение параметра "Обхват шеи" <a name = "2.2.1.1"></a>
<b> Описание: </b> Вариант использования "Увеличение параметра "Обхват шеи"" позволяет пользователю увеличить значение параметра "Обхват шеи".<br>
#####  2.2.1.1.1\. Поток событий <a name = "2.2.1.1.1"></a>
1. Пользователь нажал кнопку "+" для параметра "Обхват шеи";<br>
2. Проверить, является ли текущее значение параметра максимальным. Если да, то переход к шагу 4, иначе к шагу 3;<br>
3. Увеличить текущее значение параметра и отобразить новое значение на экран;<br>
4. Конец.<br>
#####  2.2.1.1.2\. Диаграмма активности <a name = "2.2.1.1.2"></a>
![increase_neck](diagrams/activity_diagrams/increase_neck.PNG)

##### 2.2.1.2\. Уменьшение параметра "Обхват шеи" <a name = "2.2.1.2"></a>
<b> Описание: </b> Вариант использования "Уменьшение параметра "Обхват шеи"" позволяет пользователю уменьшить значение параметра "Обхват шеи".<br>
#####  2.2.1.2.1\. Поток событий <a name = "2.2.1.2.1"></a>
1. Пользователь нажал кнопку "-" для параметра "Обхват шеи";<br>
2. Проверить, является ли текущее значение параметра минимальным. Если да, то переход к шагу 4, иначе к шагу 3;<br>
3. Уменьшить текущее значение параметра и отобразить новое значение на экран;<br>
4. Конец.<br>
##### 2.2.1.2.2\. Диаграмма активности <a name = "2.2.1.2.2"></a>
![reduce_neck](diagrams/activity_diagrams/reduce_neck.PNG)

#### 2.2.2\. Изменение параметра "Обхват груди"<a name = "2.2.2"></a>
##### 2.2.2.1\. Увеличение параметра "Обхват груди" <a name = "2.2.2.1"></a>
<b> Описание: </b> Вариант использования "Увеличение параметра "Обхват груди"" позволяет пользователю увеличить значение параметра "Обхват груди".<br>
##### 2.2.2.1.1\. Поток событий <a name = "2.2.2.1.1"></a>
1. Пользователь нажал кнопку "+" для параметра "Обхват груди";<br>
2. Проверить, является ли текущее значение параметра максимальным. Если да, то переход к шагу 4, иначе к шагу 3;<br>
3. Увеличить текущее значение параметра и отобразить новое значение на экран;<br>
4. Конец.<br>
##### 2.2.2.1.2\. Диаграмма активности <a name = "2.2.2.1.2"></a>
![increase_chest](diagrams/activity_diagrams/increase_chest.PNG)

##### 2.2.2.2\. Уменьшение параметра "Обхват груди" <a name = "2.2.2.2"></a>
<b> Описание: </b> Вариант использования "Уменьшение параметра "Обхват груди"" позволяет пользователю уменьшить значение параметра "Обхват груди".<br>
##### 2.2.2.2.1\. Поток событий <a name = "2.2.2.2.1"></a>
1. Пользователь нажал кнопку "-" для параметра "Обхват груди";<br>
2. Проверить, является ли текущее значение параметра минимальным. Если да, то переход к шагу 4, иначе к шагу 3;<br>
3. Уменьшить текущее значение параметра и отобразить новое значение на экран;<br>
4. Конец.<br>
##### 2.2.2.2.2\. Диаграмма активности <a name = "2.2.2.2.2"></a>
![reduce_chest](diagrams/activity_diagrams/reduce_chest.PNG)

#### 2.2.3\. Изменение параметра "Обхват талии"<a name = "2.2.3"></a>

##### 2.2.3.1\. Увеличение параметра "Обхват талии" <a name = "2.2.3.1"></a>
<b> Описание: </b> Вариант использования "Увеличение параметра "Обхват талии"" позволяет пользователю увеличить значение параметра "Обхват талии".<br>
##### 2.2.3.1.1\. Поток событий <a name = "2.2.3.1.1"></a>
1. Пользователь нажал кнопку "+" для параметра "Обхват талии";<br>
2. Проверить, является ли текущее значение параметра максимальным. Если да, то переход к шагу 4, иначе к шагу 3;<br>
3. Увеличить текущее значение параметра и отобразить новое значение на экран;<br>
4. Конец.<br>
##### 2.2.3.1.2\. Диаграмма активности <a name = "2.2.3.1.2"></a>
![increase_waist](diagrams/activity_diagrams/increase_waist.PNG)

##### 2.2.3.2\. Уменьшение параметра "Обхват талии" <a name = "2.2.3.2"></a>
<b> Описание: </b> Вариант использования "Уменьшение параметра "Обхват талии"" позволяет пользователю уменьшить значение параметра "Обхват талии".<br>
##### 2.2.3.2.1\. Поток событий <a name = "2.2.3.2.1"></a>
1. Пользователь нажал кнопку "-" для параметра "Обхват талии";<br>
2. Проверить, является ли текущее значение параметра минимальным. Если да, то переход к шагу 4, иначе к шагу 3;<br>
3. Уменьшить текущее значение параметра и отобразить новое значение на экран;<br>
4. Конец.<br>
##### 2.2.3.2.2\. Диаграмма активности <a name = "2.2.3.2.2"></a>
![reduce_waist](diagrams/activity_diagrams/reduce_waist.PNG)


#### 2.2.4\. Изменение параметра "Обхват бедер"<a name = "2.2.4"></a>
##### 2.2.4.1\. Увеличение параметра "Обхват бедер" <a name = "2.2.4.1"></a>
<b> Описание: </b> Вариант использования "Увеличение параметра "Обхват бедер"" позволяет пользователю увеличить значение параметра "Обхват бедер".<br>
##### 2.2.4.1.1\. Поток событий <a name = "2.2.4.1.1"></a>
1. Пользователь нажал кнопку "+" для параметра "Обхват бедер";<br>
2. Проверить, является ли текущее значение параметра максимальным. Если да, то переход к шагу 4, иначе к шагу 3;<br>
3. Увеличить текущее значение параметра и отобразить новое значение на экран;<br>
4. Конец.<br>
##### 2.2.4.1.2\. Диаграмма активности <a name = "2.2.4.2.2"></a>
![increase_hips](diagrams/activity_diagrams/increase_hips.PNG)
##### 2.2.4.2\. Уменьшение параметра "Обхват бедер" <a name = "2.2.4.2"></a>
<b> Описание: </b> Вариант использования "Уменьшение параметра "Обхват бедер"" позволяет пользователю уменьшить значение параметра "Обхват бедер".<br>
##### 2.2.4.2.1\. Поток событий <a name = "2.2.4.2.1"></a>
1. Пользователь нажал кнопку "-" для параметра "Обхват бедер";<br>
2. Проверить, является ли текущее значение параметра минимальным. Если да, то переход к шагу 4, иначе к шагу 3;<br>
3. Уменьшить текущее значение параметра и отобразить новое значение на экран;<br>
4. Конец.<br>
##### 2.2.4.2.2\. Диаграмма активности <a name = "2.2.4.2.2"></a>
![reduce_hips](diagrams/activity_diagrams/reduce_hips.PNG)

### 2.3\. Расчет парамеров <a name = "2.3"></a>
<b> Описание: </b> Вариант использования "Расчет парамеров" отображает на экран  результат расчет размера и типа фигуры на основе параметров, введенных пользователем.<br>
#### 2.3.1\. Поток событий <a name = "2.1.1"></a>
1. Пользователь нажал кнопку "Расчитать";<br>
2. Получить текущие значения параметров и произвести расчет;<br>
3. Отобразить экран с результатом расчета;<br>
4. Конец.<br>

#### 2.3.2\. Диаграмма активности <a name = "2.1.2"></a>
![calculate](diagrams/activity_diagrams/calculate.PNG)

## 3\. Диаграмма последовательности <a name = "3"></a>
![sequence_diagram](diagrams/sequence_diagram/sequence_diagram.PNG)

## 4\. Диаграмма состояний <a name = "4"></a>
![state_mashine_diagram](diagrams/state_mashine_diagram/state_mashine_diagram.png)

## 5\. Диаграмма классов <a name = "5"></a>
![class_diagram](diagrams/class_diagram/class_diagram.PNG)


## 6\. Диаграмма развертывания <a name = "6"></a>
![deployment_diagram](diagrams/deployment_diagram/deployment_diagram.PNG)