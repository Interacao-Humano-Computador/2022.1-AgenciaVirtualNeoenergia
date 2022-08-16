# Princípios Gerais do Projeto

## Introdução
Os princípios gerais de um projeto voltados para o Design e IHC servem de base para apontar objetivos, regras e boas práticas que devem ser seguidas dentro de um escopo específico. No entanto, a elaboração de tais regras não substituem outras fases, como análise, design e avaliação de IHC, que descrevem detalhadamente pontos importantes dentro dessa construção.

## Diretrizes

A construção dessas diretrizes se baseiam em nove pontos:

- **correspondência com as expectativas dos usuários**: o usuário deve ser capaz de identificar relacionamentos entre ações e suas consequências dentro do sistema;
- **simplicidade nas estruturas das tarefas**: fazer com que as tarefas tenham um ciclo de realização o mais simples possível para o usuário;
- **equilíbrio entre controle e liberdade do usuário**: trazer o usuário para dentro do controle das ações, mas reduzindo ao máximo a necessidade do mesmo realizar decisões. Com opções de saída a todo momento de uma tarefa em execução;
- **consistência e padronização**: trazer ações, resultados, layouts e diálogos de forma padronizada dentro de todo o sistema, para trazer uma maior consistência no entendimento do usuário;
- **promoção da eficiência do usuário**: evitar que processamentos que demandem mais tempo impeçam o usuário de realizar outras atividades, agilizando suas atividades dentro do sistema. É importante também não interrompê-lo dentro de suas ações sem necessidade e sempre protegê-las;
- **antecipação das necessidades do usuário**: o sistema deve prever o que o usuário irá precisar, de acordo com o andamento de uma ação. Para isso, pode fornecer informações extras antecipadamente, definir valores padrão em um formulário, entre outras atividades;
- **visibilidade e reconhecimento**: deve-se mostrar ao usuário quais atividades são possíveis de realizar e como que elas devem ser feitas. Além disso, ao finalizá-las, deve-se dar algum indicativo de que a operação se encerrou, seja visual ou sonora para se entender o estado do sistema;
- **conteúdo relevante e expressão adequada**: trazer quatro princípios dentro de uma interação: qualidade, quantidade, relação e modo;
- **projeto para erros**: planejar o sistema pensando sempre que um erro pode ser cometido em qualquer parte de uma ação, trazendo opções para desfazer o erro.

## Aplicação dos princípios no projeto

Dentro do sistema, fizemos a análise do uso dos princípios das seguintes atividades: recuperação de senha, recuperação de email e geração do relatório nada consta. A partir disso conseguimos identificar problemas com as seguintes diretrizes:

**Correspondência com as expectativas dos usuários**

Esse princípio deixa a desejar em todas as atividades citadas acima. Ao solicitar a geração do relatório nada consta, não é notificado ao usuário sobre o andamento da atividade nem se foi concluída, trazendo dificuldades para o usuário compreender se conseguiu efetuar a ação. Já na recuperação de senha e email, o sistema solicita que seja informado dados pessoais, e, quando a pessoa clica no botão de prosseguir, não é informado se os dados inseridos constam na base ou como prosseguir a seguir. Dentro disso, é importante inserir mais mensagem que informem melhor o usuário sobre qual a situação do sistema de acordo com as atividades.

**Visibilidade e reconhecimento**

O usuário não consegue reconhecer dentro das atividades quando elas foram encerradas, já que nenhum indicativo nem de forma sonora nem de forma visual, deixando-o confuso ou esperando por algo sem saber se finalizou.

**Projeto para erros**

Ao solicitar o relatório nada consta, o sistema não confere se o usuário cadastrado já teve alguma conta para ser paga, o que pode acabar gerando problemas e inconsistências. Na atividade de recuperação, também não é dado indicativo para os usuários que não possuem conta de que eles não conseguem fazer uma recuperação.

## Conclusão

Fazendo uma análise do sistema da NeoEnergia em relação às diretrizes apresentadas, podemos identificar necessidades de melhorias de acordo com as mesmas. É necessário melhorar principalmente no aspecto de trazer para o usuário respostas do andamento do sistema.

## Bibliografia
> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021);Interação Humano-Computador e Experiência do usuário.

## Tabela de Versionamento
| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 26/07/2022 | `0.1`  | Criação da página de Princípios Gerais do Projeto | [Luíza Esteves](https://github.com/luiza-esteves) | [Clara Ribeiro](https://github.com/clara-ribeiro)
| 16/08/2022 | `0.2`  | Ajustes da página de Princípios Gerais do Projeto | [Luíza Esteves](https://github.com/luiza-esteves) | [Natan Santana](https://github.com/Neitan2001)