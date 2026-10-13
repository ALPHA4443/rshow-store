# R SHOW Store — Website

Site-vitrine responsivo e estático da **R SHOW Store**, inspirado na identidade visual e nas informações públicas fornecidas pelo perfil [@rshowstore](https://www.instagram.com/rshowstore/).

## Como usar

Abra `index.html` no navegador. O site funciona sem instalar dependências ou executar um servidor de desenvolvimento. Para hospedar no GitHub Pages, publique o conteúdo deste repositório na branch principal, pasta raiz.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub, por exemplo `rshow-store`.
2. Envie `index.html`, `styles.css`, `script.js` e a pasta `assets` para a raiz do repositório.
3. Vá em **Settings → Pages** e selecione **Deploy from a branch**, branch `main`, pasta `/(root)`.
4. Salve. Após a publicação, o site ficará acessível no endereço informado pelo GitHub Pages.

### Recursos

- Visual mobile/desktop, navegação, animações e layout responsivo.
- Catálogo ilustrativo de 8 modelos, com busca, filtro e ordenação.
- Lista de interesse persistida localmente e botão de copiar consulta para enviar pelo Instagram.
- Seções de diferenciais, perguntas frequentes e links de contato.

## Atenção antes de publicar como loja oficial

**O catálogo é ilustrativo.** A lista de modelos não afirma disponibilidade, preços ou promoções reais. Garanta autorização da loja para uso da marca e substitua textos, condições comerciais, imagens e informações conforme validação do responsável. O carrinho **não** realiza pedidos ou pagamentos. O frete grátis nacional e mais de 4.000 produtos entregues foram informados pelo usuário com base na bio da loja; confirme a redação e as condições vigentes antes de usar comercialmente.

## Estrutura

- `index.html` — página e metadados.
- `styles.css` — design e responsividade.
- `script.js` — catálogo demonstrativo, filtros, carrinho e interações.
- `assets/logo-original.png` — logo fornecida pelo usuário.

Projeto desenvolvido sem framework e sem APIs externas para facilitar publicação em GitHub Pages.