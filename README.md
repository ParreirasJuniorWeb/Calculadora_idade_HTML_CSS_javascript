# Calculadora de Idade
Este é um projeto simples de uma calculadora de idade, construído com **HTML, CSS e JavaScript**. O objetivo é permitir que o usuário insira sua data de nascimento para calcular e exibir sua idade atual.

# Funcionalidades
 - **Cálculo de idade**: Calcula a idade exata do usuário com base na data de nascimento fornecida.

 - **Validação de entrada**: Garante que a data inserida é válida, impedindo idades negativas ou irreais.

 - **Interface amigável**: Design simples e direto para uma experiência de usuário fácil.

# Tecnologias Utilizadas
 - **HTML**: Para a estrutura da página.

 - **CSS**: Para a estilização e responsividade.

 - **JavaScript**: Para a lógica do cálculo e a validação de dados.

# Como Usar
Para usar a calculadora, basta seguir estes passos:

# Clone o repositório:

Bash
```
git clone https://github.com/ParreirasJuniorWeb/Calculadora_idade_HTML_CSS_javascript.git
```
Abra o arquivo:
Abra o arquivo `index.html` em seu navegador de preferência.

# Estrutura do Projeto
O projeto é composto por três arquivos principais:

 - `index.html`: Contém a estrutura da página, com o campo de entrada para a data de nascimento e o botão para calcular.

 - `style.css`: Responsável pela aparência visual da calculadora, incluindo a formatação do layout e os estilos dos elementos.

 - `script.js`: O cérebro do projeto. É aqui que a lógica de cálculo da idade e a validação dos dados de entrada estão implementadas.

# Como o Código Funciona
O código JavaScript (`script.js`) realiza as seguintes operações:

 - **Captura de elementos**: Obtém as referências dos elementos HTML, como o campo de entrada da data e o botão de cálculo.

 - **Função `calculateAge()`**: É a função principal chamada quando o botão é clicado.

 - **Validação**: A função verifica se a data inserida é válida. Se a idade calculada for menor ou igual a zero, ou maior que 100 anos, uma mensagem de erro é exibida.

 - **Cálculo**: Se a data for válida, a função calcula a diferença entre a data atual e a data de nascimento fornecida para determinar a idade.

 - **Exibição do resultado**: A idade calculada é então exibida na interface do usuário.
