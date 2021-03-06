# GOMS

## Introdução

<div style="text-align: justify">
<p>
Card et al. (1983) propuseram um conjunto de modelos chamado de família GOMS (Goals, Operators, Methods, and Selection Rules — Objetivos, Operadores, Métodos e Regras de Seleção) para analisar o desempenho de usuários competentes de sistemas computacionais, realizando tarefas dentro da sua competência e sem cometer erros. Muitos sistemas são projetados considerando que as pessoas se tornam habilidosas no seu uso e, portanto, vão querer formas eficientes de realizar tarefas rotineiras. Os modelos GOMS têm se mostrado úteis para prever o desempenho, ou seja, predizer o impacto de decisões de design no desempenho competente (John, 2003).
</p>

<p>
A análise GOMS é adequada para situações onde os usuários estão realizando tarefas que já dominam, e não situações onde é preciso resolver um problema ou identificar qual o próximo passo a dar.
O GOMS pode ser utilizado tanto quantitativamente, fornecendo previsões sobre o tempo necessário para realizar tarefas, como qualitativamente, no sentido de auxiliar na elaboração de programas de treinamento, sistemas de ajuda e sistemas tutores inteligentes, pois um modelo GOMS contém uma descrição detalhada do conhecimento necessário para realizar cada tarefa (John, 2003). Também pode ser utilizado para reprojetar um sistema: pode revelar um objetivo frequente apoiado por um método muito ineficiente; pode mostrar que alguns objetivos não são apoiados por nenhum método; e pode revelar onde objetivos semelhantes são apoiados por métodos inconsistentes, uma situação em que os usuários podem ter problemas para lembrar o que fazer. 
</p>

<p>
A família GOMS possui diversos modelos, mas dentre eles, três se sobressaem: KLM (Card et al., 1983), CMN-GOMS (Card et al., 1983) e CPM-GOMS (John e Gray, 1995). Na nossa análise GOMS adotaremos o modelo KLM.
</p>
</div>

## KLM-GOMS
<div style="text-align: justify">
KLM (Keystroke-level model) é uma das técnicas de GOMS e tem o objetivo de prever quanto tempo um usuário levaria para desenvolver uma tarefa em uma rotina sem erros. Essa técnica tem um conjunto predefinido de operadores primitivos, sendo eles:
</div>

* Pressionar uma tecla ou botão;
* Apontar com o mouse um alvo num dispositivo visual;
* Mover as mãos para o teclado ou outro dispositivo;
* Desenhar um segmento de reta;
* Se preparar mentalmente para realizar uma ação ou uma série de ações primitivas;
* Tempo de resposta do sistema.

<div style="text-align: justify">
Essa técnica foi utilizada em nosso projeto a fim de analisar tarefas simples e recorrentes, buscando identificar se há espaço de melhora em relação ao tempo gasto pelos usuários.
</div>

### Objetivo: Cadastro na plataforma

<div style="text-align: justify">
O primeiro objetivo a ser analisado é o de cadastro na plataforma. Como observado na Tabela 1, o tempo levado foi de 1 minuto e 4 segundos.
</div>

<br/>
Método: Primeiro acesso > Inserção de dados > Cadastro concluído

|  Operação | Tempo Médio |
| ------------ | ------------ |
| M - Preparação | 1,20s |
| H - Levar a mão ao mouse | 0,40s |
| P - Levar o cursor ao botão Primeiro acesso | 1,10s |
| B - Clicar no botão Primeiro acesso | 0,10s |
| P - Levar o cursor a caixa de input do CPF | 1,10s |
| B - Clicar na caixa de input do CPF | 0,10s |
| H - Levar a mão do mouse ao teclado | 0,40s |
| T - Digitação de 11 caracteres | 5,1s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor ao botão Avançar | 1,10s |
| B - Clicar no botão Avançar | 0,10s |
| W - Espera do sistema | 2,12s |
| P - Levar o cursor a caixa de input da data de nascimento | 1,10s |
| B - Clicar na caixa de input da data de nascimento | 0,10s |
| H - Levar a mão do mouse ao teclado | 0,40s |
| T - Digitação de 8 caracteres | 4,10s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor a caixa de input do RG | 1,10s |
| B - Clicar na caixa de input do RG | 0,10s |
| H - Levar a mão do mouse ao teclado | 0,40s |
| T - Digitação de 7 caracteres | 3,20s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor ao botão Avançar | 1,10s |
| B - Clicar em Avançar | 0,10s |
| W - Espera do sistema | 2,10s |
| P - Levar o cursor a caixa de input de e-mail | 1,10s |
| B - Clicar na caixa de input de e-mail | 0,10s |
| T - Digitação de 30 caracteres | 14s |
| P - Levar o cursor a caixa de input de confirmação de e-mail | 1,10s |
| B - Clicar na caixa de input de confirmação de e-mail | 0,10s |
| T - Digitação de 30 caracteres | 14s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor ao botão Enviar Dados | 1,10s |
| B - Clicar em Enviar Dados | 0,10s |
| <b>Tempo total</b> | <b>1min 4s</b>

Tabela 1: Análise do desempenho do cadastro com o KLM
<br/><br/>

### Objetivo: Entrar na plataforma

<div style="text-align: justify">
O próximo objetivo a ser analisado é o de login na plataforma. Como observado na Tabela 2, o tempo levado foi de 47 segundos. Pode ser observado que o tempo de espera do sistema foi de 24s, elevando bastante o tempo total de execução da tarefa. É importante ressaltar que mesmo tendo um tempo de espera bastante alto, o usuário não recebe nenhum feedback a respeito dessa demora além de um ícone de loading, o que não esclarece a razão do processo demorar tanto tempo.
</div>
<br/>
Método: Login > Inserção de CPF e Senha > Login concluído

|  Operação | Tempo Médio |
| ------------ | ------------ |
| M - Preparação | 1,20s |
| H - Levar a mão ao mouse | 0,40s |
| P - Levar o cursor ao botão Login | 1,10s |
| B - Clicar no botão Login | 0,10s |
| W - Espera do sistema | 1,07s |
| P - Levar o cursor a caixa de input do CPF | 1,10s |
| B - Clicar na caixa de input do CPF | 0,10s |
| H - Levar a mão do mouse ao teclado | 0,40s |
| T - Digitação de 11 caracteres | 5,1s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor a caixa de input da senha | 1,10s |
| B - Clicar na caixa de input da senha | 0,10s |
| H - Levar a mão do mouse ao teclado | 0,40s |
| T - Digitação de 8 caracteres | 3,7s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor ao checkbox "não sou um robô" | 1,10s |
| B - Clicar no checkbox "não sou um robô" | 0,10s |
| P - Levar o cursor ao botão Entrar | 1,10s |
| P - Clicar em Entrar | 0,10s |
| W - Espera do sistema | 24s |
| <b>Tempo total</b> | <b>47s</b> 

### Objetivo: Recuperar a senha

<div style="text-align: justify">
O próximo objetivo a ser analisado é o de recuperação de senha. Como observado na Tabela 3, o tempo levado foi de 1 minuto e 5 segundos. Pode-se perceber que o tempo de execução dessa tarefa se assemelha muito ao tempo de execução de cadastro na plataforma, isso acontece porque o fluxo de recuperação de senha é igual ao de cadastro. Informações como CPF, data de nascimento, RG e e-mail são necessários para fazer essa recuperação, fazendo com que o usuário gaste um tempo desnecessário para a realização da tarefa.
</div>

<br/>
Método: Login > Esqueci minha senha > Recuperação de senha

|  Operação | Tempo Médio |
| ------------ | ------------ |
| M - Preparação | 1,20s |
| H - Levar a mão ao mouse | 0,40s |
| P - Levar o cursor ao botão Login | 1,10s |
| B - Clicar no botão Login | 0,10s |
| P - Levar o cursor ao botão Esqueci e-mail ou senha | 1,10s |
| B - Clicar no botão Esqueci e-mail ou senha | 0,10s |
| P - Levar o cursor a caixa de input do CPF | 1,10s |
| B - Clicar na caixa de input do CPF | 0,10s |
| H - Levar a mão do mouse ao teclado | 0,40s |
| T - Digitação de 11 caracteres | 5,1s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor ao botão Avançar | 1,10s |
| B - Clicar no botão Avançar | 0,10s |
| W - Espera do sistema | 2,12s |
| P - Levar o cursor a caixa de input da data de nascimento | 1,10s |
| B - Clicar na caixa de input da data de nascimento | 0,10s |
| H - Levar a mão do mouse ao teclado | 0,40s |
| T - Digitação de 8 caracteres | 4,10s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor a caixa de input do RG | 1,10s |
| B - Clicar na caixa de input do RG | 0,10s |
| H - Levar a mão do mouse ao teclado | 0,40s |
| T - Digitação de 7 caracteres | 3,20s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor ao botão Avançar | 1,10s |
| B - Clicar em Avançar | 0,10s |
| W - Espera do sistema | 2,10s |
| P - Levar o cursor a caixa de input de e-mail | 1,10s |
| B - Clicar na caixa de input de e-mail | 0,10s |
| T - Digitação de 30 caracteres | 14s |
| P - Levar o cursor a caixa de input de confirmação de e-mail | 1,10s |
| B - Clicar na caixa de input de confirmação de e-mail | 0,10s |
| T - Digitação de 30 caracteres | 14s |
| H - Levar a mão do teclado ao mouse | 0,40s |
| P - Levar o cursor ao botão Enviar Dados | 1,10s |
| B - Clicar em Enviar Dados | 0,10s |
| <b>Tempo total</b> | <b>1min 5s</b>

### Objetivo: Gerar o relatório de nada consta mensal

<div style="text-align: justify">
O próximo objetivo a ser analisado é o de geração de um relatório de nada consta mensal. Como observado na Tabela 4, o tempo levado foi de 13 segundos. Essa tarefa não necessita de nenhuma digitação, fazendo com a sua realização seja mais rápida. Porém, essa ação está gerando um erro ao ser concluída e o relatório não é gerado, como pode-se observar na Figura 1. Devido a esse erro, não foi possível registrar o tempo de espera do sistema para a geração do relatório.
</div>
<br/>
Método: Gerar relatório mensal > Selecionar o mês > Geração concluída

|  Operação | Tempo Médio |
| ------------ | ------------ |
| M - Preparação | 1,20s |
| H - Levar a mão ao mouse | 0,40s |
| P - Levar o cursor ao botão correspondente ao endereço correto | 1,10s |
| B - Clicar no botão correspondente ao endereço correto | 0,10s |
| P - Levar o cursor ao botão Relatório Nada Consta | 1,10s |
| B - Clicar no botão Relatório Nada Consta | 0,10s |
| W - Espera do sistema | 2,58s |
| P - Levar o cursor ao botão Mensal | 1,10s |
| B - Clicar no botão Mensal | 0,10s |
| P - Levar o cursor ao botão de Selecionar Fatura | 1,10s |
| B - Clicar em Selecionar Fatura | 0,10s |
| P - Levar o cursor até o mês escolhido | 1,10s |
| B - Clicar no mês escolhido | 0,10s |
| P - Levar o cursor até o botão Gerar Relatório | 1,10s |
| B - Clicar em Gerar Relatório | 0,10s |
| W - Espera do sistema |
| <b>Tempo total</b> | <b>13s</b>

![Mensagem de Erro](../../assets/MensagemErro.png)
<b>Figura 1 - Mensagem de erro</b>

### Objetivo: Gerar o relatório de nada consta anual
<div style="text-align: justify">
O próximo objetivo a ser analisado é o de geração de um relatório de nada consta anual. Como observado na Tabela 5, o tempo levado foi de 10 segundos. Assim como o relatório mensal, essa tarefa não necessita de nenhuma digitação. A geração do relatório está com o mesmo erro do relatório mensal e por essa razão, não foi possível registrar o tempo de espera do sistema.
</div>
<br/>
Método: Gerar relatório anual > Geração concluída

|  Operação | Tempo Médio |
| ------------ | ------------ |
| M - Preparação | 1,20s |
| H - Levar a mão ao mouse | 0,40s |
| P - Levar o cursor ao botão correspondente ao endereço correto | 1,10s |
| B - Clicar no botão correspondente ao endereço correto | 0,10s |
| P - Levar o cursor ao botão Relatório Nada Consta | 1,10s |
| B - Clicar no botão Relatório Nada Consta | 0,10s |
| W - Espera do sistema | 2,58s |
| P - Levar o cursor ao botão Anual | 1,10s |
| B - Clicar no botão Anual | 0,10s |
| P - Levar o cursor até o botão Gerar Relatório | 1,10s |
| B - Clicar em Gerar Relatório | 0,10s |
| W - Espera do sistema |
| <b>Tempo total</b> | <b>10s</b>

## Bibliografia
> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021);Interação Humano-Computador e Experiência do usuário.

> Card, Stuart K., Newell, Allen, e Moran, Thomas P. (1983). The Psychology of Human-Computer
Interaction. L. Erlbaum Associates Inc., USA.

> John, Bonnie E. (2003). Information processing and skilled behavior. In HCI models, theories, and
frameworks: Toward a multidisciplinary science, pages 55–101. Morgan Kaufman

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 18/07/2022 | `0.1`  | Criação da página | [Natan Santana](https://github.com/Neitan2001) | [Luíza Esteves](https://github.com/luiza-esteves)
| 19/07/2022 | `0.2`  | Adição das tabelas de Operação e Tempo Médio | [Clara Ribeiro](https://github.com/clara-ribeiro) | [Natan Santana](https://github.com/Neitan2001)
19/07/2022 | `0.3` | Adição de introdução e divs | [Rafael Xavier](https://github.com/rafaelxavierr) | [Natan Santana](https://github.com/Neitan2001)