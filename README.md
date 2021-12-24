# Pratica-integrada-CD-e-AM-2021.2

1. [About The Project](#about-the-project)
    * [Built With](#built-with)
1. [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
1. [Usage](#usage)
1. [Meetings](#Encontros)
3. [Roadmap](#to-do-geral)
4. [License](#license)
5. [Contact](#contac)
6. [Acknowledgements](#acknowledgements)

## Encontros síncronos

14:00 toda quarta

## To do geral

- [x] Encontrar um aluno de IAM
- [ ] Configurar os ambientes de desenvolvimento
   - [ ] Definir as linguagens de programação (python)
   - [ ] Definir qual banco de dados utilizar (postgreSQL)
- [ ] Definir estilo do código (padronização e legibilidade)
   - [ ] Como vamos armazenar o código: .py .ipynb
   - [ ] Linguagem do código e dos cometários: português ou inglês
   - [ ] Estilo do código, vamos adotar algum? (recomendação: https://google.github.io/styleguide/cppguide.html)
- [ ] Definir como vamos separar as terefas
   - [ ] Como ficará as divisões das branches (branch de entrega é sagrada)
   - [ ] Como vamos dividir tarefas dependentes (etapa 1 tem que estar concluída para fazer a etapa 2)
   - [ ] Prazos para cumprirmos (exemplo: 2 dias para cumprirmos depois da divisão de tarefas)
   - [ ] Definir um prazo para possíveis probelmas (temos sempre que terminar antes de prazo - 4 dias antes da entrega)
   - [ ] Quando pedir ajuda?
- [ ] Compartilhar horários de disponibilidade
   - [ ] Dias e horários que todos possam se encontrar de maneira síncrona
   - [ ] Duração do encontro
   - [ ] Vezes por semana
   - [ ] Escolher dias e horários para encontros síncronos
- [ ] Como vamos deixar os outros colegas saberem o que estamos fazendo?
   - [ ] Enviar pelo WhatsApp ou enviar sempre o código no GitHub na sua branch*

## Sprint 01

### 1.1 - Introdução e coleta de dados

- [ ] Colocar todos os dados em 1 único dataframe (https://drive.google.com/file/d/1xdHaCrNs9sLbO5otCcKoR2TsO2-Uhhnv/view?usp=sharing) - é dependência de outras tarefas

### 1.2 - Exploração

- [ ] Explorar os dados
- [ ] "Obter diversas métricas sobre as variáveis" (criar estruturas para mostrar essas métricas)
- [ ] "Quantas observações temos por gênero e por movimento"
- [ ] "Procurar alguma correlação entre as coordenadas"
- [ ] "Monte um histograma revelando a distribuição das medidas obtidas nas coordenadas X"
- [ ] "Gere um gráfico com ocorrências por tipo de movimento"

### 1.3 - Preparação

- [ ] "Eliminar observações do tipo MODEL" - é dependência de outras tarefas
- [ ] "Eliminar a variável contendo nome do arquivo" - é dependência de outras tarefas
- [ ] "Acrescentar nova variável representando a média das coordenadas (Ou seja, obter, para cada instante a média das três coordenadas (X,Y,Z), ao final você deverá ter um vetor de médias ao longo do tempo)" - é dependência de outras tarefas
- [ ] Veja o grau de correlação da nova variável que criamos em relação às demais coordenadas
