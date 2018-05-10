# Estatistica1 
##### 2018-1 - professor José Caleffi

### Tabelas de contingência 


|       | Vegano | Vegetariano | Carnivoro | TOTAL |
|-------|--------|-------------|-----------|-------|
|       | 400    | 500         | 7100      | 8000  |
|       | 350    | 700         | 5950      | 7000  |
| TOTAL | 750    | 1200        | 13050     | 15000 |


# Distribuição Discreta de Probabilidade BINOMIAL 

- Experimentos repetitivos e independentes
- Em um experimento só há dois resultados: Sucesso (**P**) ou não sucesso (**Q**)

### Ex: Um time joga 4 partidas, qual a probabilidade de perder todas?

Probabilidade de perder (1 em 3 casos):  
![1/3](https://latex.codecogs.com/gif.latex?P%20%3D%20%5Cfrac%7B1%7D%7B3%7D)  
Probabilidade de não-perder (2 em 3 casos):  
![2/3](https://latex.codecogs.com/gif.latex?Q%20%3D%20%5Cfrac%7B2%7D%7B3%7D)

<a href="https://www.codecogs.com/eqnedit.php?latex=P&space;=&space;\frac{1}{3}&space;\cdot&space;\frac{1}{3}&space;\cdot&space;=&space;(\frac{1}{3})^{4}&space;=&space;0.01234&space;=&space;1.2345&space;\%" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P&space;=&space;\frac{1}{3}&space;\cdot&space;\frac{1}{3}&space;\cdot&space;=&space;(\frac{1}{3})^{4}&space;=&space;0.01234&space;=&space;1.2345&space;\%" title="P = \frac{1}{3} \cdot \frac{1}{3} \cdot = (\frac{1}{3})^{4} = 0.01234 = 1.2345 \%" /></a>

### Ex: Em uma prova com 50 questões, com 5 alternativas em cada questão, e apenas 1 correta:
#### Qual a chance de acertar todas as perguntas?

<a href="https://www.codecogs.com/eqnedit.php?latex=P&space;=&space;(\frac{1}{5})^{50}&space;=&space;1.125899906842624e-35" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P&space;=&space;(\frac{1}{5})^{50}&space;=&space;1.125899906842624e-35" title="P = (\frac{1}{5})^{50} = 1.125899906842624e-35" /></a>

#### Qual a chance de errar todas?
<a href="https://www.codecogs.com/eqnedit.php?latex=P&space;=&space;(\frac{4}{5})^{50}&space;=&space;0.000014272476927" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P&space;=&space;(\frac{4}{5})^{50}&space;=&space;0.000014272476927" title="P = (\frac{4}{5})^{50} = 0.000014272476927" /></a>

#### Joga-se um dado 5 vezes, determinar a probabilidade de ocorrer face 3, 4 vezes.
|   |   |   |   |   |
|---|---|---|---|---|
| 3 | 3 | 3 | 3 | X |
| 3 | 3 | 3 | X | 3 |
| 3 | 3 | X | 3 | 3 |
| 3 | X | 3 | 3 | 3 |
| X | 3 | 3 | 3 | 87 |

P = (1/6) ; Q = (5/6)  
P(x=4) = COMBIN(5,4) * (1/6) ^4 * (5/6) ^(5-4)  
P(x=4) = 0.003215020576  

## Formula 
<a href="https://www.codecogs.com/eqnedit.php?latex=C_{N_{1}}_{R}&space;=&space;C&space;_{N}^{R}&space;=&space;\binom{N}{R}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?C_{N_{1}}_{R}&space;=&space;C&space;_{N}^{R}&space;=&space;\binom{N}{R}" title="C_{N_{1}}_{R} = C _{N}^{R} = \binom{N}{R}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=P(X=R)&space;=&space;C_{R}^{N}&space;\cdot&space;P^{R}&space;\cdot&space;Q^{N-R}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?P(X=R)&space;=&space;C_{R}^{N}&space;\cdot&space;P^{R}&space;\cdot&space;Q^{N-R}" title="P(X=R) = C_{R}^{N} \cdot P^{R} \cdot Q^{N-R}" /></a>

### O percentual de inadimpletes é de 5% dente 10 clientes, determinar a probabilidade de que:
#### 5 sejam inadimplentes
P = 0,05 ; Q = 0,95 ; n = 10 ; P(x=5) = COMBIN(10,5) * (0.05) ^5 * (0.095) ^(10-5)  
P(X=5) = 0.0000000006093524883  


[ref1](https://github.com/STAT545-UBC/Discussion/issues/102)
[ref2](https://github.com/github/markup/issues/897)
