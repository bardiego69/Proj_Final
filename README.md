# Proj_Final
Tomada de Decisão - Melhor opção n° circuitos para painel de 10 cargas, utilizando AG, AHP-FUZZY e TOPSIS
Considerando um cenário em que há 10 cargas submarinas (motores submarinas) com localização pré-definidas, qual seria a melhor posição de um painel de distribuição de circuitos? Qual o número ideal de circuitos por painel? Como avaliar da melhor forma esta decisão.
Assim, neste trabalho seguiu-se os seguintes passos:
Calculo do fluxo de potência para cada circuito considerando as seguintes alternativas:
Alternativa 1  -> 1 painel com 10 alimentadores
Alternativa 2  -> 2 paineis com 8 e 2 alimentadores
Alternativa 3  -> 2 paineis com 7 e 3 alimentadores
Alternativa 4  -> 2 paineis com 6 e 4 alimentadores
Alternativa 5  -> 2 paineis com 5 e 5 alimentadores
Alternativa 6  -> 3 paineis com 6, 2 e 2 alimentadores
Alternativa 7  -> 3 paineis com 5, 3 e 2 alimentadores
Alternativa 8  -> 3 paineis com 4, 4 e 2 alimentadores
Alternativa 9  -> 3 paineis com 4, 3 e 3 alimentadores
Alternativa 10 -> 4 paineis com 2, 2, 2 e 4 alimentadores
Alternativa 11 -> 4 paineis com 2, 2, 3 e 3 alimentadores
Alternativa 12 -> 5 paineis com 2, 2, 2, 2 e 2 alimentadores
Otimização da localização considerando Algoritmos Genéticos (Solver - Excel), consdierando:
- menor custo de aquisição;
- Corrente de cargas com 20% de margem de segurança;
- Queda de tensão de 10% em cada trecho;
- Eficiência elétrica de 7%;
- Temperatura ambiente de 45°C.
Criação da tabela com todas as alternativas;
Somatória dos custos de instalação dos cabos e custos de equipamentos adicionais;
Calculo de confiabilidade de cada carga/ alternativa;
Calculo de probalidade de perda das 10 cargas para cada alternativa;
Utilização da metodologia AHP-FUZZY para rank de critérios;
Utilização de metodologia TOPSIS para tomada de decisão.
