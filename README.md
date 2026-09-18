🧮 Calculadora Simples em React
📚 Sobre a atividade
Esta atividade consiste no desenvolvimento de uma calculadora simples utilizando React.

O projeto permite que o usuário informe dois números, escolha uma operação matemática e visualize o resultado. Também possui validações para evitar campos vazios, valores inválidos e divisão por zero.

🚀 Tecnologias utilizadas
React
JavaScript
HTML
CSS
Vite
⚙️ Funcionalidades
A calculadora possui as seguintes operações:

➕ Soma
➖ Subtração
✖️ Multiplicação
➗ Divisão
Além disso, o sistema possui:

Validação dos campos;
Mensagem de erro para valores inválidos;
Verificação de divisão por zero;
Botão para calcular;
Botão para limpar os campos;
Exibição do resultado;
Layout responsivo.
🧠 Conceitos praticados
Durante o desenvolvimento foram utilizados conceitos importantes do React, como:

useState
Eventos com onChange
Eventos com onSubmit
Renderização condicional
Componentização
Manipulação de estados
Funções em JavaScript
Estruturas condicionais switch
Validação de dados
📁 Estrutura do projeto
src/
├── components/
│   ├── FormCalculadora.jsx
│   └── FormCalculadora.css
│
├── App.jsx
└── main.jsx
▶️ Como executar o projeto
Primeiro, instale as dependências:

npm install
Depois, execute o projeto:

npm run dev
O Vite irá disponibilizar um endereço local para acessar a aplicação pelo navegador.

🖥️ Como utilizar
Digite o primeiro número.
Escolha a operação desejada.
Digite o segundo número.
Clique em Calcular.
O resultado será exibido na tela.
Para apagar os valores e realizar uma nova operação, clique no botão Limpar.

❌ Tratamento de erros
A aplicação verifica algumas situações antes de realizar o cálculo:

Campos não preenchidos;
Valores inválidos;
Divisão por zero;
Operação inválida.
Quando ocorre algum erro, uma mensagem é exibida para orientar o usuário.

🎯 Objetivo
O objetivo da atividade é praticar a criação de componentes em React, utilização de estados, eventos, validação de dados e estilização com CSS.

Desenvolvido como atividade acadêmica utilizando React.
