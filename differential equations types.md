# Дифференциальные уравнения
## Таблица интегралов

$$
\int a^x dx = \frac{a^x}{\ln(a)} + C
$$

$$
\int \frac{1}{\sqrt{a^2-x^2}} dx = \arcsin\left(\frac{x}{a}\right) + C
$$

$$
\int \frac{1}{a^2+x^2} dx = \frac{1}{a} \arctan\left(\frac{x}{a}\right) + C
$$

$$
\int \frac{1}{a^2-x^2} dx = \frac{1}{2a} \ln \left| \frac{a+x}{a-x} \right| + C
$$

$$
\int \frac{1}{\sqrt{x^2 \pm a^2}} dx = \ln \left| x + \sqrt{x^2 \pm a^2} \right| + C
$$

$$
\int \frac{1}{\sin^2{(x)}} dx = -\cot{(x)} + C
$$

$$
\int \frac{1}{\cos^2{(x)}} dx = \tan{(x)} + C
$$

## Геометрия
**Уравнение касательной к функции в точке ($$x_0, y_0$$):**

$$
y(x)=f'(x_0)(x-x_0)+f(x_0)
$$

## Основные типы дифференциальных уравнений
### Уравнение с разделяющимися переменными (УРП):
1. $M(x)N(y)dx + P(x)Q(y)dy = 0$

**Решение:**

$$
M(x)N(y)dx + P(x)Q(y)dy = 0
$$

$$
P(x)Q(y)dy = -M(x)N(y)dx |:P(x)|:N(y)
$$

$$
\frac{Q(y)}{N(y)}dy = -\frac{M(x)}{P(x)}dx
$$

$$
\int \frac{Q(y)}{N(y)}dy = -\int \frac{M(x)}{P(x)}dx
$$

**Важно:** Необходимо проверить, являются ли функции $P(x) = 0$ и $N(y) = 0$ решениями

2. $y'(x)=M(x)N(y)$

**Решение:**

$$
y'(x)=M(x)N(y)
$$

$$
\frac{dy}{dx}=M(x)N(y) | :N(y) | \cdot dx
$$

$$
\frac{dy}{N(y)}=M(x)dx
$$

$$
\int \frac{dy}{N(y)}= \int M(x)dx
$$

**Важно:** Необходимо проверить, является ли функция $N(y) = 0$ решением

### Уравнение, сводящееся к уравнению с разделяющимися переменными (Св. к УРП):
$y'(x)=f(ax+by(x)+c)$

**Решение:**

Сделаем замену

$$
\begin{aligned}
z(x) = ax+by(x)+c \quad (1) \\
z'(x) = a+by'(x) \quad (2)
\end{aligned}
$$

Из (2) уравнения выражается $$y'(x)$$, подставляем $$z(x)$$ и $$y'(x)$$ в исходное уравнение, получаем

$$
\frac{z'(x)}{b} - a = f(z(x)) \quad (УРП)
$$

