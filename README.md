# Teste de Análise de Suporte
O teste consiste em uma simulação de atendimento a suporte de uma aplicação de FRONT-END em Angular 7. São cinco questões, estas irão simular problemas encontrados por usuários desta aplicação. As respostas desses chamados devem ser respondidas neste documento abaixo no tópico 'Respostas', e devem conter os seguintes itens*:
 
 - Uma análise inicial, com a finalidade de enriquecer o chamado de suporte. Essa sendo uma análise mais de fluxo de trabalho e não necessariamente técnica;
 - Uma análise técnica, com a finalidade de obter dados mais precisos sobre o erro, podendo indicar o motivo do erro e até indicar uma solução;
 - Uma correção do problema, com a finalidade de corrigir o erro antes de passar para uma equipe de desenvolvimento.
 - Uma mensagem para o usuário que registrou o suporte, explicando o que será feito.

 * A resposta pode ser parcial, mas deve conter pelo menos o primeiro e o ultimo item.

## Pré Requisitos:

 - Um computador com Node.js, NPM e git instalados;
 - Conexão de internet;
 - Navegador Google Chrome;
 - Editor de texto de sua preferência. Como o Sublime, VisualCode, etc;
 - Conta no gitHub.

## Procedimentos:

 - Clonar o repositório encontrado em 'https://github.com/CarlosEduardoFerreiraRamos/support-test-cora';
 - Baixar os pacotes da aplicação com NPM;
 - Subir a aplicação no browser com NPM ou com angular-CLI;
 - Seguir o fluxo descrito descrito nos suportes;
 - Reescreva este arquivo, o README.md, com as respostas;
 - Publique o projeto em seu repositório no gitHub, com o arquivo README.md modificado, e com qualquer alteração que tenha sido feita.

## Questões

  Aba de gerenciamento de usuários
   
   1 - Não é possível desselecionar usuários selecionados:
   - Após selecionar um usuário não tem como retirar a seleção, ele ainda fica marcada em azul mesmo depois de clicar nele;
   
   2 - Ao se clicar em detalhes aciona a seleção de usuário:
   - Se clico no detalhes de um usuário que não está selecionado ele acaba ficando selecionado;
   
   3 - Detalhes do usuário quebrado:
   - Ela abre em branco, sem valor, quebra.
   
  Aba de gerenciamento de produtos:
  
   4 - Produtos com três quotes, a última não valida caso seja validada com valor Zero:
   - Não estou conseguindo mandar a cobrança do produto com sku 'LIB1432', ele não está registrando a quote QA.  
   
   5 - Produto que é desvalidado após ser selecionado ainda é enviado no submit:
   - Selecionei alguns produtos no checkbox do lado do 'select', depois tive que remover o valor da quote de um produto específico e desvalida-lo, mas a contagem de produtos para cobrança ainda estava considerando esse produto.

## Respostas

Aba de gerenciamento de usuários

Questão 1
Análise Inicial - Na aba de gerênciamento de usuário a seleção dos itens está funcionando, porém ao tentar desmarcar o usuário seleciona a aplicação não está desmarcando o item que o cliente clica.

Retorno para Cliente - Prezado, a sua solicitação foi recebida e será feita uma analise, em breve entraremos em contato para informar o prazo para resolução do problema.

##################################################################################################

Questão 2
Análise Inicial - Na aba de gerênciamento de usuários ao clicar no botão detalhes de qualquer usuário o mesmo acaba sendo selecionado.

Retorno para Cliente - Prezado, a sua solicitação foi recebida e será feita uma analise, em breve entraremos em contato para informar o prazo para resolução do problema.

##################################################################################################

Questão 3
Análise Inicial - Foi visto que após clicar no botão detalhes em qualquer usuário listado a aplicação carrega o pop-up porém o mesmo não carrega nenhuma informação.

Análise Técnica - Segue em anexo erro onde id do usuário não foi definido.
https://imgur.com/a/oyokxf0

Retorno para Cliente - Prezado, a sua solicitação foi recebida, após analise a demanda foi encaminhada para nossa equipe de desenvolvimento e em breve entraremos em contato para informar o prazo para resolução do problema.

##################################################################################################

Questão 4
Análise Inicial -   O item citado pelo cliente não informa ao usuário que o valor está incorreto quando o valor é menor que 1.  

Retorno para Cliente - Prezado, a sua solicitação foi recebida, será feita uma análise e em breve entraremos em contato para informar o prazo de resolução do problema.

##################################################################################################

Questão 5
Análise Inicial - Foi encontrado um problema na experiencia do usuário, quando a quote tiver um valor invalido o mesmo deve ser removido da lista de produtos selecionados e informado ao usuário.

Retorno para Cliente - Prezado, a sua solicitação foi recebida, será feita uma análise e em breve entraremos em contato para informar o prazo de resolução do problema.
