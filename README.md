
# Escala de Serviço Automática

# Motivação

Diante da necessidade do Sgtte de uma OM preparar uma escala de serviço toda semana, surge a ideia de se desenvolver uma ferramenta que produza essa escala de forma automática, respeitando os padrões de confecção da mesma.

# Conceito
A escala de serviço é uma tabela semanal que atribui a cada dia da semana uma lista de pessoas que estarão executando funções de serviço, chamada de _guarnição de serviço_.

Todas as pessoas aptas a realizar determinada função entrarão na escala de serviço seguindo uma ordem, _geralmente alfabética_, de forma que todos executem uma vez sua função até que a ordem se repita.

As ordens definidas para os dias de semana e os dias de final de semana e feriado são diferentes, geralmente chamadas _escala preta_ e _escala vermelha_.

O _descanso mínimo_ garante que um militar deve ter ao menos 2 dias de descanso entre um serviço e outro.

_Trocas de serviço_ consistem em trocar duas pessoas dentro da ordem da escala, _preta ou vermelha_, sem alterar a ordem dos demais.
# Função
O projeto consiste em um programa Windows que lê os dados de um arquivo .txt com os nomes dos alunos e gera um documento em latex da escala de serviço.

O programa deve ser capaz de trabalhar com escalas _vermelha_ e _preta_, garantir o _descanso mínimo_ dos militares e também realizar _trocas de serviço_.
## Autores

- [@Nazário](https://github.com/FranciscoN17)
- [@Chalegre](https://github.com/chalegreiron)