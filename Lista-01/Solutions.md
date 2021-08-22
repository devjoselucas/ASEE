
----
###### Análise de Sistemas de Energia Elétrica
###### Desenvolvido por José Lucas Damasceno Holanda  
----
<h1>Lista de Exercícios Nº 1</h1>



![Questão 01](Fig01.PNG "Questão 01")

----

Segue, a seguir, a solução da primeira questão: 


<h3>1.A)</h3>

Nesta questão, deve-se encontrar o valor de <img src="https://latex.codecogs.com/svg.latex?\hat{I}" title="\hat{I}" />, assumindo que possui mesma direção e sentido aprensentado na Figura acima. Desta forma, calcula-se <img src="https://latex.codecogs.com/svg.latex?\hat{I}" title="\hat{I}" /> pelo método das malhas: 

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;-\hat{E_1}&space;&plus;\hat{I}Z&space;&plus;\hat{E_2}&space;&&space;=&space;0&space;\\&space;\hat&space;{I}&space;&&space;=&space;\frac{\hat{E_1}-\hat{E_2}}{Z}&space;\\&space;\hat&space;{I}&space;&&space;=&space;\frac{100\angle&space;0\degree&space;-&space;100\angle&space;30\degree}{5j}&space;\\&space;\hat&space;{I}&space;&&space;=&space;10,&space;35&space;\angle-165\degree&space;A\\&space;\end{aligned}" title="\begin{aligned} -\hat{E_1} +\hat{I}Z +\hat{E_2} & = 0 \\ \hat {I} & = \frac{\hat{E_1}-\hat{E_2}}{Z} \\ \hat {I} & = \frac{100\angle 0\degree - 100\angle 30\degree}{5j} \\ \hat {I} & = 10, 35 \angle-165\degree A\\ \end{aligned}" />
</p>


Tendo o fasor de corrente, é possível calcular as potências aparentes de <img src="https://latex.codecogs.com/svg.latex?\hat{E_1}" title="\hat{E_1}" /> e <img src="https://latex.codecogs.com/svg.latex?\hat{E_2}" title="\hat{E_2}" /> para determinar, assumindo o sentido da corrente, qual das duas fontes é a geradora e a consumidora.

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;S_1&space;&&space;=&space;-\hat{E_1}*\hat{I}^*&space;\\&space;S_1&space;&&space;=&space;999,&space;99&space;-&space;j267,&space;95&space;\\&space;S_1&space;&&space;=&space;1035,&space;27\angle-15\degree&space;&&space;VA&space;\\&space;\end{aligned}" title="\begin{aligned} S_1 & = -\hat{E_1}*\hat{I}^* \\ S_1 & = 999, 99 - j267, 95 \\ S_1 & = 1035, 27\angle-15\degree & VA \\ \end{aligned}" />
</p>


Com isso, sendo o sentido da corrente saindo da fonte <img src="https://latex.codecogs.com/svg.latex?\hat{E_1}" title="\hat{E_1}" /> e a potência ativa com sinal positivo, esta fonte de tensão está fornecendo tensão para o sistema que contém uma impedância em série com a fonte de tensão <img src="https://latex.codecogs.com/svg.latex?\hat{E_2}" title="\hat{E_2}" />.

----
<h3>1.B)</h3>

Para determinar as potências P e Q absorvidas pela impedância utilizam-se as tensões das fontes e a corrente obtida no item 1.a)


<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;S_Z&space;&&space;=&space;(\hat{E_1}-\hat{E_2})\hat{I}^*&space;\\&space;S_Z&space;&&space;=&space;0&space;&plus;&space;j535,&space;6&space;\\&space;S_Z&space;&&space;=&space;P_Z&space;&plus;&space;jQ_Z&space;\\&space;P_Z&space;&&space;=&space;0&space;&&&space;W&space;\\&space;Q_Z&space;&&space;=&space;535,89&space;&&&space;var\\&space;\end{aligned}" title="\begin{aligned} S_Z & = (\hat{E_1}-\hat{E_2})\hat{I}^* \\ S_Z & = 0 + j535, 6 \\ S_Z & = P_Z + jQ_Z \\ P_Z & = 0 && W \\ Q_Z & = 535,89 && var\\ \end{aligned}" />
</p>


----
<h3>1.C)</h3>

Considerando que a diferença angular entre as fontes <img src="https://latex.codecogs.com/svg.latex?\hat{E_1}" title="\hat{E_1}" /> e <img src="https://latex.codecogs.com/svg.latex?\hat{E_2}" title="\hat{E_2}" />é igual ou próxima de zero, pode-se utilizar a seguinte consideração para calcular a máxima potência transferível da Fonte 1 para a Fonte 2: 

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;P_{MAX}&space;&&space;=&space;\frac{E_1E_2}{X}&space;\\&space;&&space;=&space;\frac{100*100}{5}&space;\\&space;P_{MAX}&space;&&space;=&space;2000&space;W&space;\\&space;\end{aligned}" title="\begin{aligned} P_{MAX} & = \frac{E_1E_2}{X} \\ & = \frac{100*100}{5} \\ P_{MAX} & = 2000 W \\ \end{aligned}" />
</p>

----
<h3>1.D)</h3>

A potência demandada pela barra de carga é calculada pela equação abaixa: 

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;S_2&space;&&space;=&space;\hat{E_2}*\hat{I}^*&space;\\&space;&&space;=&space;-999,&space;99&space;-j267,&space;95&space;&&&space;VA&space;\\&space;\end{aligned}" title="\begin{aligned} S_2 & = \hat{E_2}*\hat{I}^* \\ & = -999, 99 -j267, 95 && VA \\ \end{aligned}" />
</p>

----
<h3>1.E)</h3>

Considerando a inserção de um capacitor de 2, 5 <img src="https://latex.codecogs.com/svg.latex?\Omega " title="\Omega "/> em série com a reatância indutiva da linha, obteve-se primeiro a corrente do novo sistema por meio de: 

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;-\hat{E_1}&space;&plus;\hat{I}(j5&space;-j2,5)&space;&plus;&space;\hat{E_2}&space;&&space;=&space;0&space;\\&space;\hat&space;{I}&space;&&space;=&space;\frac{\hat{E_1}-\hat{E_2}}{j2,5}&space;\\&space;&&space;=&space;-20&space;-j5,&space;3589&space;&&&space;A&space;\\&space;&&space;=&space;20,7055\angle-165\degree&space;&&&space;A&space;\\&space;\end{aligned}" title="\begin{aligned} -\hat{E_1} +\hat{I}(j5 -j2,5) + \hat{E_2} & = 0 \\ \hat {I} & = \frac{\hat{E_1}-\hat{E_2}}{j2,5} \\ & = -20 -j5, 3589 && A \\ & = 20,7055\angle-165\degree && A \\ \end{aligned}" />
</p>


Logo em seguida, calcula-se as componentes da potência aparente da nova impedância da linha: 

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;S_Z&space;&&space;=&space;(\hat{E_1}-\hat{E_2})\hat{I}^*&space;\\&space;&&space;=&space;1071,7955\angle&space;90\degree&space;&&&space;VA&space;\\&space;&&space;=&space;0&space;&plus;&space;j1071,&space;7955&space;&&&space;VA&space;\end{aligned}" title="\begin{aligned} S_Z & = (\hat{E_1}-\hat{E_2})\hat{I}^* \\ & = 1071,7955\angle 90\degree && VA \\ & = 0 + j1071, 7955 && VA \end{aligned}" />
</p>


Por conseguinte, considerando que a abertura angular entre as duas fontes de tensão é a menor possível, calcula-se a máxima transferências de potência por meio de: 

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;P_{MAX}&space;&&space;=&space;\frac{100*100}{2,5}&space;\\&space;&&space;=&space;4000&space;W&space;\\&space;\end{aligned}" title="\begin{aligned} P_{MAX} & = \frac{100*100}{2,5} \\ & = 4000 W \\ \end{aligned}" />
</p>


Por fim, Calcula-se a potência demandada na fonte de carga: 

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;S_2&space;&&space;=&space;(100\angle&space;30\degree)\hat{I}^*&space;\\&space;&&space;=&space;-1999,&space;99&space;-&space;j535,&space;89&space;&&&space;VA&space;\\&space;&&space;=&space;2070,&space;55\angle&space;-165\degree&space;&&&space;VA&space;\end{aligned}" title="\begin{aligned} S_2 & = (100\angle 30\degree)\hat{I}^* \\ & = -1999, 99 - j535, 89 && VA \\ & = 2070, 55\angle -165\degree && VA \end{aligned}" />
</p>

----

![Questão 02](Fig02.PNG "Questão 02")

----

Segue, a seguir, a solução da primeira questão: 



<h3>2.A)</h3>

Considerando a função <img src="https://latex.codecogs.com/svg.latex?\cos(\omega&space;t)" title="\cos(\omega t)" /> como referência, obteve-se os fasores de tensão e de corrente do motor:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{align*}&space;V_a(t)&space;&=&space;311,11\sin(\omega&space;t)&space;&&&space;V&space;\\&space;V_a(t)&space;&=&space;220\sin(\omega&space;t)&space;&&&space;V_{rms}\\&space;V_a(t)&space;&=&space;220\cos(\omega&space;t&space;-90\degree)&space;&&&space;V_{rms}\\&space;\end{align*}" title="\begin{align*} V_a(t) &= 311,11\sin(\omega t) && V \\ V_a(t) &= 220\sin(\omega t) && V_{rms}\\ V_a(t) &= 220\cos(\omega t -90\degree) && V_{rms}\\ \end{align*}" />
</p>


Com isso, admitindo a referência citada acima, obtém-se o valor referenciado para a corrente:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{align*}&space;I_a(t)&space;&=&space;141,42\cos(\omega&space;t&space;-30\degree)&space;&&A&space;\\&space;I_a(t)&space;&=&space;99,99\cos(\omega&space;t&space;-&space;30\degree)&space;&&&space;A_{rms}\\&space;I_a(t)&space;&=&space;99,99\cos(\omega&space;t&space;-120\degree)&space;&&&space;A_{rms}\\&space;\end{align*}" title="\begin{align*} I_a(t) &= 141,42\cos(\omega t -30\degree) &&A \\ I_a(t) &= 99,99\cos(\omega t - 30\degree) && A_{rms}\\ I_a(t) &= 99,99\cos(\omega t -120\degree) && A_{rms}\\ \end{align*}" />
</p>


----
<h3>2.B)</h3>

Para obter a impedância equivalente, considerando a carga em Y, têm-se:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{align*}&space;Z_Y&space;&=&space;\frac{\hat{V_a}}{\hat{I_a}}&space;&&\Omega&space;\\&space;Z_Y&space;&=&space;2,2\angle&space;30\degree&space;&&\Omega&space;\end{align*}" title="\begin{align*} Z_Y &= \frac{\hat{V_a}}{\hat{I_a}} &&\Omega \\ Z_Y &= 2,2\angle 30\degree &&\Omega \end{align*}" />
</p>


----
<h3>2.C)</h3>

Calculando e obtendo a impedância e a corrente em sistema por unidade:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{align*}&space;|Z_{base}|&=\frac{{|V_{base}|}^2}{|S_{base}|}&space;&&\Omega\\&space;&=&space;7,22&space;&&\Omega\\&space;Z_{Y_{pu}}&space;&=&space;\frac{Z_Y}{|Z_{base}|}&space;&&pu\\&space;Z_{Y_{pu}}&space;&=&space;\frac{2,2\angle&space;30\degree}{7,22}&space;&&pu&space;\\&space;Z_{Y_{pu}}&space;&=&space;0,30\angle&space;30\degree&space;&&pu&space;\end{align*}" title="\begin{align*} |Z_{base}|&=\frac{{|V_{base}|}^2}{|S_{base}|} &&\Omega\\ &= 7,22 &&\Omega\\ Z_{Y_{pu}} &= \frac{Z_Y}{|Z_{base}|} &&pu\\ Z_{Y_{pu}} &= \frac{2,2\angle 30\degree}{7,22} &&pu \\ Z_{Y_{pu}} &= 0,30\angle 30\degree &&pu \end{align*}" />
</p>


Calculando a corrente em pu:
<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;\hat{I_a}&space;&=&space;\frac{1\angle&space;-90\degree}{Z_{Y_{pu}}}&space;&&pu\\&space;\hat{I_a}&space;&=&space;3,2818\angle&space;-120\degree&space;&&pu\\&space;\end{aligned}" title="\begin{aligned} \hat{I_a} &= \frac{1\angle -90\degree}{Z_{Y_{pu}}} &&pu\\ \hat{I_a} &= 3,2818\angle -120\degree &&pu\\ \end{aligned}" />
</p>

----
<h3>2.D)</h3>

Calculando e obtendo a impedância e a corrente em sistema por unidade no novo sistema base:

<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{align*}&space;|Z_{base}|&=\frac{{|V_{base}|}^2}{|S_{base}|}&space;&&\Omega\\&space;&=&space;1,25&space;&&\Omega\\&space;Z_{Y_{pu}}&space;&=&space;\frac{Z_Y}{|Z_{base}|}&space;&&pu\\&space;Z_{Y_{pu}}&space;&=&space;\frac{2,2\angle&space;30\degree}{1,25}&space;&&pu&space;\\&space;Z_{Y_{pu}}&space;&=&space;1,76\angle&space;30\degree&space;&&pu&space;\end{align*}" title="\begin{align*} |Z_{base}|&=\frac{{|V_{base}|}^2}{|S_{base}|} &&\Omega\\ &= 1,25 &&\Omega\\ Z_{Y_{pu}} &= \frac{Z_Y}{|Z_{base}|} &&pu\\ Z_{Y_{pu}} &= \frac{2,2\angle 30\degree}{1,25} &&pu \\ Z_{Y_{pu}} &= 1,76\angle 30\degree &&pu \end{align*}" />
</p>


Calculando a tensão em pu:
<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;\hat{V_a}&space;&=&space;\frac{220\angle&space;-90\degree}{250/\sqrt{3}}&space;&&pu\\&space;\hat{V_a}&space;&=&space;1,5242\angle&space;-90\degree&space;&&pu\\&space;\end{aligned}" title="\begin{aligned} \hat{V_a} &= \frac{220\angle -90\degree}{250/\sqrt{3}} &&pu\\ \hat{V_a} &= 1,5242\angle -90\degree &&pu\\ \end{aligned}" />
</p>

Calculando a corrente em pu:
<p align="center">
    <img src="https://latex.codecogs.com/svg.latex?\begin{aligned}&space;\hat{I_a}&space;&=&space;\frac{1,5242\angle&space;-90\degree}{1,76\angle&space;30\degree}&space;&&pu\\&space;\hat{I_a}&space;&=&space;0,8660\angle&space;-120\degree&space;&&pu\\&space;\end{aligned}" title="\begin{aligned} \hat{I_a} &= \frac{1,5242\angle -90\degree}{1,76\angle 30\degree} &&pu\\ \hat{I_a} &= 0,8660\angle -120\degree &&pu\\ \end{aligned}" />
</p>

----

>Em caso de necessidade de correções, entrar em contato vai github ou via e-mail jose.holanda@ee.ufcg.edu.br
