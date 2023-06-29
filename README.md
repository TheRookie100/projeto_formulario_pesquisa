# Histórias de Usuários

- Você deve ter um elemento h1 com um id "title".
- Você deve ter um elemento p com um id "description".
- Você deve ter um elemento form com um id "survey-form".
- Dentro do elemento de formulário, você deve ter um campo de input para o nome com um id "name" e o atributo type definido como "text".
- Dentro do elemento de formulário, você deve ter um campo de input para o e-mail com um id "email".
- Se você inserir um e-mail que não esteja formatado corretamente, verá um erro de validação HTML5.
- Dentro do formulário, você pode inserir um número em um campo de input com o id "number".
- A entrada numérica não deve aceitar não-números, impedindo que você os digite ou exibindo um erro de validação HTML5 (dependendo do seu navegador).
- Se você inserir números fora do intervalo definido pelos atributos min e max, você verá um erro de validação HTML5.
- Para os campos de entrada de nome, e-mail e número, você pode ver os elementos label correspondentes no formulário, que descrevem a finalidade de cada campo com os seguintes IDs: "name-label", "email-label" e "number-label".
- Para os campos de entrada de nome, e-mail e número, você pode ver o texto do espaço reservado que fornece uma descrição ou instruções para cada campo.
- Dentro do elemento de formulário, você deve ter um elemento select com o id "dropdown" e pelo menos duas opções para escolher.
- Dentro do elemento de formulário, você pode selecionar uma opção de um grupo de pelo menos dois botões de opção agrupados usando o atributo name.
- Dentro do elemento de formulário, você pode selecionar várias opções em uma série de caixas de seleção, cada uma delas deve ter um atributo value.
- Dentro do elemento de formulário, você verá um elemento textarea para comentários adicionais.
- Dentro do elemento de formulário, você verá um botão com o id "submit" para enviar todas as entradas.

## Testes

Esperando: Você deve ter um elemento h1 com o id "title".
Esperando: O elemento h1 com o id "title" não deve estar vazio.
Esperando: Você deve ter um elemento p com o id "description".
Esperando: O elemento p com o id "description" não deve estar vazio.
Esperando: Você deve ter um elemento form com o id "survey-form".
Esperando: Você deve ter um elemento input com o id "name".
Esperando: O campo de input com o id "name" deve ter o atributo type definido como "text".
Esperando: O campo de input com o id "name" deve exigir entrada.
Esperando: O campo de input com o id "name" deve ser descendente de #survey-form.
Esperando: Você deve ter um elemento input com o id "email".
Esperando: O campo de input com o id "email" deve ter o atributo type definido como "email".
Esperando: O campo de input com o id "email" deve exigir entrada.
Esperando: O campo de input com o id "email" deve ser descendente de #survey-form.
Esperando: Você deve ter um elemento input com o id "number".
Esperando: O campo de input com o id "number" deve ser descendente de #survey-form.
Esperando: O campo de input com o id "number" deve ter o atributo type definido como "number".
Esperando: O campo de input com o id "number" deve ter o atributo min com um valor numérico.
Esperando: O campo de input com o id "number" deve ter o atributo max com um valor numérico.
Esperando: Você deve ter um elemento label com o id "name-label".
Esperando: Você deve ter um elemento label com o id "email-label".
Esperando: Você deve ter um elemento label com o id "number-label".
Esperando: O elemento label com o id "name-label" deve conter um texto que descreva a entrada.
Esperando: O elemento label com o id "email-label" deve conter um texto que descreva a entrada.
Esperando: O elemento label com o id "number-label" deve conter um texto que descreva a entrada.
Esperando: O elemento label com o id "name-label" deve ser descendente de #survey-form.
Esperando: O elemento label com o id "email-label" deve ser descendente de #survey-form.
Esperando: O elemento label com o id "number-label" deve ser descendente de #survey-form.
Esperando: O campo de input com o id "name" deve ter o atributo placeholder com um valor.
Esperando: O campo de input com o id "email" deve ter o atributo placeholder com um valor.
Esperando: O campo de input com o id "number" deve ter o atributo placeholder com um valor.
Esperando: Você deve ter um elemento select com o id "dropdown".
Esperando: O elemento select com o id "dropdown" deve ter pelo menos duas opções selecionáveis (não desabilitadas).
Esperando: O elemento select com o id "dropdown" deve ser descendente de #survey-form.
Esperando: Você deve ter pelo menos dois elementos input com o atributo type definido como "radio" (botões de opção).
Esperando: Você deve ter pelo menos dois botões de opção descendentes de #survey-form.
Esperando: Todos os botões de opção devem ter o atributo value com um valor.
Esperando: Todos os botões de opção devem ter o atributo name com um valor.
Esperando: Cada grupo de botões de opção deve ter pelo menos 2 botões de opção.
Esperando: Você deve ter pelo menos dois elementos input com o atributo type definido como "checkbox" (caixas de seleção) que sejam descendentes de #survey-form.
Esperando: Todas as caixas de seleção de #survey-form devem ter o atributo value com um valor.
Esperando: Você deve ter pelo menos um elemento textarea descendente de #survey-form.
Esperando: Você deve ter um elemento input ou button com o id "submit".
Esperando: O elemento com o id "submit" deve ter o atributo type definido como "submit".
Esperando: O elemento com o id "submit" deve ser descendente de #survey-form.
