#  Pilha de Pneus (Tire Stacker)

Um jogo arcade 2D leve, divertido e dinâmico para navegador, desenvolvido puramente em **HTML5, CSS3 e JavaScript (Canvas)**.

Na **Oficina do Zé**, o mecânico do andar de cima arremessa pneus para o térreo. Sua missão é controlar o funcionário na pista, empilhar os pneus antes que caiam no chão e organizar a oficina!

---

## 🎮 Como Jogar

O objetivo principal é montar **10 pilhas de 5 pneus** para arrumar a oficina e vencer o jogo.

### Regras Básicas

* **1 Pilha = 5 Pneus:** Ao completar uma pilha de 5 pneus, você ganha pontos extras e recupera **1 vida** (máximo de 5 vidas).
* **Caiu, Perdeu Vida:** Se um pneu atingir o chão sem ser pego, você perde **1 vida**.
* **Progressão de Nível:** A cada 2 pilhas concluídas, o nível do jogo aumenta:
  * A velocidade do jogo e o ritmo dos arremessos sobem.
  * Do **Nível 3 em diante**, o mecânico passa a jogar pneus de forma mais imprevisível e rápida!

---

## 🕹️ Controles

O jogo foi projetado para jogar no computador via teclado:

* **Mover para a Esquerda:** Tecla `A` ou Seta para a Esquerda `←`
* **Mover para a Direita:** Tecla `D` ou Seta para a Direita `→`
* **Pausar / Despausar:** Tecla `P` ou `ESC`

---

##  Tipos de Pneus

Cada pneu possui propriedades e comportamentos diferentes ao ser coletado:

| Pneu | Cor | Pontos / Valor | Efeito ao Coletar |
| :--- | :--- | :--- | :--- |
| **Normal** | Preto | +10 pts (1 pneu) | Não altera a física. **Limpa** efeitos de escorregão ou lentidão. |
| **Molhado** | Marrom | +10 pts (1 pneu) | Cai devagar, mas deixa o chão ensaboado por 4s (**Escorregando**). |
| **Antigo** | Cinza | +20 pts (2 pneus) | Cai mais rápido e deixa você 40% mais lento por 4s (**Pesado**). |

---

##  Itens e Efeitos Especiais (Power-ups & Traps)

Durante a partida, itens aparecem no chão da oficina. Passe por cima deles para ativar seus efeitos por alguns segundos:

###  Power-ups (Ajudam)
* **Turbo (Amarelo):** Aumenta significativamente sua velocidade de movimento.
* **Ágil (Verde):** Aumenta o controle de movimento, anula escorregões e expande a área de captura dos pneus.

###  Traps / Desafios (Atrapalham)
*  **Graxa (Roxo):** Reduz bastante a velocidade de movimentação.
*  **Terremoto (Vermelho):** O chão e a tela começam a tremer, fazendo o controle do personagem e a trajetória dos pneus oscilarem.

---

##  Tecnologias Utilizadas

* **HTML5:** Estruturação da aplicação.
* **CSS3:** Estilização responsiva, suporte a tema claro/escuro e variáveis CSS.
* **JavaScript (Vanilla JS):**
  * Manipulação da API Canvas 2D (`<canvas>`).
  * Motor de física simples para gravidade, aceleração e colisões.
  * Sistema de partículas e efeitos visuais em tempo real.
  * Renderização prévia de cenários (*offscreen canvas*) para melhor performance.
* **Google Fonts:** Utilização das fontes *Bowlby One* e *Nunito*.

---

## Como Baixar e Jogar

Não é necessária nenhuma instalação, servidores ou softwares adicionais.

1. Clique no botão verde **Code** (no topo desta página do GitHub) e selecione **Download ZIP**.
2. Extraia o arquivo `.zip` baixado em seu computador.
3. Clique duas vezes no arquivo `Pilha de Pneus.html` para abri-lo diretamente no seu navegador padrão (Chrome, Firefox, Edge, Safari, etc.).
4. Divirta-se!
