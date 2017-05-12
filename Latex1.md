##数学解法
###1.抛物线
抛物线的方程:
$$\because y=ax^2$$
$$y^{''}=2a,y^{'2}=4a^2x^2$$
$$
\therefore K=\frac{2a}{(1+4a^2x^2)^{\frac3 2}}
$$
所以抛物线的曲率为:
$$\rho=\frac{1}{K}=\frac{(1+4a^2x^2)^{\frac 3 2}}{2a}$$
###2.椭圆
椭圆的方程:
$$\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$$
$$\because\frac{2x}{a^2}+\frac{2yy^{'}}{b^2}=0$$
$$y^{'}=-\frac{b^2y}{a^2x},\ \ \ y^{''}=-\frac{b^4}{a^2y^3}$$
$$\therefore
K=\frac
{\frac{b^4}{a^2y^3}}
{(1+\frac{b^4y^2}{a^4x^2})^\frac 3 2}
$$
所以椭圆的曲率为:
$$\rho=\frac{a^4b^4}{(a^4y^2+b^4x^2)^\frac3 2}$$
###3.摆线
摆线的方程:
$$\left\{ {x=r(t-\sin t) \atop y=r(1-\cos t)} \right.$$
依次进行求导:
$$
\left\{ {x^{'}=r(1-\cos t) \atop y^{'}=r\sin t} \right.
\ \ \ \
\left\{ {x^{''}=r\sin t \atop y^{''}=r\cos t} \right.
$$
$$
\because K=\frac{r^2(1-\cos t)}{r^3(2-2\cos t)^\frac 3 2}
$$
$$\therefore \rho=4r\sin\frac t 2$$
