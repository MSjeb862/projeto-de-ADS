# Educa Prime — Site Institucional

## Estrutura do Projeto

- `index.html`: Página inicial com menu e informações institucionais.
- `pais-alunos.html`: Página do setor Pais e Alunos.
- `apoio-pedagogico.html`: Página do setor Apoio Pedagógico.
- `supervisao.html`: Página do setor Supervisão.
- `rh.html`: Página do setor Recursos Humanos (RH).
- `projetos.html`: Página do setor Projetos.
- `contato.html`: Página de contato para suporte, dúvidas e reclamações.
- `styles.css`: Arquivo único de estilos usado por todos os 6 setores.
- `styless.css`: Arquivo único de estilo usado pela página `index.html`.
- `politica-de-privacidade.html`: Página explicando como os dados são tratados.
- `termos-de-uso.html`: Página com regras de uso do site.

## Tecnologias Utilizadas

- HTML5: Estrutura das páginas.
- CSS3: Estilos centralizados em arquivos externos para manter padrão visual.
- Responsividade: Uso de media queries para adaptar o site em telas menores (celulares/tablets).

## Alterações Implementadas

- Novo menu com 6 setores:
  - Pais e Alunos
  - Apoio Pedagógico
  - Supervisão
  - RH
  - Projetos
  - Contato
- Criação de 6 páginas correspondentes, cada uma acessível e clicável a partir do menu.
- CSS unificado: todas as páginas agora usam um único arquivo `styles.css` para facilitar manutenção e garantir padronização visual.
- Responsividade ajustada: o menu muda para coluna quando aberto em telas menores.
- Rodapé padronizado com copyright.
  
---

## [2025-05-08] - Criação da Página de Contato

- Criada a página `contato.html`.
- Decisão: utilizar link direto para WhatsApp e link para envio de e-mail.
- Evita necessidade de servidor/backend.
- Funciona em qualquer celular e navegador.
- Usuário pode escolher entre:
  - Falar via WhatsApp
  - Enviar e-mail para suporte
- Página integrada com o CSS único do projeto.

---

## [2025-05-15] - Inclusão das Páginas de Política de Privacidade e Termos de Uso

- Criadas as páginas `politica-de-privacidade.html` e `termos-de-uso.html`.
- Rodapé atualizado com links para estas páginas.
- Implementação do banner de cookies que aparece na primeira visita do usuário, com opção de aceite via botão.
- Implementado mecanismo via JavaScript usando `localStorage` para armazenar o aceite do usuário, evitando reaparecimento do banner em visitas futuras.

## Motivações e Soluções

- Separar setores: para facilitar a navegação dos usuários e tornar o site modular e escalável.
- Centralizar o CSS: para facilitar futuras alterações. Qualquer modificação visual agora afeta todas as páginas ao mesmo tempo.
- Responsividade: para garantir bom funcionamento tanto em desktops quanto em celulares.
- Acessibilidade: manter uma navegação simples e com contraste adequado.
- Garantir conformidade com LGPD por meio do banner de cookies e termos de uso acessíveis.

## Como Executar a Aplicação Localmente

### Baixe o projeto

Extraia a pasta contendo os arquivos listados abaixo.

Os seguintes arquivos estarão na pasta:

- `index.html`
- `pais-alunos.html`
- `apoio-pedagogico.html`
- `supervisao.html`
- `rh.html`
- `projetos.html`
- `contato.html`
- `styless.css`
- `styles.css`
- `main.js` (JavaScript para o banner de cookies)
- `politica-de-privacidade.html`
- `termos-de-uso.html`

### Abra a página inicial

Clique duas vezes no arquivo `index.html` ou abra com seu navegador preferido (Chrome, Firefox, Edge).

### Navegue entre os setores

Use o menu para acessar cada página setorial. Todas são clicáveis e estão estruturadas.

## Observação

O conteúdo das páginas dos setores está como "Em construção", mas toda a estrutura e navegação já estão funcionando.

Para mudar as cores ou o estilo geral do site, edite os arquivos `styless.css` ou `styles.css`.

---

Desenvolvido para fins acadêmicos — Projeto Educa Prime.

