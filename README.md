As informações apresentadas neste repositório são de responsabilidade de seus autores. Esta iniciativa é uma produção independente que visa apresentar de diferentes formas as informações repassadas pelas prefeituras municipais acerca da evolução da COVID-19. Junte-se à nós e colabore!

### Instrução para construção do CSV:   

| data | confirmados | recuperados | mortes | restricao |
| --- | --- | --- | --- | --- |

#### Tipos de restrições:
- 0 => Comércio aberto
- 1 => Comércio fechado (exceto serviços essenciais)
- 2 a 23 => Horário do toque de recolher
- 24 => Saída do toque de recolher
- -1 => Entrada no lockdown
- -0 => Saída do lockdown

Fonte da linha de expectativa: https://github.com/cidacslab/Mathematical-and-Statistical-Modeling-of-COVID19-in-Brazil
- O repositório utiliza Aprendizagem de Máquina que leva em consideração a quantidade de casos confirmados. O modelo utilizado é o **Susceptible-Infected-Recovered (SIR)**.


## Lista de Cidades
- Ilhéus (Responsável: Allan Alves - IFBA):
  - Colab: https://github.com/covidba/covid/blob/master/covid19_ilheus.ipynb
- Itabuna (Responsável: Allan Alves - IFBA):
  - Colab: https://github.com/covidba/covid/blob/master/covid19_itabuna.ipynb
- Jequié (Responsável: Ramon Fontes - IFBA): 
  - Colab: https://github.com/covidba/covid/blob/master/covid19_jequie.ipynb
- Vitória da Conquista (Responsável: Ramon Fontes - IFBA): 
  - Colab: https://github.com/covidba/covid/blob/master/covid19_vitoria_da_conquista.ipynb
