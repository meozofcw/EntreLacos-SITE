# Site EntreLaços — Como publicar

## Arquivos necessários

Coloque estes 3 arquivos na **mesma pasta**:

```
index.html   ← já incluso
logo.png     ← logo do EntreLaços (fundo transparente)
arandu.png   ← logo da Arandu LABS (fundo transparente)
```

Sem esses dois PNGs na pasta, os espaços das logos no cabeçalho, na seção
"Quem fez" e no rodapé aparecem quebrados (ícone de imagem ausente).

## Onde editar texto

Tudo está em `index.html`, em português, sem nenhum framework — é só abrir
no bloco de notas ou em qualquer editor de código e editar o texto entre as
tags. Não precisa rodar nenhum build.

## Como publicar gratuitamente

**Opção mais simples — GitHub Pages**, já que o projeto já está no GitHub:

1. Suba os 3 arquivos (`index.html`, `logo.png`, `arandu.png`) para uma pasta
   `/docs` no repositório, ou para um repositório novo só para o site.
2. No GitHub, vá em **Settings → Pages**.
3. Em "Source", selecione a branch `main` e a pasta `/docs` (ou `/root`).
4. Salve. Em alguns minutos o site estará no ar em um link como:
   `https://meozofcw.github.io/EntreLacos/`

Esse link é o que você coloca na bio do Instagram/perfil do app.

## Seções do site

1. **Hero** — frase de impacto + mockup do app
2. **Sobre / Problema** — 4 dores que o app resolve
3. **Funcionalidades** — Comunidade, Oportunidades, Rede de Apoio, Espaço Sensorial
4. **Premium** — benefícios e os 3 planos
5. **Tecnologia** — stack usada
6. **Identidade visual** — paleta de cores
7. **Impacto social**
8. **Equipe** — crédito à Arandu LABS e ao DLJ4
9. **FAQ** — respostas às dúvidas do vídeo pitch
10. **CTA final + rodapé**