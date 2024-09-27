
# Atletas do Brasil

Este projeto é uma aplicação simples que permite aos usuários pesquisar informações sobre atletas brasileiros. A pesquisa é realizada com base no nome do atleta ou em palavras-chave relacionadas à sua descrição.

## Funcionalidades

- Campo de pesquisa para encontrar atletas com base no nome ou descrição.
- Resultados dinâmicos exibidos na página, conforme o texto de busca.
- Exibição de links para mais informações sobre o atleta.

## Tecnologias Utilizadas

- **HTML**: Estrutura básica do site.
- **CSS**: Estilização visual (não incluído neste exemplo, mas referenciado no arquivo `style.css`).
- **JavaScript**: Lógica de pesquisa e exibição dos resultados dinâmicos.
- **JSON (dados.js)**: Simula um banco de dados com informações sobre atletas (não incluído neste exemplo).

## Arquivos

- **index.html**: Página principal com o layout básico e elementos de interação (pesquisa e exibição de resultados).
- **style.css**: Arquivo de estilo para personalizar a aparência da página.
- **app.js**: Script de lógica de pesquisa e manipulação dos resultados.
- **dados.js**: Contém os dados dos atletas, como nome, descrição e links para mais informações (não incluído no exemplo, mas necessário para o funcionamento).

## Como Funciona

1. O usuário digita o nome de um atleta ou uma palavra-chave no campo de pesquisa.
2. Ao clicar no botão "Pesquisar", a função `pesquisar()` é acionada.
3. O sistema faz a correspondência entre o texto de busca e os dados dos atletas (provenientes de `dados.js`).
4. Se houver correspondência, os resultados são exibidos dinamicamente na seção de resultados; caso contrário, uma mensagem informando que nenhum resultado foi encontrado será mostrada.

## Como Usar

1. Clone o repositório.
2. Certifique-se de que todos os arquivos estejam na mesma pasta:
   - `index.html`
   - `style.css`
   - `app.js`
   - `dados.js` (a ser criado)
3. Abra o arquivo `index.html` em um navegador da web.

### Exemplo de dados.js

Aqui está um exemplo de como o arquivo `dados.js` poderia ser estruturado:

```javascript
const dados = [
  {
    titulo: "Rebeca Andrade",
    descricao: "Rebeca Andrade é uma das maiores ginastas brasileiras de todos os tempos.",
    link: "https://exemplo.com/rebeca-andrade"
  },
  {
    titulo: "Gabriel Medina",
    descricao: "Gabriel Medina é um surfista brasileiro, bicampeão mundial de surfe.",
    link: "https://exemplo.com/gabriel-medina"
  }
];
```

## Licença

Este projeto é licenciado sob os termos da licença MIT.
```

Este `README.md` fornece um guia claro e simples sobre como o projeto funciona, quais tecnologias são usadas e como ele pode ser executado.
