# fabricio-queiroz.github.io

![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-16233D)
![HTML](https://img.shields.io/badge/HTML-5-5B3B8C)
![CSS](https://img.shields.io/badge/CSS-3-4A5670)

Meu site pessoal — portfolio, habilidades e contato.

**No ar: [fabricio-queiroz.github.io](https://fabricio-queiroz.github.io)**

---

## Sobre

Pagina unica, sem framework e sem build: HTML e CSS escritos a mao, publicados
direto pelo GitHub Pages a partir da branch principal. Nao ha dependencia para
instalar nem etapa de compilacao — o que esta no repositorio e exatamente o que
vai para o ar.

Secoes: apresentacao, sobre mim, habilidades, projetos e contato.

## Estrutura

```
.
├── index.html    marcacao completa da pagina
└── style.css     estilos, incluindo o layout responsivo
```

## Rodar localmente

Abrir o `index.html` no navegador ja funciona. Para servir por HTTP — util para
testar caminhos relativos do jeito que o Pages vai resolver:

```bash
python -m http.server 8000
```

E acessar `http://localhost:8000`.

## Publicacao

Qualquer commit na branch principal e publicado automaticamente pelo GitHub Pages.
A configuracao fica em **Settings → Pages**.

## Licenca

[MIT](LICENSE) — o codigo pode ser reaproveitado. O conteudo pessoal (textos,
foto, dados de contato) e meu.
