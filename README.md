地表面が自由境界の一様な半無限地盤にSV波の定常波が入射した際の変位と応力を計算します。式展開は以下の論文を参考にします。
[地震動のSV波動特性の研究](https://www.jstage.jst.go.jp/article/jscej1969/1979/289/1979_289_1/_pdf)(1979 金子)
SV波が入射した際にはSV波とP波が反射されることが知られています。P波の変位ポテンシャル $\phi$ とS波の変位ポテンシャル $\psi$ を用いると変位は次式のように表されます。

$$
\begin{align}
u&=\dfrac{\partial\phi}{\partial x}+\dfrac{\partial\psi}{\partial z}\\
w&=\dfrac{\partial\phi}{\partial z}-\dfrac{\partial\psi}{\partial x}\\
\end{align}
$$

