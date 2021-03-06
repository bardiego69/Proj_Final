# Utilização de Metodologia Multicritérios

#### Aluno: [Diego Alexandre Belmonte Barbosa](https://github.com/link_do_github)
#### Orientador(/a/es/as): [Cristian Muños](https://github.com/link_do_github)

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".


---


### Resumo

**1. Objetivo**

Utilizar metodologia multicritérios para a decisão de qual topologia de painel é a ideal para 10 cargas.
A partir do uso da metodologia AHP/FUZZY é realizado o ranqueanto dos critérios.
Em seguida, considerando a metodologia TOPSIS, é realizado o ranqueamento das alternativas.

**Divisão do trabalho:**

**1.1. Utilização do AHP/FUZZY - rank de critérios com Python**
- Aplicação de 04 macro-critérios
- Aplicação de critérios com 01 nível de alternativas de 5,3,2 e 2

**1.2. Utilização do TOPSIS - rank de alternativas com Python**
- Aplicação para de uma matriz de 12x12

**2.Dados:** 
- [DATA_CABLE.xlsx] - Contem os parametros elétricos dos cabos
- [dados.xlsx] - Contem o número de equipamentos envolvidos
- [dist.xlsx] - Contem as localizações das cargas e paineis
- [conf.xlsx] - Contem a confiabilidade de cada equipamento

**3.[Escopo]**

Calculo do fluxo de potência para cada circuito considerando as seguintes alternativas:
- Alternativa 1  -> 1 painel com 10 alimentadores
- Alternativa 2  -> 2 paineis com 8 e 2 alimentadores
- Alternativa 3  -> 2 paineis com 7 e 3 alimentadores
- Alternativa 4  -> 2 paineis com 6 e 4 alimentadores
- Alternativa 5  -> 2 paineis com 5 e 5 alimentadores
- Alternativa 6  -> 3 paineis com 6, 2 e 2 alimentadores
- Alternativa 7  -> 3 paineis com 5, 3 e 2 alimentadores
- Alternativa 8  -> 3 paineis com 4, 4 e 2 alimentadores
- Alternativa 9  -> 3 paineis com 4, 3 e 3 alimentadores
- Alternativa 10 -> 4 paineis com 2, 2, 2 e 4 alimentadores
- Alternativa 11 -> 4 paineis com 2, 2, 3 e 3 alimentadores
- Alternativa 12 -> 5 paineis com 2, 2, 2, 2 e 2 alimentadores

Otimização da localização considerando Algoritmos Genéticos (Solver - Excel), consdierando:
- menor custo de aquisição;
- Corrente de cargas com 20% de margem de segurança;
- Queda de tensão de 10% em cada trecho;
- Eficiência elétrica de 7%;
- Temperatura ambiente de 45°C.

Criação da tabela com todas as alternativas;
- Somatória dos custos de instalação dos cabos e custos de equipamentos adicionais;
- Calculo de confiabilidade de cada carga/ alternativa;
- Calculo de probalidade de perda das 10 cargas para cada alternativa;


#  Plataformas utilizadas
- Google [[Google Colab](https://colab.research.google.com/)]

---

Matrícula: 192.190.054

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*

