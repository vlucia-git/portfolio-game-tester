# 🏰 Casos de Teste - Shining Force 1  

Um teste de coragem para garantir que a aventura flua sem falhas!  

---

## 🛡️ **Caso de Teste 01: Movimentação no Grid**  

📜 **Descrição:** Testar se os personagens podem se mover corretamente dentro do grid de batalha.  

| 🆔 ID  | 📝 Passo | ✅ Resultado Esperado | 📊 Status |
|--------|--------------------------------|-------------------------------|-----------|
| **CT-01** | Selecionar um personagem e mover até um local permitido | O personagem se move corretamente | ✔️ Correto |
| **CT-02** | Tentar mover para um local bloqueado (obstáculo) | Movimento deve ser impedido | ✔️ Correto |
| **CT-03** | Tentar mover um personagem sem pontos de movimento restantes | Movimento deve ser negado | ✔️ Correto |

---

## ⚔️ **Caso de Teste 02: Ataque em Combate**  

📜 **Descrição:** Testar o funcionamento dos ataques em combate.  

| 🆔 ID  | 📝 Passo | ✅ Resultado Esperado | 📊 Status |
|--------|----------------------------|-------------------------|-----------|
| **CT-04** | Selecionar um inimigo dentro do alcance e atacar | Ataque ocorre corretamente | ✔️ Correto |
| **CT-05** | Tentar atacar um inimigo fora do alcance | Ataque não deve ser permitido | ✔️ Correto |
| **CT-06** | Verificar se o dano é calculado corretamente | O valor do dano deve corresponder à fórmula do jogo | ✔️ Correto |

---

## 🧠 **IA Inimiga**  

📜 **Descrição:** Verificar o comportamento estratégico dos inimigos.  

| 🆔 ID  | 📝 Caso de Teste | 🎮 Passos | ✅ Resultado Esperado |
|--------|----------------|----------|---------------------|
| **IA-001** | Inimigos atacam quando o jogador está no alcance | Mover personagem para perto de um inimigo e passar o turno | O inimigo deve atacar se estiver dentro do alcance |
| **IA-002** | Inimigos evitam obstáculos corretamente | Posicionar um obstáculo entre o personagem e o inimigo e passar o turno | O inimigo deve encontrar outro caminho ou parar |
| **IA-003** | Inimigos usam magias de forma estratégica | Aproximar-se de um inimigo mago e observar | O inimigo deve usar magias quando for vantajoso |

---

## 📜 **Interface (Menus e Informações)**  

📜 **Descrição:** Testar se menus e informações são exibidos corretamente.  

| 🆔 ID  | 📝 Caso de Teste | 🎮 Passos | ✅ Resultado Esperado |
|--------|----------------|----------|---------------------|
| **UI-001** | Menu de batalha exibe opções corretas | Entrar em batalha e abrir o menu de ação | O menu deve exibir "Atacar", "Magia", "Item", etc. |
| **UI-002** | Status dos personagens estão corretos | Abrir tela de status e comparar atributos | Os valores exibidos devem ser precisos |
| **UI-003** | Inventário exibe os itens corretamente | Adquirir um item e abrir o inventário | O item recém-adquirido deve aparecer |

---

## 🎨 **Gráficos e Som**  

📜 **Descrição:** Verificar animações, efeitos sonoros e música.  

| 🆔 ID  | 📝 Caso de Teste | 🎮 Passos | ✅ Resultado Esperado |
|--------|----------------|----------|---------------------|
| **GS-001** | Animações funcionam corretamente | Movimentar um personagem e observar | As animações devem ser fluídas e sem bugs |
| **GS-002** | Testar áudio das batalhas | Iniciar uma batalha e observar sons | Os efeitos sonoros devem estar corretos |
| **GS-003** | Música muda corretamente entre exploração e combate | Mover-se pelo mapa e entrar em batalhas | A trilha sonora deve alternar conforme esperado |

---

## ⚙️ **Performance (Travamentos, Glitches, FPS)**  

📜 **Descrição:** Garantir que o jogo rode de forma estável.  

| 🆔 ID  | 📝 Caso de Teste | 🎮 Passos | ✅ Resultado Esperado |
|--------|----------------|----------|---------------------|
| **PF-001** | Travamentos ao entrar em batalhas | Caminhar pelo mapa e iniciar batalhas | O jogo deve carregar rapidamente |
| **PF-002** | Estabilidade da taxa de FPS em mapas grandes | Andar por mapas grandes | O FPS deve permanecer estável |
| **PF-003** | Glitches visuais ao alternar menus | Abrir e fechar menus rapidamente | O menu não deve apresentar falhas |

---

💾 **Missão Concluída!** Este plano de testes garantirá que Shining Force 1 esteja pronto para a batalha! ⚔️🏰  
