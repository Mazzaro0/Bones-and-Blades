### Prefabs

---

#### Kael (Personagem Principal)

- **Nome:** Kael  
- **Descrição:** Guerreiro controlado pelo jogador. Luta contra esqueletos e coleta moedas.  
- **Quando são utilizados:** Desde o início do jogo até a morte ou vitória.  
- **Quais seus componentes:**  
  - **Sprites:** Animações de andar, pular, atacar e tomar dano  
  - **Colisores:** BoxCollider2D para interações com inimigos, moedas e ambiente  
  - **Fontes de audio:** Som de espada, pulo, dano e morte  
  - **Scripts:**  
    - Controle de movimento  
    - Sistema de combate  
    - Sistema de vida  

---

#### Esqueleto Inimigo

- **Nome:** Esqueleto  
- **Descrição:** Inimigo comum que causa dano ao jogador.  
- **Quando são utilizados:** Espalhados pelo cenário ao longo da fase.  
- **Quais seus componentes:**  
  - **Sprites:** Andando, atacando, morrendo  
  - **Colisores:** BoxCollider2D para dano e colisão  
  - **Fontes de audio:** Som de ataque e morte  
  - **Scripts:**  
    - Movimento automático  
    - Ataque ao jogador  
    - Morte ao perder vida  

---

#### Moeda Mística

- **Nome:** Moeda  
- **Descrição:** Item coletável que aumenta a pontuação e dificuldade.  
- **Quando são utilizados:** Posicionadas em locais estratégicos no mapa.  
- **Quais seus componentes:**  
  - **Sprites:** Animação de rotação/brilho  
  - **Colisores:** Trigger para coleta  
  - **Fontes de audio:** Som ao coletar moeda  
  - **Scripts:**  
    - Aumenta pontuação  
    - Aumenta dificuldade com base nas moedas coletadas  

---

#### Tile de Plataforma

- **Nome:** Tile  
- **Descrição:** Blocos utilizados para formar o terreno e obstáculos.  
- **Quando são utilizados:** Construção de mapas e cenários.  
- **Quais seus componentes:**  
  - **Sprites:** Texturas de chão, pedras, paredes  
  - **Colisores:** BoxCollider2D para impedir atravessamento  
  - **Fontes de audio:** Não possui  
  - **Scripts:** (opcional) Para eventos como plataformas móveis  

---

#### HUD de Vida

- **Nome:** Barra de Vida  
- **Descrição:** Interface que mostra a vida atual do jogador.  
- **Quando são utilizados:** Durante todo o gameplay.  
- **Quais seus componentes:**  
  - **Sprites:** Ícones ou barras visuais  
  - **Colisores:** Não se aplica  
  - **Fontes de audio:** (opcional) Som ao perder vida  
  - **Scripts:**  
    - Atualiza visualmente a vida com base no valor atual  
