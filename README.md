# Matemática Computacional: materiais interativos

Site estático para o GitHub Pages (Licenciatura em MATD, Iscte Sintra, 2026/2027). Não há passo de
compilação: basta servir esta pasta.

```
index.html                 página inicial (lista de materiais)
slides/
└── residuos/              singularidades, Laurent, resíduos e integrais impróprios
```

Cada conjunto de slides é um único ficheiro `index.html`, sem dependências locais. Para juntar outro,
cria-se `slides/<nome>/index.html` e acrescenta-se um cartão em `index.html`.

## Publicar

Settings → Pages → *Deploy from a branch* → `main` / `(root)`. O site fica em
<https://joaoprijo.github.io/matematica-computacional/>.

## Ver localmente

```bash
python3 -m http.server 8000
```

e abrir <http://localhost:8000>. Abrir o ficheiro com duplo clique também funciona.

As fórmulas usam MathJax 3.2.2, carregado do jsDelivr, e os tipos de letra vêm do Google Fonts, por isso é
preciso ligação à internet.

## Atalhos nos slides

`→` / `←` navegar · `I` índice · `E` modo estudo (mostra todos os passos; é o modo por omissão no
telemóvel) · `F` ecrã inteiro. Cada slide tem endereço próprio, por exemplo
`slides/residuos/#exemplo1`.
