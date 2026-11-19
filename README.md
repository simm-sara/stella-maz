# stella-maz

Site da Stella Maz, educadora física: força e fisiologia aplicadas a quem quer treinar por muitos anos. O site é o hub da marca, e o Own Your Pace (guia de corrida) é um dos produtos dentro dele.

É uma página estática, sem build: `index.html` na raiz e as imagens em `img/`.

## Publicar no GitHub Pages

1. No GitHub, abra **Settings → Pages** deste repositório.
2. Em **Build and deployment**, escolha **Source: Deploy from a branch**.
3. Selecione o branch **`main`** e a pasta **`/ (root)`**, e clique em **Save**.
4. Em um ou dois minutos o site fica disponível em `https://simm-sara.github.io/stella-maz/`.

O arquivo `.nojekyll` faz o Pages servir os arquivos como estão, sem processar com Jekyll.

### Domínio próprio (opcional)

1. Em **Settings → Pages → Custom domain**, informe o domínio (por exemplo, `stellamaz.com.br`). O GitHub cria o arquivo `CNAME` no repositório.
2. No provedor do domínio, aponte o DNS para o GitHub Pages, como explica a [documentação do GitHub](https://docs.github.com/pt/pages/configuring-a-custom-domain-for-your-github-pages-site).
3. Marque **Enforce HTTPS** quando a opção aparecer.
4. Troque o endereço nas tags `og:url` e `og:image` do `index.html` pelo domínio novo.

## Estrutura

| Arquivo | O que é |
|---|---|
| `index.html` | O site inteiro: estrutura, estilos e scripts |
| `img/logo-branco.svg` | Logo oficial em branco (topo e rodapé) |
| `img/favicon.svg` | Ícone da aba, feito a partir do símbolo do logo |
| `img/stella-*.jpg` | Fotos da Stella, tratadas em P&B com pretos puxados para o petróleo |
| `img/*.jpg` (demais) | Fotos de banco de imagem (Pexels), provisórias |

## Antes de divulgar o site

Conteúdos que ainda são provisórios no `index.html`:

- [ ] Número de WhatsApp no botão "Começar o aquecimento" (hoje o link é `https://wa.me/` sem número)
- [ ] Links reais do Instagram e do YouTube (topo e contato)
- [ ] Depoimentos: confirmar se são reais ou trocar
- [ ] Planos de acompanhamento (formatos, valores, vagas) e o texto "Presencial ou online"
- [ ] Own Your Pace: turma aberta ou só lista de interesse
- [ ] Seção "Isso funciona?": pelo guia de estratégia, entra no ar só com 3 episódios prontos
- [ ] Fotos reais da Stella no hero, no carrossel do Own Your Pace e na faixa "Ciência, não tendência"
- [ ] Página de política de privacidade (o link do rodapé ainda não leva a lugar nenhum)
