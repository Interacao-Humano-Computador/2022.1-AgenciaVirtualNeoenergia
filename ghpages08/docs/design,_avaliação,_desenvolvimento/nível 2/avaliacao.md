# Avaliação do Protótipo de Papel

## Introdução

<div style="text-align: justify">

O seguinte documento apresentará o relato das entrevistas realizadas por Natan Tavares Santana e Luíza Esteves no dia 31/08/2022, especificando o objetivo da avaliação, os dados coletados e as suas interpretações.
</div>

## Objetivo

Após a validação e criação da versão final do Storyboard e da Análise de Tarefas, foi feito um [Protótipo de Papel](./prototipo.md) que busca atingir o modelo conceitual levantado, eliminando os problemas encontrados no sistema atual. Assim, é de suma importância fazer a avaliação deste protótipo a fim de verificar com possíveis usuários se as suas necessidades foram atendidas e corrigir qualquer erro que o time possa ter deixado passar. 

## Método

<div style="text-align: justify">
O método utilizado pelo grupo a fim de validar o protótipo de papel foi a entrevista, a qual trata-se de uma conversa guiada por um roteiro de perguntas ou tópicos, na qual um entrevistador busca obter informação de um entrevistado (Seidman, 2019). A fim de recolher dados que possam ajudar a complementar os storyboards feitos anteriormente, foi decidido executar uma entrevista semiestruturada a qual possui um roteiro de perguntas e permite ao entrevistador ter uma liberdade para mudar a ordem dos tópicos abordados e explorar as respostas fornecidas pelo entrevistado, tendo em mente o foco nos objetivos da entrevista.
</div>

## Avaliadores e Participantes

<div style="text-align: justify">
As entrevistas foram conduzidas pelos avaliadores Natan Tavares Santan e Luíza Esteves. O entrevistador Natan ficou responsável por fazer as perguntas e a entrevistadora Luíza por fazer as anotações. Quanto aos participantes, o planejado era entrevistar 3 pessoas, porém um dos entrevistados cancelou de última hora e não foi possível encontrar outro participante a tempo.
</div>
<div style="text-align: justify">
Com a finalidade de preservar o anonimato dos participantes, os nomes reais não serão utilizados e será usado nomes fictícios durante o relato dos dados coletados. A primeira entrevistada, o qual será chamada de Natália, possui 22 anos e é responsável por pagar a conta de energia da casa dela. Já o segundo entrevistado, o qual será chamado de Marcos, possui 20 anos e também é responsável por pagar a conta de energia da casa dele. Os dois entrevistados se encaixam dentro do perfil de usuário levantado durante a fase de Análise de Requisitos. Além disso, ambos são responsáveis pela conta de energia, possuindo as mesmas necessidades dos usuários que acessam a Agência Virtual da NeoEnergia.
</div>

## Sumário dos dados

### Natália

| Pergunta | Resposta |
| ---- | ------ | 
|  Qual é a sua idade? | 22 anos  | 
|  É você quem paga a conta de energia na sua casa? | Sim  |
|  Após a simulação e observando os protótipos da tarefa de Login como usuário, você identifica que a sequência das atividades seja coerente? | Sim |
|  Após a simulação e observando os protótipos da tarefa de Recuperação de Senha como usuário, você identifica que a sequência das atividades seja coerente? | Sim |
|  Após a simulação e observando os protótipos da tarefa de Recuperação de Email como usuário, você identifica que a sequência das atividades seja coerente? | Não, não faz sentido esta funcionalidade estar disponível na tela de login como "Esqueci email", pois o usuário não usa o email para entrar na conta e no fluxo de recuperar senha, é mostrado o email cadastrado |
|  Após a simulação e observando os protótipos da tarefa de Relatório Nada Consta Anual como usuário, você identifica que a sequência das atividades seja coerente? | Sim |
|  Após a simulação e observando os protótipos da tarefa de Relatório Nada Consta Mensal como usuário, você identifica que a sequência das atividades seja coerente? | Sim |
|  Você imagina alguma outra forma de solução que poderia ser representado pelo protótipo? | Sim, a funcionalidade de recuperar email poderia estar no fluxo de recuperação de senha como "Perdi acesso ao meu email" |

### Marcos

| Pergunta | Resposta |
| ---- | ------ | 
|  Qual é a sua idade? | 20 anos  | 
|  É você quem paga a conta de energia na sua casa? | Sim  |
|  Após a simulação e observando os protótipos da tarefa de Login como usuário, você identifica que a sequência das atividades seja coerente? | Sim |
|  Após a simulação e observando os protótipos da tarefa de Recuperação de Senha como usuário, você identifica que a sequência das atividades seja coerente? | Sim |
|  Após a simulação e observando os protótipos da tarefa de Recuperação de Email como usuário, você identifica que a sequência das atividades seja coerente? | Não, a funcionalidade de "Esqueci meu email" deveria estar no fluxo de recuperação de senha pois é o unico momento que o usuário utiliza o email para executar a tarefa, diferentemente do login |
|  Após a simulação e observando os protótipos da tarefa de Relatório Nada Consta Anual como usuário, você identifica que a sequência das atividades seja coerente? | Sim |
|  Após a simulação e observando os protótipos da tarefa de Relatório Nada Consta Mensal como usuário, você identifica que a sequência das atividades seja coerente? | Sim |
|  Você imagina alguma outra forma de solução que poderia ser representado pelo protótipo? | Sim, a funcionalidade de recuperar email poderia estar no fluxo de recuperação de senha como "Perdi acesso ao meu email" |

## Problemas encontrados

<div style="text-align: justify">
A seguir será listado os problemas encontrados pelos entrevistados:
</div>

- Recuperação de email: Tanto Natália quanto Marcos fizeram a mesma pontuação de que o acesso à funcionalidade de Recuperar Email deveria ficar no fim do fluxo da recuperação de senha como uma opção chamado "Perdi acesso ao meu email", pois esse seria o único cenário de que o usuário iria precisar mudar o email sem acessar a conta já que no login é pedido o CPF e não o email do usuário.


## Aplicação das Sugestões

<div style="text-align: justify">
Como sugerido pelos entrevistados, será retirado a opçção de "Esqueci meu email" da tela de login e será adicionado a opção de "Perdi acesso ao meu email" no final do fluxo de recuperação de senha quando o email de recuperação é enviado para o usuário. Essas modificações podem ser verificadas na página do Protótipo de Baixa Fidelidade.
</div>


## Conclusão

<div style="text-align: justify">
As entrevistas conseguiram levantar pontos importantes que não haviam sido pensados durante a construção do protótipo e contribuiram para que a versão final ficasse com mais qualidade de uso.
</div>

## Bibliografia
> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021);Interação Humano-Computador e Experiência do usuário.

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 01/09/2022 | `0.1`  | Criação do documento de relato da entrevista do protótipo de papel | [Natan Santana](https://github.com/Neitan2001) | [Clara Ribeiro](https://github.com/clara-ribeiro) |