# Governo Pernambuco

## Introdução

<div style="text-align: justify">
Ao analisar o site do Governo de Pernambuco, cujo processo de
desenvolvimento já foi feito, o melhor método encontrado para fazer uma
avaliação inicial neste relatório será por meio de uma Avaliação Heurística,
uma vez que ela se baseia em identificar problemas na interface que possam
atrapalhar a usabilidade do sistema.
<br/><br/>
A seguir será explicado brevemente o método de avaliação escolhido e apresentado todos os dados
coletados por meio da inspeção realizada pela avaliadora Luíza Esteves.
</div>

## Heurísticas de Nielsen

<div style="text-align: justify">
As heurísticas de Nielsen permitem uma análise de um sistema que já
está em desenvolvimento ou foi finalizado. Com isso, é possível buscar
soluções de forma rápida que melhorem a usabilidade do sistema. Existem 10
heurísticas que foram construídas para serem utilizadas como base de
identificação de problemas no sistema:
</div>

- Visibilidade do estado do sistema: Permitir que o usuário entenda qual o status do sistema.
- Correspondência entre o sistema e o mundo real: Os termos e textos que se encontram no site devem estar de acordo com a sua finalidade.
- Controle e liberdade do usuário: O usuário consegue sair de uma ação caso deseje ou volte em uma ação.
- Consistência e padronização: O sistema segue padrões definidos de acordo com as convenções da plataforma.
- Reconhecimento em vez de memorização:  O usuário consegue identificar o que cada parte do sistema significa e realizar suas ações sem a necessidade de consulta ou ajuda.
- Flexibilidade e eficiência de uso: A utilização de ícones intuitivos que facilitem o reconhecimento de funções no sistema e aumente a eficiência de realização de um objetivo.
- Projeto estético e minimalista: Interface simples e fácil de se entender, sem uma sobrecarga de informações no usuário.
- Prevenção de erros: Colocar obstáculos que impeçam o usuário de cometer erros durante o uso do sistema.
- Ajude os usuários a reconhecerem, diagnosticarem e se recuperarem de erros:  Mostrar mensagens de erros de forma clara e atenciosa, para que o usuário consiga reconhecer e corrigir seus erros.
- Ajuda e documentação: Ter uma documentação do sistema que possa ser utilizada caso o usuário sinta dificuldade de realizar alguma operação.

## Interpretação e identificação de problemas no sistema

### 1 - Visibilidade e status do sistema

- Verificação
    - O sistema mantém feedback?
    - Os feedbacks são adequados e no tempo certo?
    - Os usuários conseguem identificar e compreender o feedback?
- Descrição do problema: Ao iniciar o processo de carregamento de uma página, o sistema
coloca uma mensagem de que a página está sendo carregada mas não é
removida ao fim do carregamento. Isso pode levar o usuário a esperar
demasiadamente por um carregamento que já foi feito e desistir de utilizar o
site.
- Grau de Severidade:
- [ ] 1 - Cosmético
- [x] 2 - Pequeno
- [ ] 3 - grande
- [ ] 4 - Catastrófico
- Natureza do problema:
- [ ] Barreira
- [ ] Obstáculo
- [x] Ruído
- Perspectiva da Tarefa:
- [ ] Problema Principal
- [x] Problema Secundário
- Correção possível: Remover a indicação de carregando quando finalizar o carregamento
do sistema.

### 2 - Compatibilidade com o mundo real

- Verificação
    - Os padrões identificados em um sistema comum estão sendo seguidos?
    - As expressões utilizadas condizem com o padrão governamental?
- Descrição do problema: Existem 3 menus diferentes em partes diferenciadas e com layouts diferentes na página inicial, o que pode dificultar o entendimento do funcionamento, já que o comum é existir um menu superior ou lateral, com seus subtipos abertos ao selecionar um título principal.
- Grau de Severidade:
- [ ] 1 - Cosmético
- [ ] 2 - Pequeno
- [x] 3 - grande
- [ ] 4 - Catastrófico
- Natureza do problema:
- [ ] Barreira
- [ ] Obstáculo
- [x] Ruído
- Perspectiva da Tarefa:
- [x] Problema Principal
- [ ] Problema Secundário
- Correção possível: Criar um menu superior único, com títulos gerais e seus subtemas devem aparecer ao passar o mouse por cima, evitando uma grande quantidade de títulos que geram sobrecarga de informações.

### 3 - Consistência e padronização
- Verificação
    - Todos os títulos condizem com o seu conteúdo?
    - Existem ações diferentes que significam a mesma coisa?
- Descrição do problema: Dentro da página de serviços onlines, tanto na parte de cidadãos quanto de empresas estão apenas faixas escritas “testes” e um link que redireciona ao site do Google, trazendo inconsistência e fugindo do padrão de conteúdo que deveria estar.
- Grau de Severidade:
- [ ] 1 - Cosmético
- [ ] 2 - Pequeno
- [ ] 3 - grande
- [x] 4 - Catastrófico
- Natureza do problema:
- [x] Barreira
- [ ] Obstáculo
- [ ] Ruído
- Perspectiva da Tarefa:
- [x] Problema Principal
- [ ] Problema Secundário
- Correção possível: Adicionar os serviços disponíveis para os cidadãos e as empresas e retirar a sessão de teste. Caso ainda não haja esse serviço disponível, excluir essa opção do menu e remover a página temporariamente até que esteja tudo pronto.

### 4 - Projeto estético e minimalista
- Verificação
    - A interface contém apenas informações necessárias?
    - O design elaborado é simples?
    - O usuário consegue visualizar apenas o importante para sua ação?
- Descrição do problema: A estética produzida para o sistema possui uma carga de informações muito grande e mal posicionada. Tanto a página inicial quanto as demais possuem background com imagens que dificultam a leitura, menus mal posicionados e textos com cores fortes.
- Grau de Severidade:
- [ ] 1 - Cosmético
- [ ] 2 - Pequeno
- [x] 3 - grande
- [ ] 4 - Catastrófico
- Natureza do problema:
- [x] Barreira
- [ ] Obstáculo
- [ ] Ruído
- Perspectiva da Tarefa:
- [x] Problema Principal
- [ ] Problema Secundário
- Correção possível: Refazer o design e as cores padrões dos textos do sistema, para que tanto os textos quanto os menus fiquem mais limpos e fáceis de ser entendidos.

## Objetivos e escopo da avaliação

<div style="text-align: justify">
A avaliação realizada busca identificar, em um sistema já existente,
problemas na interface que dificultem sua usabilidade e acessibilidade. Se
tratando de um site que atende uma grande população de diversificadas
características, ele deve ser claro e de fácil identificação nas atividades do
site.
</div>

## Bibliografia
> Nielsen, Jakob (1994). Usability Engineering. Morgan Kaufmann Publishers Inc., San Francisco, CA, USA.

> BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.

> MACIEL, Cristiano; NOGUEIRA, José Luis; CIUFFO, Leandro; GARCIA, Ana Cristina. Avaliação Heurística de Sítios na Web. [S. l.]

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 15/07/2022 | `0.1`  | Criação da página de Avaliação do Governo de Pernambuco | [Natan Santana](https://github.com/Neitan2001) | [Clara Ribeiro](https://github.com/clara-ribeiro)