# FiscoApp — Organizador de Imposto de Renda no Excel

Aplicativo desenvolvido em **Microsoft Excel** durante o Bootcamp Santander – Excel com IA e Claude, com o objetivo de auxiliar na organização de informações utilizadas na preparação da declaração de Imposto de Renda.

O projeto combina organização de dados, fórmulas, validações, navegação entre abas e recursos visuais do Excel para criar uma experiência semelhante à de um aplicativo, permitindo que o usuário registre seus dados, organize seus rendimentos e consulte uma estimativa do imposto a pagar.

⚠️ *Aviso: este projeto possui finalidade exclusivamente educacional. A simulação apresentada não substitui a declaração oficial do Imposto de Renda nem representa um cálculo fiscal oficial.*
________________________________________
## Objetivo do projeto
Criar uma ferramenta em Excel capaz de centralizar informações financeiras relevantes para a organização do Imposto de Renda, facilitando o preenchimento e permitindo uma simulação estimada do imposto com base nos dados informados pelo usuário.
O projeto foi desenvolvido com foco não apenas nos cálculos, mas também na experiência de uso, utilizando elementos visuais e navegação por botões para proporcionar uma interface mais próxima de um aplicativo.
________________________________________
## Estrutura do aplicativo
O FiscoApp é composto por quatro áreas principais:
**TITULAR:** Cadastro das informações pessoais do titular
**INFORMES:** Registro de contas e saldos bancários
**NOTAS:** Registro de entradas e rendimentos ao longo do ano
**SIMULAÇÃO:** Consolidação dos rendimentos, deduções e estimativa do imposto

________________________________________
## Principais fórmulas e recursos utilizados
Um dos principais objetivos técnicos do projeto foi trabalhar diferentes funções do Excel para transformar os dados inseridos pelo usuário em informações consolidadas.
### SOMASE
Utilizada na aba SIMULAÇÃO para consolidar os valores da aba NOTAS de acordo com sua classificação.
Exemplo:
| =SOMASE(Tabela13[CLASSIFICAÇÃO IR];"Tributável";Tabela13[VALOR]) |
Dessa forma, os rendimentos tributáveis, isentos e não tributáveis podem ser totalizados separadamente.
________________________________________
### SE + E
A combinação das funções SE e E foi utilizada para identificar a faixa de alíquota aplicável, comparando a base de cálculo com os limites definidos na tabela de alíquotas.
A lógica permite verificar em qual faixa o valor calculado se encontra e retornar a respectiva alíquota.
________________________________________
### PROCV
Depois da identificação da alíquota, a função PROCV é utilizada para localizar a parcela a deduzir correspondente.
________________________________________
### SEERRO
A função SEERRO foi utilizada para evitar que erros de cálculo ou ausência de dados sejam exibidos diretamente ao usuário.
Isso contribui para uma experiência de utilização mais limpa e amigável.
________________________________________
Tabelas estruturadas
O projeto também utiliza Tabela do Excel para organizar os registros de entradas e rendimentos.
Isso permite que as fórmulas trabalhem diretamente com referências estruturadas, tornando a consolidação dos dados mais dinâmica.
________________________________________
## 🎨 Interface e experiência do usuário
Um dos principais diferenciais do projeto é a preocupação com a experiência de utilização.
Foi criado um menu de navegação fixo, contendo botões que funcionam como links para as diferentes áreas do aplicativo.
Dessa forma, o usuário pode navegar entre:
TITULAR → INFORMES → NOTAS → SIMULAÇÃO
sem a sensação de estar alternando entre diferentes planilhas. A proposta é fazer com que a estrutura se comporte visualmente como um pequeno aplicativo desenvolvido dentro do Excel.

### Imagem da Tela Titular:

<img src="Imagens\Titular.png" >
________________________________________

## Tecnologias e recursos
•	Microsoft Excel
•	Tabelas estruturadas
•	Fórmulas e funções do Excel
•	Validação de dados
•	Hiperlinks para navegação
•	Formatação condicional
•	Organização e tratamento de dados
•	Interface visual
•	Simulação baseada em regras
•	Excel com apoio de IA
Principais funções utilizadas
SOMASE • SE • E • PROCV • SEERRO • SOMA
________________________________________
## Aprendizados
Durante o desenvolvimento deste projeto, foram praticados conceitos relacionados a:
* Estruturação de uma aplicação dentro do Excel
* Organização de informações financeiras
* Utilização de tabelas estruturadas
* Criação de fórmulas compostas
* Aplicação de regras condicionais
* Busca de informações em tabelas auxiliares
* Tratamento de erros
* Criação de interfaces mais intuitivas no Excel
* Navegação entre diferentes áreas de uma planilha
* Utilização de IA como apoio ao desenvolvimento de soluções no Excel
Além da parte técnica, o projeto ajudou a desenvolver uma visão mais voltada para experiência do usuário e resolução de problemas utilizando dados.
________________________________________

## Possíveis melhorias futuras
Algumas funcionalidades que poderiam ser incorporadas em versões futuras:
* Inclusão de gráficos e indicadores financeiros
* Dashboard com resumo anual
* Controle de despesas dedutíveis
* Inclusão de outras categorias de rendimentos
* Expansão da base de instituições financeiras
* Validação mais completa dos dados inseridos
* Automatização da importação de informações
* Comparação entre diferentes cenários de declaração
* Inclusão de um guia de preenchimento para o usuário
* Aprimoramento da interface e experiência de navegação
________________________________________

### Contexto do projeto
Projeto desenvolvido durante:
Bootcamp Santander – Excel com IA e Claude
Ferramenta principal:
Microsoft Excel
Tipo de projeto:
Aplicação prática / Projeto de portfólio
Tema:
Organização financeira e simulação de Imposto de Renda.

<a href="https://www.linkedin.com/in/thais-cabral-489182198/" target="_blank">Meu Linkedin</a>
 
