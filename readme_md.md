# 🏎️ F1 - Pit Wall | GP de São Paulo

O **F1 - Pit Wall** é uma landing page moderna e responsiva voltada para os fãs de Fórmula 1 e entusiastas do Grande Prêmio de São Paulo. O projeto simula a experiência oficial de transmissão e compra de ingressos da F1, apresentando a grade de pilotos, tabela de classificação atualizada e um formulário para reserva de ingressos no Autódromo de Interlagos.

---

## 📸 Demonstração das Funcionalidades

- **Hero Banner Interativo:** Destaque para o evento no Autódromo de Interlagos, estatísticas da pista (distância, voltas e curvas) e botões de navegação rápida (*Call to Action*).
- **Grid de Pilotos:** Cards estilizados com as cores oficiais de cada equipe (Ferrari, Mercedes, Red Bull, McLaren) e efeito de sobreposição das fotos dos pilotos.
- **Tabela de Classificação:** Visualização clara das posições dos pilotos, vitórias e pontuação com design inspirado na transmissão oficial F1 TV, além de controles para busca e filtragem.
- **Reserva de Ingressos:** Seção detalhada com preços por setor (Arquibancada A, Setor da Reta e Box VIP) e formulário completo para solicitação de ingressos.
- **Design Responsivo:** Interface otimizada para telas de computadores, tablets e smartphones.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web fundamentais, sem a dependência de frameworks externos:

- **HTML5:** Estrutura semântica para melhor acessibilidade e SEO.
- **CSS3:**
  - **CSS Grid & Flexbox:** Para a construção de layouts complexos e responsivos.
  - **Variáveis CSS (`:root`):** Gerenciamento centralizado da paleta de cores (incluindo cores das equipes) e tipografia.
  - **Animações e Transições:** Efeitos *hover* suaves nos cards de pilotos, botões e elementos interativos.
  - **Media Queries:** Garantia de adaptação para dispositivos móveis (`@media`).
- **Google Fonts:** Tipografia oficial inspirada no automobilismo (*Titillium Web*).

---

## 📁 Estrutura do Projeto

```text
.
├── index.html          # Estrutura e conteúdo da página
├── style.css           # Estilização completa, variáveis e responsividade
└── img/                # Recursos visuais (Logos, imagens dos pilotos e banners)
    ├── F1-Logo.png
    ├── FerrariLH.jpg
    ├── Charles Leclerc.png
    ├── Lewis Hamilton.png
    ├── Kimi Antonelli.png
    └── verstappen.png
```

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório ou baixe os arquivos:**
   ```bash
   git clone https://github.com/seu-usuario/f1-pit-wall.git
   ```

2. **Navegue até a pasta do projeto:**
   ```bash
   cd f1-pit-wall
   ```

3. **Abra no navegador:**
   - Basta dar um duplo clique no arquivo `index.html` ou utilizar uma extensão como o [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code.

---

## ✍️ Autor

Projeto desenvolvido por **Gabriel Caprari Viezzer** como estudo prático de desenvolvimento web frontend com HTML5 e CSS3.