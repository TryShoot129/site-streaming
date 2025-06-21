# Site de Streaming

Site estático para exibir animes, séries e doramas online, integrado com uma API que lista os títulos atualizados.

## Como publicar no GitHub Pages

1. Faça upload deste repositório no GitHub.

2. Vá até as **Settings** do repositório no GitHub.

3. Na aba **Pages**, configure para publicar a branch `main` na pasta `/root` (ou `master` se for sua branch).

4. Aguarde alguns minutos. O site estará disponível em:
   ```
   https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO/
   ```

## Configurações

- O site faz requisições à API hospedada em:  
  `https://api-titulos.onrender.com/titulos`

- Para trocar a API, edite o arquivo `index.html` no script da função `carregarTitulos`.

## Requisitos

- Navegador moderno com suporte a fetch API e JavaScript.

---

Qualquer dúvida, só abrir issue ou me chamar.