1-1 Comparison of running times
For each function f .n/ and time t in the following table, determine the largest size n of a problem that can be solved in time t, assuming that the algorithm to solve the problem takes f .n/ microseconds.


- $ f(x) = \log_{2} $
igualamos a função ao tempo total $t$ convertido em microsegundos
$\log_{2} n = t$

$2^\log_{2} n = 2^t$

$n = 2^t$

substituir o $t$ pelo tempo em microsegundos.


f(n)=n o calculo do maior tamanho de n em um determinado tempo t é direto n=t

---

## Conversão de $t$ para microssegundos

(mês = 30 dias, ano = 365 dias)

| tempo | $t$ (µs) |
| --- | --- |
| 1 segundo | $10^6$ |
| 1 minuto | $6\times10^7$ |
| 1 hora | $3{,}6\times10^9$ |
| 1 dia | $8{,}64\times10^{10}$ |
| 1 mês | $2{,}592\times10^{12}$ |
| 1 ano | $3{,}1536\times10^{13}$ |
| 1 século | $3{,}1536\times10^{15}$ |

## Tabela

| $f(n)$ | 1 segundo | 1 minuto | 1 hora | 1 dia | 1 mês | 1 ano | 1 século |
| --- | --- | --- | --- | --- | --- | --- | --- |
| $\lg n$ | $2^{10^6}$ | $2^{6\times10^7}$ | $2^{3{,}6\times10^9}$ | $2^{8{,}64\times10^{10}}$ | $2^{2{,}592\times10^{12}}$ | $2^{3{,}1536\times10^{13}}$ | $2^{3{,}1536\times10^{15}}$ |
| $\sqrt{n}$ |  |  |  |  |  |  |  |
| $n$ | $10^6$ | $6\times10^7$ | $3{,}6\times10^9$ | $8{,}64\times10^{10}$ | $2{,}592\times10^{12}$ | $3{,}1536\times10^{13}$ | $3{,}1536\times10^{15}$ |
| $n\lg n$ |  |  |  |  |  |  |  |
| $n^2$ |  |  |  |  |  |  |  |
| $n^3$ |  |  |  |  |  |  |  |
| $2^n$ |  |  |  |  |  |  |  |
| $n!$ |  |  |  |  |  |  |  |
