#
>Análise de Sistemas de Energia Elétrica
>
>José Lucas Damasceno Holanda
#

<h1>Lista de Exercícios Nº 1</h1>


![Questão 01](Fig01.PNG "Questão 01")

Segue, a seguir, a solução da primeira questão:

<h3>1.A)</h3>

Nesta questão, deve-se encontrar o valor de $\hat{I}$, assumindo que possui mesma direção e sentido aprensentado na Figura acima. Desta forma, calcula-se $\hat{I}$ pelo método das malhas:


$
\begin{aligned}
-\hat{E_1} +\hat{I}Z +\hat{E_2}  &= 0 \\
\hat{I} &= \frac{\hat{E_1}-\hat{E_2}}{Z} \\
\hat{I} &= \frac{100\angle 0\degree - 100\angle 30\degree}{5j} \\
\hat{I} &= 10,35 \angle-165\degree  A\\
\end{aligned}
$


Tendo o fasor de corrente, é possível calcular as potências aparentes de $\hat{E_1}$ e $\hat{E_2}$ para determinar, assumindo o sentido da corrente, qual das duas fontes é a geradora e a consumidora.


$
\begin{aligned}
S_1 &= -\hat{E_1}*\hat{I}^* \\
S_1 &= 999,99 - j267,95 \\
S_1 &= 1035,27\angle-15\degree  VA \\
\end{aligned}
$

Com isso, sendo o sentido da corrente saindo da fonte $\hat{E_1}$ e a potência ativa com sinal positivo, esta fonte de tensão está fornecendo tensão para o sistema que contém uma impedância em série com a fonte de tensão $\hat{E_2}$.

<h3>1.B)</h3>

Para determinar as potências P e Q absorvidas pela impedância utilizam-se as tensões das fontes e a corrente obtida no item 1.a)

$
\begin{aligned}
S_Z &= (\hat{E_1}-\hat{E_2})\hat{I}^* \\
S_Z &= 0 + j535,6 \\
S_Z &= P_Z + jQ_Z \\
P_Z &= 0 W \\
Q_Z &= 535,89 var\\
\end{aligned}
$

<h3>1.C)</h3>