# Rastreamento Correios

## Introdução

<div style="text-align: justify">
Para a avaliação do site do Rastreamento Correios foi escolhido o método da avaliação
heurística, justamente por ser um método que orienta o avaliador a inspecionar
sistematicamente a interface em busca de problemas que prejudiquem a usabilidade.
<br/>
A seguir será apresentado todos os dados coletados por meio da inspeção realizada pelo avaliador Daniel Coimbra dos Santos.
</div>

## Dados Coletados

### Visibilidade do estado do sistema

<div style="text-align: justify">
Ao requisitar os dados de um rastreio, enquanto o website
carrega as mudanças, é possível ver uma mensagem dizendo “Buscando”, dando feedback ao
usuário; também há mensagem de erro ao falhar o captcha no momento da requisição. O
campo fica em vermelho e é exibida a mensagem “Captcha inválido”.
</div>

### Correspondência entre o sistema e o mundo real

<div style="text-align: justify">
É possível argumentar que o termo
“Captcha”, apesar de reconhecido por programadores, não é necessariamente semântico a
toda a população que irá utilizar o sistema online para rastreio de encomenda dos Correios,
podendo assim criar uma distância linguística entre o público que interage com o software e o
próprio sistema.
</div>

### Controle e liberdade do usuário

<div style="text-align: justify">
Não há muito o que errar no sistema, o usuário preenche
apenas dois campos, o cpf e o captcha. Quando há de fato um erro, o usuário precisa corrigir o
campo em que existe o erro, seja por cpf inválido ou por captcha inválido.
</div>

### Consistência e padronização

<div style="text-align: justify">
A linguagem é bem padronizada, o único ponto delicado é
quanto ao uso da palavra “captcha”, já citada acima, que pode ser desconhecida pelos
usuários.
</div>

### Reconhecimento em vez de memorização

<div style="text-align: justify">
O sistema é bem direto e simples de ser operado,
mas poderia ser mais informativo, já que pessoas não versadas em tecnologia podem ter
dificuldades ao lidar com ele pela primeira vez.
</div>

### Flexibilidade e eficiência de uso

<div style="text-align: justify">
Não existe botão de ajuda, mas o usuário recebe instruções
para preencher os campos de input.
</div>

### Projeto estético e minimalista

<div style="text-align: justify">
O site é bem enxuto, conta com o conteúdo do serviço no
corpo, um hamburguer menu na barra do topo e um diversos links para outros serviços no
rodapé.
</div>

### Prevenção de erros

<div style="text-align: justify">
Direciona o usuário para a tela de login diretamente ao tentar acessar um
rastreio sem ter entrado na conta, além disso, somente as mensagens de erro.
</div>

### Ajude os usuários a reconhecerem, diagnosticarem e se recuperarem de erros

<div style="text-align: justify">
Existe um
contexto em que um usuário pode se ver sem solução, caso não verifique com calma a
situação. No caso de um usuário com um número X de encomendas, suficiente para o campo
de input sair do campo de visão do usuário, ao clicar em um objeto, solicitando mais dados de
um determinado rastreio, se o captcha estiver errado, a mensagem somente irá aparecer lá em
cima no input, ou seja, fora do campo de visão de quem opera o sistema, fazendo assim com
que um desavisado pense que o site está quebrado. Vale salientar que o captcha reseta a cada
clique em um objeto, então ao requisitar dados a partir de um segundo rastreio na mesma
sessão, é necessário sobrescrever o campo de escrita para combinar com o novo captcha
gerado, e isso não é informado ao usuário.
</div>

### Ajuda e documentação

<div style="text-align: justify">
Existem as instruções para preenchimento dos campos e um botão
que direciona o usuário para as perguntas frequentes, além de as mensagens de erro dos
inputs.
</div>

## Bibliografia
> Nielsen, Jakob (1994). Usability Engineering. Morgan Kaufmann Publishers Inc., San Francisco, CA, USA.

> BARBOSA, Simone. Avaliação Heurística. In: INTERAÇÃO Humano-Computador e Experiência do Usuário. [S. l.: s. n.], 2021. cap. 12, p. 282.

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 16/07/2022 | `0.1`  | Criação da página de Avaliação do Rastreamento Correios | [Natan Santana](https://github.com/Neitan2001) | 
