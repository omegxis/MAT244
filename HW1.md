Task 1a) $\frac{dy}{dx} = xsin(x^2)-\frac{1}{1+x^2}, y(0)=0$
$$
dy = (xsin(x^2)-\frac{1}{1+x^2})dx \newline
\int dy = \int (xsin(x^2)-\frac{1}{1+x^2})dx \newline
\int dy = \int (xsin(x^2))dx - \int \frac{1}{1+x^2}dx
$$
$\int (xsin(x^2))dx:$ let u = $x^2$, $du = 2xdx. \implies dx= \frac{du}{2x}$
$$
\int xsin(u)\frac{du}{2x} = \frac{1}{2}\int sin(u)du = \frac{1}{2}-cos(u)+c = \frac{1}{2}(-cos(x^2)) \newline = \frac{-cos(x^2)}{2} +c
$$
$\int \frac{1}{1+x^2}dx$: let u = $tan(\theta) dx = sec^2(\theta)d\theta$
$$
\int \frac{sec^2\theta d\theta}{1+tan^2\theta} = \int \frac{1+tan^2\theta d\theta}{1+tan^2\theta} = \int d\theta = \theta +c \newline
x = tan\theta \implies tan^{-1}x = \theta \implies tan^{-1}x+c
$$

$$
\implies \frac{-cos(x^2)}{2}-tan^{-1}+c
$$

$$
y(0) = 0 \implies 0 = \frac{-cos(0^2)}{2}-tan^{-1}(0)+c \newline
\implies 0 = \frac{-1}{2} - 0 + c \implies c = \frac{1}{2}
$$

$\framebox[1.1\width]{$\therefore y = \frac{-cos(x^2)}{2}-tan^{-1}x+\frac{1}{2}$}$



b)  some text



---------------





Task 2a) 
$$
\frac{dv}{dt} = -3v \newline \frac{dv}{v}=-3dt \newline
\int \frac{dv}{v} = \int -3dt \newline ln\abs{v} = -3t+c \newline
\abs{v} = e^{-3t+c} = e^3e^c \implies e^c = k \newline
\abs{v} = ke^{-3t} \implies v = ke^{-3t}
\newline
v_0 = e^{0}e^c \newline v_0 = e^c
$$
$\framebox[1.1/width]{$\therefore v = v_0e^{-3t}$}$



b) 
$$
x'(t) = v_0e^{-3t} \implies \int x'(t)dt = \int v_0e^{-3t}dt \newline
\implies x(t) = -\frac{1}{3}v_0e^{-3t} +c \newline
0 = -\frac{1}{3}v_0e^{-3*0}+c \newline \implies
\frac{1}{3}v_0 = c 
\newline \implies
x(t) = -\frac{1}{3}v_0e^{-3t}+\frac{1}{3}v_0
$$

$$
\lim_{x\to\infty}x(t) = \lim_{x\to\infty}(\frac{v_0}{3}-\frac{1}{3}v_0e^{-3t}) \newline
= \frac{v_0}{3} -\frac{1}{3}v_0(0) \space : \text{$e^{-3t}$ approaches 0 as t approches infinity}
\newline
= \frac{v_0}{3}
$$



$\framebox[1.1\width]{$\therefore x(t) = -\frac{1}{3}v_0e^{-3t}+\frac{1}{3}v_0   $ and the limit position of the boat as $\lim_{x\to\infty}x(t) = \frac{v_0}{3}$ }$



-----------





Task 4a)

