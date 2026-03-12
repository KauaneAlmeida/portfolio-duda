# Duda Castro - Psicologia Infantil

Portfolio profissional desenvolvido para a psicóloga infantil Duda Castro, com foco em uma experiencia visual imersiva e acolhedora.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat&logo=greensock&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)

---

## Sobre o Projeto

Site portfolio criado para apresentar o trabalho da psicóloga infantil Duda Castro. O design busca transmitir acolhimento, leveza e profissionalismo, utilizando uma paleta de cores suave com tons de lavanda e elementos visuais ludicos.

## Funcionalidades

- **Scroll horizontal** com GSAP ScrollTrigger no desktop
- **Scroll vertical** adaptado para dispositivos moveis
- **Animacao de fumaca** com Three.js saindo de uma vela, com palavras relacionadas a psicologia infantil
- **Cursor personalizado** que segue o mouse
- **Nuvens animadas** com movimento autonomo via CSS keyframes
- **Efeito de luz do abajur** que revela texto ao scrollar
- **Cards de portfolio** com animacoes de entrada
- **Layout totalmente responsivo** para mobile e desktop

## Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura semantica |
| CSS3 | Estilizacao, animacoes, responsividade |
| JavaScript | Interatividade e logica |
| GSAP + ScrollTrigger | Scroll horizontal e animacoes de scroll |
| Three.js | Efeito de particulas de fumaca (WebGL) |
| SVG | Ilustracoes vetoriais customizadas |

## Estrutura

```
psicologiainfantil/
├── index.html          # Pagina principal
├── style.css           # Estilos e responsividade
├── img/
│   ├── ilustration.svg # Ilustracao principal
│   ├── flores.svg      # Flores decorativas
│   ├── escalier.svg    # Cena da escadaria
│   ├── rocher.svg      # Cena do rochedo
│   ├── coelhinha.png   # Personagem
│   └── duda*.jpeg      # Fotos do portfolio
└── README.md
```

## Como Executar

1. Clone o repositorio:
```bash
git clone https://github.com/KauaneAlmeida/portfolio-duda.git
```

2. Abra o arquivo `index.html` no navegador.

> Nao requer instalacao de dependencias. Todas as bibliotecas sao carregadas via CDN.

## Responsividade

O site adapta automaticamente o layout conforme o tamanho da tela:

- **Desktop (> 900px):** Scroll horizontal com GSAP, cursor personalizado, efeito de fumaca com Three.js
- **Mobile (< 900px):** Scroll vertical normal, paineis empilhados, portfolio em grid, elementos pesados desativados para performance

## Paleta de Cores

| Cor | Hex | Uso |
|---|---|---|
| Lavanda | `#b8a9f5` | Cor principal, fundos |
| Escuro | `#0d0d0d` | Textos, contrastes |
| Creme | `#f5f0e8` | Textos claros |

---

Desenvolvido por **Isla** com auxilio de IA
