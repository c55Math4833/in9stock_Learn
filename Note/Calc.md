* * *

## 1極限

&emsp;<span style="color: red;">定義</span>:

$$
\begin{aligned}
	&\lim_{x\rightarrow a}(L)\Leftrightarrow \forall \varepsilon > 0,\quad \delta > 0
	\\~\\
	&\ni 0<\left | x-a \right |<\delta \\
	&\left | f(x)-L \right |<\varepsilon\quad恆成立
\end{aligned}
$$

&emsp;`*註:∀≡forall 對於所有;∃≡ezist 存在;∋≡such that 使得;δ⇒很小的自變數(x);ε⇒很小的因變數(y)`

`對於所有(∀)打靶誤差(ε),都存在(∃)拉弓長度(δ),使得拉弓長度x接近a時,打靶的結果就接近L`
 <span style="color: deeppink;">計算</span>:\[直接帶入\];\[約分\];\[通分\];\[代換\];(羅畢達);\[夾擠\]
&emsp;&emsp;-夾擠<span style="color: red;">定義</span>:

$$
\begin{aligned}
	&若f(x)\leq h(x)\leq g(x),\\
	&且\lim_{x\rightarrow a}(f(x))=\lim_{x\rightarrow a}(g(x))=L,
	\\~\\
	&則\lim_{x\rightarrow a}(h(x))=L
\end{aligned}
$$

**題型:無窮極限**
&emsp;<span style="color: deeppink;">計算</span>:\[相除型→比最大項係數\];\[根式相減型→次大象係數相減\]
&emsp;&emsp;-根式相減型解法:$\lim(\sqrt[c]{x^2+ax^{n-1}+...}-\sqrt[c]{x^2+bx^{n-1}+...})=\frac{a-b}{c}$

**題型:三角極限**
&emsp;<span style="color: deeppink;">計算</span>:\[本尊分身速解\] (由夾擠推導)

$$
\begin{array}{ccc}\hline
\textbf{本尊}&\textbf{分身}&\textbf{應用}\\\hline
\text{sin(x)}&\displaystyle{x}&\ \displaystyle\lim_{x\rightarrow0}(\frac{sin(x)}{x})\approx\lim_{x\rightarrow0}(\frac{x}{x})=1\\\hline
\text{tan(x)}&\displaystyle{x}&\ \displaystyle\lim_{x\rightarrow0}(\frac{tan(x)}{x})\approx\lim_{x\rightarrow0}(\frac{x}{x})=1\\\hline
\text{1-cos(x)}&\displaystyle\ \frac{x^2}{2}&\ \displaystyle\lim_{x\rightarrow0}(\frac{1-cos(x)}{x^2})\approx\lim_{x\rightarrow0}(\frac{x^2/2}{x^2})=\frac{1}{2} \\\hline
\end{array}
$$

**題型:含絕對值極限**
 <span style="color: deeppink;">計算</span>:\[直接帶入有解\];\[直接帶入無解或無意義者，使用左右極限法\]

**題型:漸進線**

$$
\begin{array}{cc}\hline
\textbf{垂直漸進線}&\textbf{水平漸進線}\\\hline
\ \displaystyle\lim_{x\rightarrow a^\pm }(f(x))=\pm \infty &\displaystyle\ \lim_{x\rightarrow\pm\infty}(f(x))=L\\\hline
\text{任一成立，則x=a有f(x)垂直漸進線}&\text{任一成立，則y=L有f(x)水平漸進線}\\\hline
\end{array}
$$

&emsp;<span style="color: deeppink;">計算</span>:\[垂直找函數存在不連續處加以檢查\];\[水平求極限=正負無線\]

&emsp;斜漸進線<span style="color: deeppink;">計算</span>:

&emsp;&emsp;$
\begin{aligned}
&若\left\{
	\begin{matrix}
	\begin{aligned}
		&\lim_{x\rightarrow\pm\infty}(\frac{f(x)}{x})=m\\
		&\lim_{x\rightarrow\pm\infty}(f(x)-mx))=b
	\end{aligned}
	\end{matrix}\right.\\~\\
&則y=mx+b
\end{aligned}$
&emsp;&emsp;`*註:證明:`
&emsp;&emsp;&emsp;若:$\displaystyle\lim_{x\rightarrow\pm\infty}(f(x))=mx+b$
&emsp;&emsp;&emsp;1. 同除x:$\displaystyle\lim_{x\rightarrow\pm\infty}(\frac{f(x)}{x})=m+\frac{b}{x}$
&emsp;&emsp;&emsp;2. $\displaystyle\frac{b}{x}趨近於0，故\lim_{x\rightarrow\pm\infty}(\frac{f(x)}{x})=m$


**題型:連續**
&emsp;<span style="color: red;">定義</span>:
&emsp;&emsp;當:
&emsp;&emsp;a. $f(x)$有定值
&emsp;&emsp;b. $\displaystyle\lim_{x→a}(f(x))$存在
&emsp;&emsp;c. $\displaystyle\lim_{x→a}(f(x))=f(a)$

&emsp;&emsp;皆滿足，則$f(x)$於$x=a$連續`(函數值=極限值)`

**題型:勘根定理**
&emsp;<span style="color: red;">定義</span>:

$$
\begin{aligned}
	&若f(x)在閉區間[a,b]為連續,\\
	&且f(a)f(b)<0,
	\\~\\
	&則開區間(a,b)至少有一解
\end{aligned}
$$

&emsp;&emsp;`一正一負必有根，根者有其零`

* * *

## 導數

&emsp;<span style="color: red;">定義</span>:

$$
\begin{aligned}
(一)、&f'(x)=\lim_{\Delta x\rightarrow 0}(\frac{(x_0+\Delta x)-f(x_0)}{\Delta x})=\lim_{\Delta x\rightarrow 0}(\frac{f(x)-f(x_0)}{x-x_0})\\
(二)、&f'(x)=\lim_{h\rightarrow0}(\frac{f(a+h)-f(a)}{h})
\end{aligned}
$$

&emsp;&emsp;`微分就是退化後的前進分之上升 ]`
&emsp;<span style="color: deeppink;">四則運算</span>:

$$
\begin{aligned}
&若f(x),g(x),h(x)可微分,則:\\
&\left\{\begin{matrix}\begin{aligned}
係數可提出: & \frac{d}{dx}(cf(x))=c\frac{d}{dx}(f(x))\\ 
可分離加減: & \frac{d}{dx}(f(x)\pm g(x))=f'(x)\pm g'(x)\\ 
乘法: & \frac{d}{dx}(f(x)g(x))=f'(x)g(x)+g'(x)f(x)\\ 
除法: & \frac{d}{dx}(\frac{f(x)}{g(x)})=\frac{f'(x)g(x)-g'(x)f(x)}{g^2(x)}
\end{aligned}\end{matrix}\right.
\end{aligned}
$$

&emsp;&emsp;`乘法:微前乘後，微後乘前。`
&emsp;&emsp;`除法:微上乘下-微下乘上，下面平方。`
&emsp;<span style="color: deeppink;">合成函數</span>$(f.g)(x)=f(g(x))$:先微外面再微裡面。

**題型:隱微分法**
&emsp;<span style="color: deeppink;">計算</span>:\[左右都微分\]
&emsp;&emsp;`將y視為x的可微函數，兩邊對x微分，移項整理。`

**題型:三角函數微分**
&emsp;<span style="color: deeppink;">計算</span>:
&emsp;&emsp;$\begin{array}{|c|c|}\hline
\text{(sin(x))'=cos(x)}&\text{(cos(x))'=-sin(x)}\\\hline
\ {(ten(x))'=sec^{2}(x)}&\ {(cot(x))'=-csc^{2}(x)}\\\hline
\text{(sec(x))'=sec(x)ten(x)}&\text{(csc(x))'=-csc(x)cot(x)}\\\hline
\end{array}$

**題型:反函數微分**
&emsp;<span style="color: deeppink;">計算</span>:\[微分的倒數\]
&emsp;&emsp;$(f^{-1})'(f(a))=\frac{1}{f'(a)}$
&emsp;&emsp;`*註:證明:`
&emsp;&emsp;&emsp;1. $y為f(x)的反函數:y=f^{-1}(x),即f(y)=x$
&emsp;&emsp;&emsp;2. $以f(y)=x做隱微分:f'(y)y'=1$
&emsp;&emsp;&emsp;故，$y'=\frac{1}{f'(y)}$
&emsp;&emsp;例題:
&emsp;&emsp;&emsp;$\begin{aligned}
&f(x)=x^3-2,\quad求(f^{-1})'(6)=?\\
&f(x)'=3x^2,\quad f^{-1}(6)=2\\
&\frac{1}{f(2)'}=\frac{1}{3(2)^2}=\frac{1}{12}
\end{aligned}$

**題型:特殊函數微分**
&emsp;<span style="color: deeppink;">對數微分</span>:
&emsp;&emsp;$\frac{d}{dx}(\ln(f(x)))=\frac{1}{f(x)}f'(x)$
&emsp;&emsp;$\frac{d}{dx}(\log_{a}(f(x)))=\frac{f'(x)}{\ln(a)f(x)}$

&emsp;<span style="color: deeppink;">指數微分</span>:上微下對抄一遍
&emsp;<span style="color: deeppink;">反三角微分</span>:
&emsp;&emsp;$\begin{array}{|c|c|}\hline
\ (sin^{-1}(x))'=\frac{1}{\sqrt{1-x^2}}&\ (cos^{-1}(x))'=-\frac{1}{\sqrt{1-x^2}}\\\hline
\ (tan^{-1}(x))'=\frac{1}{1+x^2}&\ (cot^{-1}(x))'=-\frac{1}{1+x^2}\\\hline
\ (sec^{-1}(x))'=\frac{1}{x\sqrt{x^2-1}}&\ (csc^{-1}(x))'=-\frac{1}{x\sqrt{x^2-1}}\\\hline
\end{array}$

* * *

## 微分應用

**洛爾定理**
&emsp;<span style="color: red;">定義</span>:
$$\begin{aligned}
若&f(x)在\left [ a,b \right ]連續,\quad且f(x)在(a,b)可微分,\quad又f(a)=f(b)
\\~\\
則&\exists c\in (a,b)\\
&\ni f'(c)=0
\end{aligned}$$
**均值定理**
&emsp;<span style="color: red;">定義</span>:
$$\begin{aligned}
若&f(x)在[a,b]連續,\quad且f(x)在(a,b)可微分
\\~\\
則&\exists c\in (a,b)\\
&\ni f(c)=\frac{f(b)-f(a)}{b-a}
\end{aligned}$$
&emsp;&emsp;`某一點切線斜率=整體變化率`
**均值定理應用:求近似值**
&emsp;<span style="color: deeppink;">計算</span>:$f(x)\fallingdotseq f(x_0)+f'(x_0)(x-x_0)$
&emsp;例題:
&emsp;&emsp;$\begin{aligned}
&求\sqrt[4]{15.7}=?\\
&令f(x)=\sqrt[4]{x},\quad 則f'(x)=\frac{1}{4\sqrt[4]{x^3}}\\
&f(15.7)\fallingdotseq f(16)+f'(16)(15.7-16)=1.990625
\end{aligned}$

**作圖**
&emsp;<span style="color: deeppink;">計算</span>:觀察對稱→觀察漸進線→微分求臨界點、反曲點→做表→繪圖

* * *

## 積分

$$
\begin{array}{|c|c|}\hline
\textbf{原型}&\textbf{擴展}\\\hline
\int \textcolor{cyan}x^n\;dx=\frac{\textcolor{cyan}x^{n+1}}{n+1}+c&\int (a\textcolor{cyan}x+b)^n\;dx=\frac{1}{a}\frac{(a\textcolor{cyan}x+b)^{n+1}}{n+1}+c\\\hline
\int \frac{1}{\textcolor{cyan}x}\;\;dx=\ln(\textcolor{cyan}x)+c&\int \frac{1}{a\textcolor{cyan}x+b}\;dx=\frac{1}{a}\ln(a\textcolor{cyan}x+b)+c\\\hline
\int e^\textcolor{cyan}x\;dx=e^\textcolor{cyan}x+c&\int e^{a\textcolor{cyan}x+b}\;dx=\frac{1}{a}e^{a\textcolor{cyan}x+b}+c\\\hline
\int a^\textcolor{cyan}x\;dx=\frac{a^\textcolor{cyan}x}{\ln(a)}+c&\int a^{a\textcolor{cyan}x+b}\;dx=\frac{1}{a}\frac{a^{a\textcolor{cyan}x+b}}{\ln(a)}+c\\\hline
\end{array}
$$
$$
\begin{array}{|c|c|}\hline
\textbf{原型}&\textbf{擴展}\\\hline
\int sin(\textcolor{cyan}x)\;dx=-cos(\textcolor{cyan}x)+c&\int sin(a\textcolor{cyan}x+b)\;dx=-\frac{1}{a}cos(a\textcolor{cyan}x+b)+c\\\hline
\int cos(\textcolor{cyan}x)\;dx=sin(\textcolor{cyan}x)+c&\int cos(a\textcolor{cyan}x+b)\;dx=\frac{1}{a}sin(a\textcolor{cyan}x+b)+c\\\hline
\int sec^2(\textcolor{cyan}x)\;dx=tan(\textcolor{cyan}x)+c&\int sec^2(a\textcolor{cyan}x+b)\;dx=\frac{1}{a}tan(a\textcolor{cyan}x+b)+c\\\hline
\int\frac{1}{\sqrt{1-\textcolor{cyan}x^2}}\;dx=sin^{-1}(\textcolor{cyan}x)+c&\int\frac{1}{\sqrt{a^2-\textcolor{cyan}x^2}}\;dx=sin^{-1}(\frac{\textcolor{cyan}x}{a})+c\\\hline
\int\frac{1}{1+\textcolor{cyan}x^2}\;dx=tan^{-1}(\textcolor{cyan}x)+c&\int\frac{1}{\sqrt{a^2+\textcolor{cyan}x^2}}\;dx=\frac{1}{a}tan^{-1}(\frac{\textcolor{cyan}x}{a})+c\\\hline
\end{array}
$$

&emsp;<span style="color: cyan;">x</span>可代換u(記得都要再多除係數)
&emsp;`除次方，除係數`
&emsp;<span style="color: deeppink;">計算</span>:\[代換\],\[分部積分\],\[三角代換\],\[部分分式\]
&emsp;<span style="color: deeppink;">分部積分計算</span>:
&emsp;&emsp;$\int f(x)g'(x)\;dx=f(x)g(x)-\int f'(x)g(x)\;dx$
&emsp;&emsp;`*註:證明:`
&emsp;&emsp;&emsp;$\frac{d}{dx}(f(x)g(x))=f'(x)g(x)+f(x)g'(x)$
&emsp;&emsp;&emsp;兩邊積分:$f(x)g(x)=\int f'(x)g(x)\;dx+\int f(x)g'(x)\;dx$
&emsp;&emsp;速解法:
&emsp;&emsp;&emsp;$
\begin{vmatrix}
\pm微分&積分\\ 
+g(x)&f(x)\\ 
-g'(x)&F(x)\\
...&...\\
\pm g^{(n)}(x)&F_n(x) 
\end{vmatrix}
=g(x)F(x)-g'(x)F_2(x)+g^{(2)}(x)F_3(x)-\cdots \pm \int g^{(n)}(x)F_n(x)\;dx$

&emsp;<span style="color: deeppink;">三角代換計算</span>:代換後利用恆等式解題，遇分母有根號之題型大多用此，若根號內多項式需先行配方。
&emsp;&emsp;$\begin{array}{|c|c|c|}\hline
\textbf{遇到}&\textbf{使用}&\textbf{恆等式}\\\hline
\sqrt{a^2-x^2}&x=a\,sin(\theta)代換&1-sin^2\theta=cos^2\theta\\\hline
\sqrt{a^2+x^2}&x=a\,tan(\theta)代換&1+tan^2\theta=sec^2\theta\\\hline
\end{array}$

&emsp;<span style="color: deeppink;">部分分式計算</span>(遮住法):
&emsp;&emsp;$注意(ax+b)^m必須逐項分解成(ax+b)(ax+b)^2...(ax+b)^m$

- 第一類(分母可分解為全不同之一次因式):分母因式分解，依次遮住帶入遮住展開中心。
    例題:
&emsp;$\begin{aligned}
\frac{x+7}{x^2-x-6}&=\frac{x+7}{(x-3)(x+2)}\\&=
\frac{(3)+7}{(\colorbox{gray}x-3)((3)+2)}+\frac{(-2)+7}{((-2)-3)(\colorbox{gray}x+2)}\\
&=\frac{2}{x-3}+\frac{-7}{x+2}
\end{aligned}$

- 第二類(分母有重複分解出相同一次因式):先使用遮住法，在乘重複展開中心後取極限x→∞
    例題:
&emsp;$\begin{aligned}
&\frac{3x}{x^3+x^2-x-1}=\frac{3x}{(x-1)(x+1)^2}\\
&=\frac{3/4}{x-1}+\frac{a}{x+1}+\frac{3/2}{(x+1)^2}\\
同乘(x+1):&\frac{3x}{(x-1)(x+1)}=\frac{(3/4)(x+1)}{x-1}+a+\frac{3/2}{x+1}\\
取極限x\rightarrow\infty:&0=(3/4)+a+0\\
得:&a=-3/4\\
故:&\frac{3x}{x^3+x^2-x-1}=\frac{3/4}{x-1}-\frac{3/4}{x+1}+\frac{3/2}{(x+1)^2}
\end{aligned}$

- 第三類(分母可全分解為重複一次因數):使用綜合除法

**微積分基本定理**
&emsp;<span style="color: red;">定義</span>:
$$\begin{aligned}
&\frac{d}{dx}(\int_{a}^{g(x)}f(t)\;dt)=f(g(x))g'(x)\\
&\frac{d}{dx}(\int_{h(x)}^{g(x)}f(t)\;dt)=f(g(x))g'(x)-f(h(x))h'(x)
\end{aligned}$$
&emsp;`*註:證明:`
&emsp;&emsp;$\begin{aligned}
&\frac{d}{dx}(\int_{a}^{g(x)}f(t)\;dt)=\frac{d}{dx}(F(g(x))-F(a))=f(g(x))g'(x)-f(a)\cdot 0=f(g(x))g'(x)\\
&\frac{d}{dx}(\int_{h(x)}^{g(x)}f(t)\;dt)=\frac{d}{dx}(F(g(x))-F(h(x)))=f(g(x))g'(x)-f(h(x))h'(x)
\end{aligned}$

**瑕積分**
&emsp;<span style="color: red;">定義</span>:不符合1.區間\[a,b\]必有限;2.被積函數f(x)在\[a,b\]必為連續，若不連續則必須有界。任一者則為瑕積分。
&emsp;<span style="color: deeppink;">第一型計算</span>:
&emsp;&emsp;$\left\{\begin{matrix}
\displaystyle\int_{a}^{\infty}f(x)\;dx=\lim_{t\rightarrow\infty}(\int_{a}^{t}f(x)\;dx)\\
\displaystyle\int_{-\infty}^{b}f(x)\;dx=\lim_{t\rightarrow-\infty}(\int_{t}^{b}f(x)\;dx)
\end{matrix}\right.$

- 審歛法:
    
    1.  p級數檢驗法:
    
    $$
    \int_1^\infty\frac{1}{x^p}\;dx\\\left\{\begin{matrix}p>0,\quad收斂\\p<0,\quad發散\end{matrix}\right.
    
    $$
    2.  比較檢驗法:令f與g在\[a,∞)為連續，且∀x≥a恆有0≤f(x)≤g(x)。

$$
\left\{\begin{matrix}
\displaystyle若\int_{a}^{\infty}g(x)\;dx收斂，則\int_{a}^{\infty}f(x)\;dx收斂\\
\displaystyle若\int_{a}^{\infty}f(x)\;dx發散，則\int_{a}^{\infty}g(x)\;dx發散
\end{matrix}\right.
$$

3.  極限比較檢驗法:

$$
\begin{aligned}
若f與g在[a,\infty )為連續，且\lim_{x\rightarrow\infty}(\frac{f(x)}{g(x)})=L\; \; (0<L<\infty)\\~\\
則\int_{a}^{\infty }f(x)\; dx與\int_{a}^{\infty }g(x)\; dx同歛散\end{aligned}
$$

<span style="color: deeppink;">第二型計算</span>:
&emsp;$\left\{\begin{matrix}
\displaystyle\int_{a}^{b}f(x)\; dx=\lim_{t\rightarrow b^-}(\int_{a}^{t}f(x)\; dx)\\ 
\displaystyle\int_{a}^{b}f(x)\; dx=\lim_{t\rightarrow -a^+}(\int_{t}^{b}f(x)\; dx)
\end{matrix}\right.$

- 審歛法:
    - p級數檢驗法:

$$
若\int_{0}^{1}\frac{1}{x^p}\;dx\\
則\left\{\begin{matrix}
p< 1，收斂\\ 
p\geq 1，發散
\end{matrix}\right.
$$

* * *

## 積分應用

**平面曲線長度**
&emsp;$L=\int_{a}^{b}\sqrt{1+(f'(x))^2}\;dx$

**旋轉曲面面積**
&emsp;$\left\{\begin{aligned}
&f(x)於[a,b]繞x軸旋轉曲面面積A=\int_{a}^{b}s\pi f(x)\sqrt{1+(f'(x))^2}\;dx\\ 
&f(x)於[a,b]繞y軸旋轉曲面面積A=\int_{a}^{b}s\pi\sqrt{1+(f'(x))^2}\;dx\;or\;A=\int_{a}^{b}2\pi g(y)\sqrt{1+(f'(x))^2}\;dy
\end{aligned}\right.$

**旋轉曲面體積**
&emsp;圓盤法:
&emsp;&emsp;$f(x)於[a,b]繞x軸體積V=\int_{a}^{b}\pi f^2(x)\;dx$
&emsp;&emsp;$g(y)於[c,d]繞y軸體積V=\int_{c}^{d}\pi g^2(y)\;dy$
&emsp;墊圈法:圓盤法相減而得
&emsp;圓柱殼法:
&emsp;&emsp;$f(x)於[a,b]繞x軸體積V=\int_{a}^{b}2\pi xf(x)\;dx$
&emsp;&emsp;$g(y)於[c,d]繞y軸體積V=\int_{c}^{d}2\pi g(y)\;dy$

**平面型心**
&emsp;$\left\{\begin{matrix}
\displaystyle\bar{x}=\frac{1}{A}\int_{a}^{b}xf(x)\;dx\\ 
\displaystyle\bar{y}=\frac{1}{A}\int_{a}^{b}\frac{1}{2}f(x)\;dx
\end{matrix}\right.\quad(\bar{x},\bar{y})即為型心$

* * *
## 多變數函數
**極限存在問題(齊次函數)**
`y=mx帶入`
題型:齊次函數求極限是否存在
<span style="color: deeppink;">計算</span>:
&emsp;$y=x帶入\lim(f(x,y))=
\left\{\begin{aligned}
&C&，存在\quad\\ 
&g(m)&，不存在
\end{aligned}\right.$
**極限存在問題(極座標代換)**
`x摳ysin`
題型:求雙變數極限是否存在
<span style="color: deeppink;">計算</span>:
&emsp;$\begin{cases}
 x=r\cos(\theta)&\\y=r\sin(\theta)&
\end{cases}帶入\lim(f(x,y))=\left\{\begin{aligned}
&C&，存在\quad\\ 
&g(m)&，不存在
\end{aligned}\right.$
**近似問題**
`全微分`
題型:多變數函數求接近值(類似均值定理)
<span style="color: deeppink;">計算</span>:
&emsp;$f(x+\Delta x,y+\Delta y)=[f(x,y)]+[f_x(x,y)\Delta x]+[f_y(x,y)\Delta y]$
**多變數函數求微分問題**
`上下顛倒，微分加負號`
題型:F(x,y,z)=0求微分
<span style="color: deeppink;">計算</span>:
&emsp;$\frac{\partial x}{\partial x}=-\frac{F_y}{F_x}$
**二元函數求極值問題**
`微分聯立求臨界點→二階判定`
題型:f(x,y)求極值
<span style="color: deeppink;">計算</span>:
&emsp;1. $sloves\left\{\begin{matrix}F_x(x,y)=0\\F_y(x,y)=0\end{matrix}\right.解出臨界點x_0,y_0$
&emsp;2. $\Delta =\begin{vmatrix}F_{xx} &F_{xy} \\ F_{yx}&F_{yy}\end{vmatrix}判定$
&emsp;&emsp;3-1. $若\Delta > 0，則\begin{cases}
 f_{xx}(x_0,y_0)>0，極小\\ 
 f_{xx}(x_0,y_0)<0，極大
\end{cases}$
&emsp;&emsp;3-2. $若\Delta < 0，則(x_0,y_0)為鞍點$

* * *
## 幾何應用
**面積求極值問題**
`注意面積及邊`
題型:f(x,y)及頂點求極值
<span style="color: deeppink;">計算</span>:
&emsp;1. $f(x,y)求臨界點，在圖形範圍內才計算數值。$
&emsp;2. $將邊分離並取xy範圍，令t帶入f(x,y)使之成為單變數方程式$
&emsp;3. 微分求其值
&emsp;4. 統整極值

**點到幾何距離問題**
$f(x,y,\cdots)=(距離)^2=x^2+y^2+\cdots ^2$
題型:$f(x,\cdots)$及基準點$(x_0,\cdots)$求最短距離
<span style="color: deeppink;">計算</span>:
&emsp;1. $將f(x,\cdots)帶入(x-x_0)^2+\cdots+(n-n_0)^2後，可化簡成雙變數$
&emsp;2. 新方程式求臨界點
&emsp;3. 判斷極小值並開根號
* * *
## 重積分
**重積分問題**
`直接積分(先積內在積外)`
題型:雙重積分
<span style="color: deeppink;">計算</span>:先積內在積外
**簡單面積問題**
`找平行、找範圍`
題型:$\iint f(x,y)\;dA$並給予範圍求面積
<span style="color: deeppink;">計算</span>:
&emsp;$\int_{a}^{b}\int_{g_1(x)}^{g_2(x)}f(x,y)\;dy\;dx$
**積分變換順序問題**
`看圖說故事`
題型:雙重積分內部無法直接積時
<span style="color: deeppink;">計算</span>:
&emsp;1. 上下界圖形畫出
&emsp;2. 依圖形一項改變自變數及因變數
&emsp;3. 重寫重積分式






$$
\begin{aligned}
\end{aligned}
$$

$$
\begin{array}{|c|c|}\hline
\textbf{原型}&\textbf{擴展}\\\hline
&\\\hline
&\\\hline
\end{array}
$$


$$\left\{\begin{aligned}
&\\ 
&
\end{aligned}\right.$$
