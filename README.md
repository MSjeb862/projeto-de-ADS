# Home Page — Educa Prime

## Estrutura do Projeto

- `index.html`: Contém a estrutura da página inicial da Educa Prime, com seções como destaque de cursos, informações institucionais, depoimentos e rodapé com contato.
- `styless.css`: Arquivo CSS separado que define todo o estilo visual da página (cores, fontes, layout e responsividade).

## Decisões de Design

- **Separação Estruturada**: HTML limpo e sem estilos inline. Todo o design é controlado pelo CSS externo.
- **Uso de Variáveis CSS**: As cores principais são definidas no seletor `:root`, permitindo fácil troca da paleta de cores. Exemplo:
  - `--primary-color`: preto
  - `--secondary-color`: amarelo
  - `--text-color`: branco
- **Layout Responsivo**: O menu e o layout adaptam-se para telas menores usando media queries.
- **Acessibilidade**: Uso de atributos `aria-label` na navegação para ajudar leitores de tela.
- **Tipografia**: Uso consistente da fonte Arial, com títulos centralizados e textos em negrito para maior destaque.

## Como Executar a Aplicação Localmente

1. **Baixe o Projeto**
   - Salve os arquivos `index.html` e `styless.css` na mesma pasta do seu computador.

2. **Abra a Página**
   - Dê um duplo clique no arquivo `index.html`.
   - Ou clique com o botão direito e selecione "Abrir com" e escolha seu navegador (Chrome, Firefox, Edge, etc).

3. **Visualize Localmente**
   - A página abrirá no seu navegador e funcionará sem necessidade de internet, pois todo o código está local.

## Observação

- Se desejar personalizar as cores, edite as variáveis no início do arquivo `styless.css`:
```css
:root {
    --primary-color:  #000000;
    --secondary-color: #FFC107;
    --text-color: #FFFFFF;
}
