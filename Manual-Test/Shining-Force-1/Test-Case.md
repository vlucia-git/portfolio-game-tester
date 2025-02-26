# Casos de Teste - Shining Force 1

## 🛡️ Caso de Teste 01: Movimentação no Grid

**Descrição:** Testar se os personagens podem se mover corretamente dentro do grid de batalha.  

| ID    | Passo | Resultado Esperado | Status |
|-------|------------------------------------------------------------------------|-----------------------------------|--------|
| CT-01 | Selecionar um personagem e mover até um local permitido | O personagem se move corretamente | ✅ Correto |
| CT-02 | Tentar mover para um local bloqueado (obstáculo) | Movimento deve ser impedido | ✅ Correto |
| CT-03 | Tentar mover um personagem sem pontos de movimento restantes  | Movimento deve ser negado  | ✅ Correto |

## ⚔️ Caso de Teste 02: Ataque em Combate

**Descrição:** Testar o funcionamento dos ataques em combate.  

| ID    | Passo                 | Resultado Esperado | Status |
|-------|----------------------|--------------------|--------|
| CT-04 | Selecionar um inimigo dentro do alcance e atacar | Ataque ocorre corretamente | ✅ Correto |
| CT-05 | Tentar atacar um inimigo fora do alcance | Ataque não deve ser permitido | ✅ Correto |
| CT-06 | Verificar se o dano é calculado corretamente | O valor do dano deve corresponder à fórmula do jogo | ✅ Correto |

## 🕹️ IA Inimiga  
| ID      | Caso de Teste | Passos | Resultado Esperado |
|---------|--------------|--------|--------------------|
| **IA-001** | Verificar se inimigos atacam quando o jogador está no alcance | 1. Mover personagem para perto de um inimigo <br> 2. Passar o turno | O inimigo deve se mover para atacar, caso esteja dentro do alcance |
| **IA-002** | Testar se inimigos evitam obstáculos corretamente | 1. Posicionar um obstáculo entre o personagem e o inimigo <br> 2. Passar o turno | O inimigo deve encontrar um caminho alternativo ou parar |
| **IA-003** | Verificar se inimigos utilizam magias de forma estratégica | 1. Aproximar-se de um inimigo mago <br> 2. Observar se ele usa magias ao invés de ataques físicos | O inimigo deve usar magias quando for vantajoso |

---

## 📑 Interface (Menus e Exibição de Informações)  
| ID      | Caso de Teste | Passos | Resultado Esperado |
|---------|--------------|--------|--------------------|
| **UI-001** | Testar se o menu de batalha exibe as opções corretas | 1. Entrar em uma batalha <br> 2. Abrir o menu de ação | O menu deve mostrar opções como "Atacar", "Magia" e "Item" corretamente |
| **UI-002** | Verificar se os status dos personagens são exibidos corretamente | 1. Abrir a tela de status <br> 2. Comparar os atributos com os valores esperados | Os valores mostrados devem corresponder aos atributos reais do personagem |
| **UI-003** | Testar se o inventário exibe os itens corretamente | 1. Adquirir um novo item <br> 2. Abrir o menu de inventário | O item recém-adquirido deve aparecer no inventário |

---

## 🎨 Gráficos e Som  
| ID      | Caso de Teste | Passos | Resultado Esperado |
|---------|--------------|--------|--------------------|
| **GS-001** | Testar se as animações dos personagens funcionam corretamente | 1. Movimentar um personagem pelo mapa <br> 2. Observar as animações | As animações devem estar fluídas, sem travamentos ou sprites bugados |
| **GS-002** | Verificar se há problemas de áudio nas batalhas | 1. Iniciar uma batalha <br> 2. Observar os efeitos sonoros dos ataques | Todos os sons devem ser reproduzidos corretamente, sem cortes ou ruídos |
| **GS-003** | Testar se a música muda corretamente entre exploração e batalha | 1. Mover-se pelo mapa <br> 2. Entrar e sair de batalhas repetidamente | A trilha sonora deve alternar corretamente entre os momentos do jogo |

---

## ⚙️ Performance (Travamentos, Glitches, FPS)  
| ID      | Caso de Teste | Passos | Resultado Esperado |
|---------|--------------|--------|--------------------|
| **PF-001** | Verificar se há travamentos ao entrar em batalhas | 1. Caminhar pelo mapa <br> 2. Iniciar diversas batalhas | O jogo deve carregar rapidamente sem quedas bruscas de FPS |
| **PF-002** | Testar a estabilidade da taxa de FPS em mapas grandes | 1. Andar por mapas grandes com vários personagens na tela | O FPS deve permanecer estável, sem quedas perceptíveis |
| **PF-003** | Identificar glitches visuais ao alternar rapidamente entre menus | 1. Abrir e fechar rapidamente o menu principal diversas vezes | O menu não deve exibir falhas gráficas ou travamentos |

---


