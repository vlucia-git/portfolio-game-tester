# Casos de Teste - Shining Force 1

## 🛡️ Caso de Teste 01: Movimentação no Grid

**Descrição:** Testar se os personagens podem se mover corretamente dentro do grid de batalha.  

| ID    | Passo                                                                  | Resultado Esperado                | Status |
|-------|------------------------------------------------------------------------|-----------------------------------|--------|
| CT-01 | Selecionar um personagem e mover até um local permitido                | O personagem se move corretamente |   ✅  |
| CT-02 | Tentar mover para um local bloqueado (obstáculo)                       | Movimento deve ser impedido       |   ✅  |
| CT-03 | Tentar mover um personagem sem pontos de movimento restantes           | Movimento deve ser negado         |   ✅  |

## ⚔️ Caso de Teste 02: Ataque em Combate

**Descrição:** Testar o funcionamento dos ataques em combate.  

| ID    | Passo                 | Resultado Esperado | Status |
|-------|----------------------|--------------------|--------|
| CT-04 | Selecionar um inimigo dentro do alcance e atacar | Ataque ocorre corretamente | ✅ Passou |
| CT-05 | Tentar atacar um inimigo fora do alcance | Ataque não deve ser permitido | ✅ Passou |
| CT-06 | Verificar se o dano é calculado corretamente | O valor do dano deve corresponder à fórmula do jogo | ✅ |


