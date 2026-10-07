# Controle de Investimentos - Excel (Cabral Invest)

Este projeto foi desenvolvido durante o Bootcamp Santander — Excel com IA e Claude, com o objetivo de aplicar conhecimentos de Excel na criação de um simulador de investimentos interativo.

A solução permite que o usuário informe dados financeiros básicos, simule a evolução de seus investimentos ao longo do tempo e visualize sugestões de distribuição de aportes de acordo com diferentes perfis de investidor.

O projeto foi desenvolvido com foco em automação de cálculos, aplicação de funções financeiras, busca de dados e visualização de informações, utilizando recursos nativos do Excel.

## Perguntas de negócio
O projeto foi estruturado para responder principalmente:
"Considerando um aporte mensal, uma taxa de rendimento e determinado período de investimento, qual patrimônio poderá ser acumulado e qual seria o valor mensal de dividendos?"
Além disso, a ferramenta permite explorar diferentes cenários de investimento e diferentes distribuições de carteira.

## Principais recursos do Excel utilizados
Durante o desenvolvimento foram utilizados diferentes recursos e funções do Excel:
•	VF - cálculo de valor futuro;
•	PROCV - busca de percentuais na tabela de referência;
•	SOMA - consolidação dos valores;
•	Operações matemáticas para cálculo dos aportes;
•	Células nomeadas para facilitar a utilização das fórmulas;
•	Validação de dados para seleção do perfil;
•	Tabelas de referência;
•	Chave composta para buscas;
•	Gráficos de pizza dinâmicos;
•	Formatação e organização de uma interface de simulação.

## Estrutura da aplicação
A planilha possui duas abas principais:
1. Controle_de_investimentos
É a interface principal da aplicação, onde estão concentradas as entradas do usuário, os cálculos, as simulações e os gráficos.
2. Referências
Contém as tabelas de apoio utilizadas para armazenar os percentuais de distribuição para cada perfil de investidor.
Essa estrutura permite separar os dados utilizados nos cálculos da interface principal da aplicação.

## Estrutura da planilha
Controle_de_investimentos
* Configurações
* Simulação de FIIs
* Cenários de investimento
* Distribuição geral por perfil
* Distribuição de FIIs por perfil
* Gráficos dinâmicos

## Imagens:
<img src="images\imagem1.png">

Para o cálculo do patrimônio futuro foi utilizada a função financeira:

=VF(taxa_mensal; prazo_em_meses; aporte_mensal)

A função VF permite calcular o valor futuro de uma série de aportes considerando uma taxa de rendimento periódica.

<img src="images\imagem2.png">

A aplicação possui uma área destinada à distribuição de um aporte mensal de acordo com quatro perfis:

Conservador
Moderado
Arrojado
Agressivo

O usuário informa o valor que pretende investir mensalmente e seleciona seu perfil.

A planilha retorna automaticamente:

Percentual sugerido para cada tipo de investimento;
Valor correspondente do aporte mensal.

<img scr="images\imagem3.png">

A aplicação também apresenta uma distribuição específica para Fundos Imobiliários.

A partir do perfil selecionado, o sistema consulta automaticamente a distribuição correspondente e calcula o valor de aporte para cada categoria.

## Principais aprendizados
O desenvolvimento deste projeto permitiu praticar conceitos importantes de Excel aplicados a um problema de negócio:
- Estruturação de uma ferramenta interativa;
- Transformação de requisitos de negócio em cálculos;
- Utilização de funções financeiras;
- Criação de cenários;
- Construção de tabelas de referência;
- Utilização de chaves compostas para buscas;
- Automatização de cálculos com base em entradas do usuário;
- Criação de gráficos vinculados aos resultados;
- Organização de uma planilha para facilitar a experiência do usuário.

## Observação
Este projeto foi desenvolvido exclusivamente para fins de estudo e demonstração de conhecimentos em Excel.
Os percentuais de distribuição, taxas de rendimento e demais parâmetros utilizados na ferramenta são hipotéticos e não devem ser interpretados como recomendação de investimento.

<a href="https://www.linkedin.com/in/thais-cabral-489182198/">Meu Linkedin</a>
