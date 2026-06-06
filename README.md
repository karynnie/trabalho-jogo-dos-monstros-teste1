# ⚔️ Dungeon Crawler

> Jogo de dungeon crawler desenvolvido em linguagem C, com interface inteiramente no terminal via caracteres ASCII.

Desenvolvido como projeto final da disciplina de Programação — Curso de Ciência da Computação.

---

## 👥 Desenvolvedores

- Wanderlei Neto
- Karynnie Vitoria
- Victor Yamada

---

## 📖 História

Em um reino esquecido pelos mapas, existe uma vila que vive sob a sombra de uma antiga masmorra. Criaturas sombrias emergem de suas profundezas, aterrorizando os moradores há décadas.

Você é um aventureiro que chega à vila sem nome em busca de glória. A anciã do vilarejo te entrega uma arma e aponta para a entrada da masmorra:

> *"Três andares. Cada um mais sombrio que o anterior. No fundo... o Senhor das Sombras. Muitos tentaram. Nenhum voltou."*

Derrote o Boss Final e liberte o reino.

---

## 🎮 Como Jogar

**Objetivo:** explorar os três andares da masmorra e derrotar o Boss Final.

| Tecla | Ação |
|-------|------|
| `W` | Mover para cima |
| `A` | Mover para a esquerda |
| `S` | Mover para baixo |
| `D` | Mover para a direita |
| `I` | Interagir com objeto à frente |
| `O` | Atacar a célula à frente |

> ⚠️ Não há movimentação diagonal.

### Vidas

O jogador possui **3 vidas**. Perder uma vida reinicia a fase do início. Perder todas as 3 exibe a tela de Game Over e retorna ao menu principal.

---

## 🗺️ Estrutura do Jogo

| Local | Tamanho | Descrição |
|-------|---------|-----------|
| 🏘️ Vila | 10 × 10 | Área inicial. Converse com o NPC e escolha sua arma. |
| 🏚️ 1° Andar | 10 × 10 | Tutorial: movimentação, chaves, portas e caixas destruíveis. |
| 🕳️ 2° Andar | 15 × 15 | Apresenta espinhos, botões e o Monstro Tipo 1. |
| 💀 3° Andar | 25 × 25 | Desafio final com o Boss e todos os elementos anteriores. |

---

## ⚔️ Armas

Escolhidas ao interagir com o NPC da Vila. A arma persiste por toda a partida.

| Arma | Área de Ataque |
|------|----------------|
| ⚔️ Espada | Região 3×2 diretamente à frente do jogador |
| 🏹 Arco e Flecha | 4 células em linha reta à frente |
| 🪄 Cajado | Todas as 8 células adjacentes ao jogador |

---

## 🔣 Símbolos do Mapa

| Símbolo | Significado |
|---------|-------------|
| `<` | Jogador olhando para a esquerda |
| `^` | Jogador olhando para cima |
| `>` | Jogador olhando para a direita |
| `v` | Jogador olhando para baixo |
| `*` | Parede (intransponível) |
| `#` | Espinho (morte instantânea ao pisar) |
| `k` | Caixa (bloqueia passagem, destruível com ataque) |
| `O` | Botão (executa ação ao ser pressionado) |
| `D` | Porta fechada (requer chave) |
| `@` | Chave (abre porta fechada ao interagir) |
| `=` | Porta aberta (passável) |
| `L` | Escada (avança para o próximo andar) |
| `X` | Monstro Tipo 1 — movimento aleatório |
| `Y` | Monstro Tipo 2 — persegue o jogador |
| `Z` | Boss Final |

---

## 🤖 Uso de IA Generativa

O projeto utilizou ferramentas de IA generativa como apoio ao aprendizado, para esclarecimento de dúvidas sobre sintaxe, lógica e depuração de código em C. Todo o código foi compreendido e implementado pelos integrantes da equipe.
