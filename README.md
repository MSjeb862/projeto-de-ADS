# Educa Prime — Site Institucional com Setores

## Estrutura do Projeto

- `index.html`: Página inicial com menu e informações institucionais.
- `pais-alunos.html`: Página do setor Pais e Alunos.
- `apoio-pedagogico.html`: Página do setor Apoio Pedagógico.
- `supervisao.html`: Página do setor Supervisão.
- `rh.html`: Página do setor Recursos Humanos (RH).
- `projetos.html`: Página do setor Projetos.
- `contato.html`: Página de contato para suporte, dúvidas e reclamações.
- `styles.css`: Arquivo único de estilos usado por todos os 6 setores.
- `styless.css`: Arquico único de estilo usado pelo `index.html`

## Tecnologias Utilizadas

- **HTML5**: Estrutura das páginas.
- **CSS3**: Estilos centralizados em um único arquivo para manter padrão visual.
- **Responsividade**: Uso de media queries para adaptar o site em telas menores (celulares/tablets).

## Alterações Implementadas

- **Novo menu com 6 setores**:
  - Pais e Alunos
  - Apoio Pedagógico
  - Supervisão
  - RH
  - Projetos
  - contato
- **Criação de 6 páginas** correspondentes, cada uma acessível e clicável a partir do menu.
- **CSS unificado**: Todas as páginas agora usam um único arquivo `styles.css` para facilitar manutenção e garantir padronização visual.
- **Responsividade** ajustada: o menu muda para coluna quando aberto em telas menores.
- **Footer padronizado** com copyright.

## [2025-05-08] - Criação da Página de Contato

- Criada a página `contato.html`.
- Decisão: Utilizar link direto para WhatsApp e link para envio de e-mail.
  - Evita necessidade de servidor/backend.
  - Funciona em qualquer celular e navegador.
- Usuário pode escolher entre:
  - Falar via WhatsApp
  - Enviar e-mail para suporte
- Página está integrada com o CSS único do projeto.

## Motivações e Soluções

- **Separar setores**: Para facilitar a navegação dos usuários e tornar o site modular e escalável.
- **Centralizar o CSS**: Para facilitar futuras alterações. Qualquer modificação visual agora afeta todas as páginas ao mesmo tempo.
- **Responsividade**: Para garantir bom funcionamento tanto em desktops quanto em celulares.
- **Acessibilidade**: Manter uma navegação simples e com contraste adequado.

## Como Executar a Aplicação Localmente

1. **Baixe o Projeto**
   - Instale a pasta.
   - Os seguintes arquivos estarão na pasta:
     - `index.html`
     - `pais-alunos.html`
     - `apoio-pedagogico.html`
     - `supervisao.html`
     - `rh.html`
     - `projetos.html`
     - `contato.html`
     - `styless.css`
     - `styles.css`

2. **Abra a Página Inicial**
   - Clique duas vezes no arquivo `index.html` ou abra com seu navegador preferido (Chrome, Firefox, Edge).

3. **Navegue Entre os Setores**
   - Use o menu para acessar cada página setorial. Todas são clicáveis e estão estruturadas.

## Observação

- O conteúdo das páginas dos setores está como "Em construção", mas toda a estrutura e a navegação já estão funcionando.
- Para mudar as cores ou o estilo geral do site, edite o arquivo `styless.css` ou `styles.css`.

---

Desenvolvido como projeto institucional da **Educa Prime**.
