# Link na bio | Raphael Almeida Castro

Página de links no estilo Linktree para usar na bio das redes sociais. Reúne Instagram, LinkedIn e GitHub, o curso atual e os focos de aprendizado, com visual preto e azul-marinho e efeito de vidro translúcido inspirado no iOS.

## Recursos

- Foto de perfil circular com anel azul
- Banners para Instagram, LinkedIn e GitHub
- Seções de curso atual e focos de aprendizado
- Efeito de vidro (`backdrop-filter`) sobre fundo com manchas de azul
- Layout responsivo, pensado para celular
- Sem frameworks nem dependências: só HTML, CSS e JavaScript

## Estrutura

```
.
├── index.html
├── style.css
├── script.js
├── assets/
│   └── foto-perfil.jpg
└── README.md
```

## Como rodar localmente

Abra o arquivo `index.html` no navegador. Se preferir um servidor local, use a extensão Live Server do VS Code ou rode:

```bash
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Como personalizar

- **Textos e links:** edite o `index.html`. Cada banner é um bloco `<a class="glass link">` com o `href` da rede.
- **Foto:** troque `assets/foto-perfil.jpg` por outra imagem quadrada, de preferência com 400 px ou mais.
- **Cores:** no `style.css`, ajuste as manchas de fundo (`.o1`, `.o2`, `.o3`), o anel do avatar (`.avatar`) e as variáveis em `:root`.
- **Intensidade do vidro:** altere o valor de `blur()` na classe `.glass`.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie os arquivos:

   ```bash
   git init
   git add .
   git commit -m "feat: página link na bio"
   git branch -M main
   git remote add origin https://github.com/Raphael-Cas/NOME-DO-REPOSITORIO.git
   git push -u origin main
   ```

2. No repositório, vá em **Settings > Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e salve.
4. Em alguns minutos o site estará em `https://raphael-cas.github.io/NOME-DO-REPOSITORIO/`.

Se o repositório se chamar `Raphael-Cas.github.io`, o endereço fica só `https://raphael-cas.github.io/`. Cole o link final na bio do Instagram e do LinkedIn.

## Tecnologias

HTML5, CSS3 e JavaScript puro.

## Autor

**Raphael Almeida Castro**
[LinkedIn](https://www.linkedin.com/in/raphael-almeida-castro/) | [Instagram](https://www.instagram.com/1raphael.castro/) | [GitHub](https://github.com/Raphael-Cas)
