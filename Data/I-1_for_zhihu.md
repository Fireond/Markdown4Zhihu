# Part I

## 1 I.1

从对称/变换的角度出发，例如经典的 <img src="https://www.zhihu.com/equation?tex=D_3" alt="D_3" class="ee_img tr_noresize" eeimg="1"> 群（考虑保持平面中的等边三角形不变的操作，如旋转 <img src="https://www.zhihu.com/equation?tex=2\pi /3" alt="2\pi /3" class="ee_img tr_noresize" eeimg="1"> ，轴对称等一共有6种），
进而引入群的定义（封闭、单位元、逆元、结合律），并举了大量经典的例子：有限群如对称群 <img src="https://www.zhihu.com/equation?tex=S_n" alt="S_n" class="ee_img tr_noresize" eeimg="1"> 及其子群 <img src="https://www.zhihu.com/equation?tex=A_n" alt="A_n" class="ee_img tr_noresize" eeimg="1"> ，循环群 <img src="https://www.zhihu.com/equation?tex=Z_n" alt="Z_n" class="ee_img tr_noresize" eeimg="1"> ；
无限群如平面上的旋转群 <img src="https://www.zhihu.com/equation?tex=SO(2)" alt="SO(2)" class="ee_img tr_noresize" eeimg="1"> ，Lorentz变换群等。

紧接着介绍了群论中经典的Lagrange定理：有限群子群的阶是母群阶的因子。一个简单的推论是 <img src="https://www.zhihu.com/equation?tex=Z_p" alt="Z_p" class="ee_img tr_noresize" eeimg="1"> （ <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> 为素数）没有平凡子群。
同时还介绍了群的直积： <img src="https://www.zhihu.com/equation?tex=F \times G := \{(f,g):f \in F,g \in G\}" alt="F \times G := \{(f,g):f \in F,g \in G\}" class="ee_img tr_noresize" eeimg="1"> ，并举例 <img src="https://www.zhihu.com/equation?tex=Z_2 \times Z_2=V" alt="Z_2 \times Z_2=V" class="ee_img tr_noresize" eeimg="1"> ，其中 <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1"> 为Klein’s Vierergruppe（即德语的“4-group”），
值得注意的是该群与4阶循环群 <img src="https://www.zhihu.com/equation?tex=Z_4" alt="Z_4" class="ee_img tr_noresize" eeimg="1"> 为所有可能的4阶群。
为了说明这一结论，作者引入了群的乘法表的概念，并通过枚举4阶群的乘法表来证明该结论。
对于其他阶数的群，可以同样通过枚举乘法表的可能情况来对群进行分类，但是随着阶数 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 的增大，乘法表的大小 <img src="https://www.zhihu.com/equation?tex=n ^2" alt="n ^2" class="ee_img tr_noresize" eeimg="1"> 导致枚举变的十分困难。
对于 <img src="https://www.zhihu.com/equation?tex=n=4" alt="n=4" class="ee_img tr_noresize" eeimg="1"> 的特例，一个比较快的方法是讨论是否存在阶数为4的群元素：
- 若有，则为循环群 <img src="https://www.zhihu.com/equation?tex=Z_4" alt="Z_4" class="ee_img tr_noresize" eeimg="1"> 。
- 否则根据Lagrange定理，非单位元的群元素的阶均为2，即为群 <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1"> 。

最后介绍了群同态与群同构，同态为保持群乘法结构的映射，即满足 <img src="https://www.zhihu.com/equation?tex=f(g_1)f(g_2)=f(g_1g_2)" alt="f(g_1)f(g_2)=f(g_1g_2)" class="ee_img tr_noresize" eeimg="1"> 的映射 <img src="https://www.zhihu.com/equation?tex=f:G\to G'" alt="f:G\to G'" class="ee_img tr_noresize" eeimg="1"> 。
特别的，如果 <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> 为双射，则称为同构，因为此时两个群具有完全相同的结构（用符号 <img src="https://www.zhihu.com/equation?tex=\cong" alt="\cong" class="ee_img tr_noresize" eeimg="1"> 表示）。
例如对于循环群 <img src="https://www.zhihu.com/equation?tex=Z_n" alt="Z_n" class="ee_img tr_noresize" eeimg="1"> ，如果 <img src="https://www.zhihu.com/equation?tex=n=pq" alt="n=pq" class="ee_img tr_noresize" eeimg="1"> 且 <img src="https://www.zhihu.com/equation?tex=p,q" alt="p,q" class="ee_img tr_noresize" eeimg="1"> 互素，则可以证明 <img src="https://www.zhihu.com/equation?tex=Z_n \cong Z_p \times Z_q" alt="Z_n \cong Z_p \times Z_q" class="ee_img tr_noresize" eeimg="1"> （考虑阶为 <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> 的元素）。

**附录**

- 群公理的弱化：左右单位元与逆元可弱化为
    1. 存在左单位元 <img src="https://www.zhihu.com/equation?tex=e" alt="e" class="ee_img tr_noresize" eeimg="1"> ： <img src="https://www.zhihu.com/equation?tex=e g=g, \forall g" alt="e g=g, \forall g" class="ee_img tr_noresize" eeimg="1"> 。
    2. 存在左逆元： <img src="https://www.zhihu.com/equation?tex=\forall g, \exists f,fg=e" alt="\forall g, \exists f,fg=e" class="ee_img tr_noresize" eeimg="1"> 。

**Proof.**
 <img src="https://www.zhihu.com/equation?tex=\forall g" alt="\forall g" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=\exists f,fg=e" alt="\exists f,fg=e" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=\exists k" alt="\exists k" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=kf=e" alt="kf=e" class="ee_img tr_noresize" eeimg="1"> 。则

<img src="https://www.zhihu.com/equation?tex=g=eg=kfg=ke \implies ge=kee=ke=g
" alt="g=eg=kfg=ke \implies ge=kee=ke=g
" class="ee_img tr_noresize" eeimg="1">
则 <img src="https://www.zhihu.com/equation?tex=e" alt="e" class="ee_img tr_noresize" eeimg="1"> 同时也是右单位元，因此 <img src="https://www.zhihu.com/equation?tex=g=ke=k" alt="g=ke=k" class="ee_img tr_noresize" eeimg="1"> ，因此左逆也是右逆。 <img src="https://www.zhihu.com/equation?tex=\square" alt="\square" class="ee_img tr_noresize" eeimg="1"> 

- 结合律
如果把群乘法看成对群的作用，或者更一般的对某个集合 <img src="https://www.zhihu.com/equation?tex=P=\{p_i\}" alt="P=\{p_i\}" class="ee_img tr_noresize" eeimg="1"> 的作用，那么我们可以“证明”结合律：
若群元素 <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> 的作用为 <img src="https://www.zhihu.com/equation?tex=p_i \mapsto p_i'" alt="p_i \mapsto p_i'" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=g'" alt="g'" class="ee_img tr_noresize" eeimg="1"> 的作用为 <img src="https://www.zhihu.com/equation?tex=p_i' \to p_i''" alt="p_i' \to p_i''" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=g''" alt="g''" class="ee_img tr_noresize" eeimg="1"> 的作用为 <img src="https://www.zhihu.com/equation?tex=p_i''\to p_i'''" alt="p_i''\to p_i'''" class="ee_img tr_noresize" eeimg="1"> ，
那么考虑作用 <img src="https://www.zhihu.com/equation?tex=g''(g'g)" alt="g''(g'g)" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=(g'g)" alt="(g'g)" class="ee_img tr_noresize" eeimg="1"> 将 <img src="https://www.zhihu.com/equation?tex=p_i \mapsto p_i''" alt="p_i \mapsto p_i''" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=g''" alt="g''" class="ee_img tr_noresize" eeimg="1"> 再将其映射到 <img src="https://www.zhihu.com/equation?tex=p_i'''" alt="p_i'''" class="ee_img tr_noresize" eeimg="1"> ，显然这与 <img src="https://www.zhihu.com/equation?tex=(g''g')g" alt="(g''g')g" class="ee_img tr_noresize" eeimg="1"> 的作用相同，因此结合律成立。

- 模群（Modular group）
其定义为复函数 <img src="https://www.zhihu.com/equation?tex=z \mapsto (az+b) / (cz+d)" alt="z \mapsto (az+b) / (cz+d)" class="ee_img tr_noresize" eeimg="1"> ，其中 <img src="https://www.zhihu.com/equation?tex=a,b,c,d \in \mathbb{Z}" alt="a,b,c,d \in \mathbb{Z}" class="ee_img tr_noresize" eeimg="1"> 满足 <img src="https://www.zhihu.com/equation?tex=ad-bc=1" alt="ad-bc=1" class="ee_img tr_noresize" eeimg="1"> 。
该变换可以由矩阵

<img src="https://www.zhihu.com/equation?tex=M=\begin{bmatrix}
  a&b\\c&d
\end{bmatrix},\quad \det M=1
" alt="M=\begin{bmatrix}
  a&b\\c&d
\end{bmatrix},\quad \det M=1
" class="ee_img tr_noresize" eeimg="1">
描述。但注意到 <img src="https://www.zhihu.com/equation?tex=M" alt="M" class="ee_img tr_noresize" eeimg="1"> 与 <img src="https://www.zhihu.com/equation?tex=-M" alt="-M" class="ee_img tr_noresize" eeimg="1"> 实际上代表着相同的变换，因此该群并非同构于 <img src="https://www.zhihu.com/equation?tex=SL(2,\mathbb{Z})" alt="SL(2,\mathbb{Z})" class="ee_img tr_noresize" eeimg="1"> ，而是 <img src="https://www.zhihu.com/equation?tex=SL(2,\mathbb{Z}) /\{\pm I\}" alt="SL(2,\mathbb{Z}) /\{\pm I\}" class="ee_img tr_noresize" eeimg="1"> ，后者记作 <img src="https://www.zhihu.com/equation?tex=PSL(2,\mathbb{Z})" alt="PSL(2,\mathbb{Z})" class="ee_img tr_noresize" eeimg="1"> ，其中 <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> 代表projective，类似的还有 <img src="https://www.zhihu.com/equation?tex=PGL(n,F)" alt="PGL(n,F)" class="ee_img tr_noresize" eeimg="1"> ， <img src="https://www.zhihu.com/equation?tex=PSO(n)" alt="PSO(n)" class="ee_img tr_noresize" eeimg="1"> 等。
注意到该群可以由 <img src="https://www.zhihu.com/equation?tex=S:z \mapsto -1 /z" alt="S:z \mapsto -1 /z" class="ee_img tr_noresize" eeimg="1"> 与 <img src="https://www.zhihu.com/equation?tex=T:z \mapsto z+1" alt="T:z \mapsto z+1" class="ee_img tr_noresize" eeimg="1"> 生成：

<img src="https://www.zhihu.com/equation?tex=PSL(2,\mathbb{Z})=\langle S,T:S ^2=I,(ST)^3=I \rangle.
" alt="PSL(2,\mathbb{Z})=\langle S,T:S ^2=I,(ST)^3=I \rangle.
" class="ee_img tr_noresize" eeimg="1">

**习题**

2. 一个简单的恒等式：对于任意定义在有限群 <img src="https://www.zhihu.com/equation?tex=G" alt="G" class="ee_img tr_noresize" eeimg="1"> 上的函数 <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> ，有

<img src="https://www.zhihu.com/equation?tex=\sum_{g \in G} f(g)=\sum_{g \in G} f(gg')=\sum_{g \in G} f(g'g), \quad \forall g' \in G.
" alt="\sum_{g \in G} f(g)=\sum_{g \in G} f(gg')=\sum_{g \in G} f(g'g), \quad \forall g' \in G.
" class="ee_img tr_noresize" eeimg="1">


