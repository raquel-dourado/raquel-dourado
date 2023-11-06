## Testes Automatizados de Login e Carrinho de Compra com Robot Framework

Este projeto contém cenários de testes automatizados para a funcionalidade de login e carrinho de compra usando o Robot Framework.

## Pré-requisitos

Certifique-se de ter as seguintes dependências instaladas em seu ambiente:

- [Python](https://www.python.org/downloads/)
- [Robot Framework](https://robotframework.org/)
- [SeleniumLibrary](https://robotframework.org/SeleniumLibrary/SeleniumLibrary.html) 

Você pode instalar o Robot Framework e a biblioteca SeleniumLibrary usando o pip:

  - pip install robotframework
  - pip install robotframework-seleniumlibrary

## Execução dos Testes

### Para executar os testes de Login e Carrinho de Compra, siga as instruções abaixo:

#### Navegue até o diretório de testes:

- cd testes 

### Execute o teste de Login com o seguinte comando:

- robot -d results_login login.robot

### Execute o teste de Carrinho de Compra com o seguinte comando:

- robot -d results_carrinho carrinho.robot

*** *-d [nome da pasta], serve para que sua estrutura fique mais organizada, levando para uma pasta separada informações de resultado, evidências e log*

### _Os comandos acima executará os testes e fornecerá relatórios no console e em arquivos de saída no diretório output._

## Personalização dos Testes:

Se desejar personalizar os cenários de teste de login ou carrinho de compras, abra os respectivos arquivos .robot de cada funcionalidade, no diretório testes e edite os casos de teste conforme necessário.

## Contribuições:
Contribuições são bem-vindas! 
Sinta-se à vontade para apontar problemas e adicionar melhorias pertinentes ao projeto.





