# Github Favorites Profiles

## Descrição

Este é um site simples que permite aos usuários buscar e favoritar perfis do Github. Os usuários podem buscar perfis utilizando uma barra de busca e, através da API do Github, obter informações como foto, nickname, quantidade de repositórios, quantidade de seguidores e também habilitar um botão para exclusão do favoritado.

## Funcionalidades

- **Busca de Perfis**: Permite aos usuários buscar perfis do Github utilizando uma barra de busca.
- **Visualização de Informações**: Exibe informações dos perfis buscados, foto, nickname, quantidade de repositórios e quantidade de seguidores.
- **Favoritar Perfis**: Possibilidade de favoritar perfis buscados para fácil acesso posterior.
- **Remover Favoritos**: Opção de remover perfis favoritados.

## Tecnologias Utilizadas

- **HTML**: Estruturação do site.
- **CSS**: Estilização do site.
- **JavaScript**: Funcionalidades dinâmicas e integração com a API do Github.

## Técnicas Utilizadas

1. **Utilização de Orientação a Objeto**:
   - Implementação de classes pai e subclasses para armazenar dados e salvá-los no `localStorage`.
  
2. **Funções Assíncronas com Promessas**:
   - Uso de `try`, `catch` e `throw` para manipulação de erros em operações assíncronas.

3. **Higher-order Functions**:
   - Funções que recebem outras funções.

4. **Respeitando a Imutabilidade dos Dados**:
   - Manipulação de dados sem modificar os objetos originais.

5. **Utilização da DOM**:
   - Manipulação direta do DOM para criação e remoção de elementos.

6. **Criação de Elementos HTML pelo JS**:
   - Criação dinâmica de elementos HTML utilizando JavaScript.

7. **Remoção de Elementos da Tela**:
   - Funções para remover elementos HTML do DOM.

8. **Utilização do Fetch para Buscar um Endpoint**:
   - Uso da API Fetch para realizar requisições HTTP e obter dados da API do Github.
