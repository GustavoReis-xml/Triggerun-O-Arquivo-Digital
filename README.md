# Triggerun / 超神狙击: O Arquivo Digital

![Triggerun Digital Archive Banner](https://placehold.co/1200x400/0c0a18/ff0096?text=Triggerun%20Digital%20Archive)

Bem-vindo ao **Arquivo Digital de Triggerun**, um projeto de arqueologia digital dedicado a preservar a história e os recursos do MMOFPS *Triggerun* (versão brasileira) e da sua contraparte original chinesa, *超神狙击 (Chāoshén Zǔjī)*.

Este repositório contém uma aplicação web de página única (SPA) que funciona como um museu interativo, permitindo aos utilizadores explorar o elenco de heróis, os seus cosméticos e a história fragmentada deste jogo esquecido.

**[➡️ Ver Demonstração Ao Vivo (Live Demo)](#)**

---

## 🚀 Funcionalidades

* **Dossiê Interativo de Heróis:** Explore o perfil completo de todos os 23 heróis recuperados, incluindo nomes, origens, classes e habilidades.
* **Galerias Visuais de Cosméticos:** Visualize todas as skins, armas, emotes e poses de cada herói, utilizando os ícones originais do jogo.
* **Arsenal de Personalização:** Navegue por uma galeria completa de avatares de jogador (`userface`) e sprays (`playerpaint`) disponíveis no jogo.
* **Dados Técnicos das Habilidades:** Veja detalhes como o tempo de recarga (`cooldown`) e a duração de cada habilidade, extraídos diretamente dos arquivos de configuração do jogo.
* **Design Responsivo:** A interface foi projetada para ser totalmente acessível em computadores, tablets e telemóveis.
* **Interface Temática:** Um design de inspiração ciberpunk e néon para fazer jus à estética de um *hero shooter* futurista.

---

## 📚 Fontes de Dados

Este projeto só foi possível através da análise meticulosa dos seguintes arquivos de dados do jogo, que serviram como a "Pedra de Roseta" para a reconstrução deste arquivo:

* `heroskillinfo.xml`
* `herounlock.xml`
* `iteminfo.xml`
* `playerskill.xml`
* `ids.txt` (manifesto de recursos completo)

Um agradecimento especial pela disponibilização destes artefactos digitais cruciais.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído como uma aplicação web de página única, sem necessidade de *build steps* ou dependências complexas.

* **HTML5:** Para a estrutura semântica do conteúdo.
* **Tailwind CSS:** Para a estilização e criação de um layout responsivo e moderno.
* **JavaScript (Vanilla JS):** Para toda a lógica de interatividade, manipulação do DOM, filtragem de dados e construção dinâmica dos componentes.
* **Chart.js:** Para a visualização de dados, como o gráfico de distribuição de classes.

---

## ⚙️ Como Utilizar

Como este projeto está contido num único ficheiro `index.html`, não é necessário qualquer processo de compilação.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/triggerun-archive.git](https://github.com/seu-usuario/triggerun-archive.git)
    ```
2.  **Abra o ficheiro:**
    Navegue até à pasta do projeto e abra o ficheiro `index.html` diretamente no seu navegador de preferência (Chrome, Firefox, Edge, etc.).

---

## 🤝 Contribuições

Contribuições para melhorar e expandir este arquivo são bem-vindas! Se tiver mais dados, ficheiros de recursos (`.sds` convertidos, por exemplo) ou correções, sinta-se à vontade para:

1.  Fazer um *Fork* do repositório.
2.  Criar uma nova *Branch* (`git checkout -b feature/sua-melhoria`).
3.  Fazer *Commit* das suas alterações (`git commit -m 'Adiciona funcionalidade X'`).
4.  Fazer *Push* para a sua *Branch* (`git push origin feature/sua-melhoria`).
5.  Abrir um *Pull Request*.

---

