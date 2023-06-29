<hr>
<h2>Histórias de Usuários</h2>
<h3>Formulario-pesquisa</h3>

<img src="images/formulario-pesquisa.png">
<hr>

<h4>Passo 1</h4>
<p>- Você deve ter um elemento h1 com um id "title".</p>
<h4>Passo 2</h4>
<p>- Você deve ter um elemento p com um id "description".</p>
<h4>Passo 3</h4>
<p>>- Você deve ter um elemento form com um id "survey-form".</p>
<h4>Passo 4</h4>
<p>- Dentro do elemento de formulário, você deve ter um campo de input para o nome com um id "name" e o atributo type definido como "text".</p>
<h4>Passo 5</h4>
<p>- Dentro do elemento de formulário, você deve ter um campo de input para o e-mail com um id "email".</p>
<h4>Passo 6</h4>
<p>- Se você inserir um e-mail que não esteja formatado corretamente, verá um erro de validação HTML5.</p>
<h4>Passo 7</h4>
<p>- Dentro do formulário, você pode inserir um número em um campo de input com o id "number".</p>
<h4>Passo 8</h4>
<p>- A entrada numérica não deve aceitar não-números, impedindo que você os digite ou exibindo um erro de validação HTML5 (dependendo do seu navegador).</p>
<h4>Passo 9</h4>
<p>- Se você inserir números fora do intervalo definido pelos atributos min e max, você verá um erro de validação HTML5.</p>
<h4>Passo 10</h4>
<p>- Para os campos de entrada de nome, e-mail e número, você pode ver os elementos label correspondentes no formulário, que descrevem a finalidade de cada campo com os seguintes IDs: "name-label", "email-label" e "number-label".</p>
<h4>Passo 11</h4>
<p>- Para os campos de entrada de nome, e-mail e número, você pode ver o texto do espaço reservado que fornece uma descrição ou instruções para cada campo.</p>
<h4>Passo 12</h4>
<p>- Dentro do elemento de formulário, você deve ter um elemento select com o id "dropdown" e pelo menos duas opções para escolher.</p>
<h4>Passo 13</h4>
<p>- Dentro do elemento de formulário, você pode selecionar uma opção de um grupo de pelo menos dois botões de opção agrupados usando o atributo name.</p>
<h4>Passo 14</h4>
<p>- Dentro do elemento de formulário, você pode selecionar várias opções em uma série de caixas de seleção, cada uma delas deve ter um atributo value.</p>
<h4>Passo 15</h4>
<p>- Dentro do elemento de formulário, você verá um elemento textarea para comentários adicionais.</p>
<h4>Passo 16</h4>
<p> Dentro do elemento de formulário, você verá um botão com o id "submit" para enviar todas as entradas.</p>

<h2>## Testes</h2>

<h4>Passo 1</h4>
<p>Esperando: Você deve ter um elemento h1 com o id "title".</p>
<h4>Passo 2</h4>
<p>Esperando: O elemento h1 com o id "title" não deve estar vazio.</p>
<h4>Passo 3</h4>
<p>Esperando: Você deve ter um elemento p com o id "description".</p>
<h4>Passo 4</h4>
<p>Esperando: O elemento p com o id "description" não deve estar vazio.</p>
<h4>Passo 5</h4>
<p>Esperando: Você deve ter um elemento form com o id "survey-form".</p>
<h4>Passo 6</h4>
<p>Esperando: Você deve ter um elemento input com o id "name".</p>
<h4>Passo 7</h4>
<p>Esperando: O campo de input com o id "name" deve ter o atributo type definido como "text".</p>
<h4>Passo 8</h4>
<p>Esperando: O campo de input com o id "name" deve exigir entrada.</p>
<h4>Passo 9</h4>
<p>Esperando: O campo de input com o id "name" deve ser descendente de #survey-form.</p>
<h4>Passo 10</h4>
<p>Esperando: Você deve ter um elemento input com o id "email".</p>
<h4>Passo 11</h4>
<p>Esperando: O campo de input com o id "email" deve ter o atributo type definido como "email</p>
<h4>Passo 12</h4>
<p>Esperando: O campo de input com o id "email" deve exigir entrada.</p>
<h4>Passo 13</h4>
<p>Esperando: O campo de input com o id "email" deve ser descendente de #survey-form.</p>
<h4>Passo 14</h4>
<p>Esperando: Você deve ter um elemento input com o id "number".</p>
<h4>Passo 15</h4>
<p>Esperando: O campo de input com o id "number" deve ser descendente de #survey-form.</p>
<h4>Passo 16</h4>
<p>Esperando: O campo de input com o id "number" deve ter o atributo type definido como "number".</p>
<h4>Passo 17</h4>
<p>Esperando: O campo de input com o id "number" deve ter o atributo min com um valor numérico.</p>
<h4>Passo 18</h4>
<p>Esperando: O campo de input com o id "number" deve ter o atributo max com um valor numérico.</p>
<h4>Passo 19</h4>
<p>Esperando: Você deve ter um elemento label com o id "name-label".</p>
<h4>Passo 20</h4>
<p>Esperando: Você deve ter um elemento label com o id "email-label".</p>
<h4>Passo 21</h4>
<p>Esperando: Você deve ter um elemento label com o id "number-label".</p>
<h4>Passo 22</h4>
<p>Esperando: O elemento label com o id "name-label" deve conter um texto que descreva a entrada.</p>
<h4>Passo 23</h4>
<p>Esperando: O elemento label com o id "email-label" deve conter um texto que descreva a entrada.</p>
<h4>Passo 24</h4>
<p>Esperando: O elemento label com o id "number-label" deve conter um texto que descreva a entrada.</p>
<h4>Passo 25</h4>
<p>Esperando: O elemento label com o id "name-label" deve ser descendente de #survey-form.</p>
<h4>Passo 26</h4>
<p>Esperando: O elemento label com o id "email-label" deve ser descendente de #survey-form.</p>
<h4>Passo 27</h4>
<p>Esperando: O elemento label com o id "number-label" deve ser descendente de #survey-form.</p>
<h4>Passo 28</h4>
<p>Esperando: O campo de input com o id "name" deve ter o atributo placeholder com um valor.</p>
<h4>Passo 29</h4>
<p>Esperando: O campo de input com o id "email" deve ter o atributo placeholder com um valor.</p>
<h4>Passo 30</h4>
<p>Esperando: O campo de input com o id "number" deve ter o atributo placeholder com um valor.</p>
<h4>Passo 31</h4>
<p>Esperando: Você deve ter um elemento select com o id "dropdown".</p>
<h4>Passo 32</h4>
<p>Esperando: O elemento select com o id "dropdown" deve ter pelo menos duas opções selecionáveis (não desabilitadas).</p>
<h4>Passo 33</h4>
<p>Esperando: O elemento select com o id "dropdown" deve ser descendente de #survey-form.</p>
<h4>Passo 34</h4>
<p>Esperando: Você deve ter pelo menos dois elementos input com o atributo type definido como "radio" (botões de opção).</p>
<h4>Passo 35</h4>
<p>Esperando: Você deve ter pelo menos dois botões de opção descendentes de #survey-form.</p>
<h4>Passo 36</h4>
<p>Esperando: Todos os botões de opção devem ter o atributo value com um valor.</p>
<h4>Passo 37</h4>
<p>Esperando: Todos os botões de opção devem ter o atributo name com um valor.</p>
<h4>Passo 38</h4>
<p>Esperando: Cada grupo de botões de opção deve ter pelo menos 2 botões de opção.</p>
<h4>Passo 39</h4>
<p>Esperando: Você deve ter pelo menos dois elementos input com o atributo type definido como "checkbox" (caixas de seleção) que sejam descendentes de #survey-form.</p>
<h4>Passo 40</h4>
<p>Esperando: Todas as caixas de seleção de #survey-form devem ter o atributo value com um valor.</p>
<h4>Passo 41</h4>
<p>Esperando: Você deve ter pelo menos um elemento textarea descendente de #survey-form.</p>
<h4>Passo 42</h4>
<p>Esperando: Você deve ter um elemento input ou button com o id "submit".</p>
<h4>Passo 43</h4>
<p>Esperando: O elemento com o id "submit" deve ter o atributo type definido como "submit".</p>
<h4>Passo 44</h4>
<p>Esperando: O elemento com o id "submit" deve ser descendente de #survey-form.</p>
