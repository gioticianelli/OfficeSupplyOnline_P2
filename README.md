# OfficeSupply Online — Teste A/B

## O que está implementado
- Versão A (controle) e Versão B (variante).
- Página inicial com área de banner de destaque.
- Navegação funcional entre Início, Kit Escritório e Mouse Ergonômico.
- Página de detalhes própria para o Mouse Ergonômico.
- Ícone de carrinho no cabeçalho com contador de unidades.
- Carrinho funcional via localStorage: adicionar, aumentar/diminuir quantidade, remover itens, limpar carrinho e visualizar total.
- Janela pop-up do carrinho, com fechamento pelo botão, clique fora ou tecla Esc.
- Botões com ícone de carrinho e feedback visual ao passar o mouse.

## Estrutura
- `controle/home.html`: início da versão A.
- `controle/index.html`: detalhe do kit na versão A.
- `controle/mouse.html`: detalhe do mouse na versão A.
- `variante/home.html`: início da versão B.
- `variante/index.html`: detalhe do kit na versão B.
- `variante/mouse.html`: detalhe do mouse na versão B.
- `assets/`: imagens fornecidas.

## Como testar
Abra `index.html` na raiz para escolher A ou B, ou abra diretamente `controle/home.html` / `variante/home.html`.
O carrinho usa armazenamento local do navegador. Para compartilhar o mesmo carrinho entre páginas dentro da mesma versão, mantenha as páginas no mesmo domínio e caminho publicado.

## Publicação
Publique a pasta inteira em GitHub Pages. As URLs previstas serão:
- `https://SEU-USUARIO.github.io/REPOSITORIO/controle/home.html`
- `https://SEU-USUARIO.github.io/REPOSITORIO/variante/home.html`

Substitua `SEU-USUARIO` e `REPOSITORIO` pelos dados reais do GitHub. Ainda é necessário publicar e testar no endereço público.

## Limite do protótipo
O carrinho é funcional no navegador, mas não há checkout, pagamento, estoque ou integração com backend. O clique de compra é armazenado localmente no navegador para demonstração.
