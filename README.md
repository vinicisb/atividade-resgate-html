# 🏠 Desafio: Mini Jogo de Navegação em HTML

## 📜 Sobre o Projeto
Este repositório contém o desafio (e futuramente a minha implementação) de um mini jogo de exploração baseado em texto, construído **exclusivamente com HTML**. 

A proposta é criar uma aventura interativa onde o jogador precisa entrar em uma casa virtual e navegar por seus cômodos para localizar um alvo específico (uma pessoa, um tesouro, etc). A interação acontece através de links ou âncoras do HTML, simulando escolhas em cada ambiente.

## 🎯 Objetivo do Jogo
O jogador inicia a aventura do lado de fora da casa (na rua). A cada tela, é apresentado o cômodo atual e as opções de navegação disponíveis (ex: porta, corredor, escada). O jogo termina com sucesso quando o jogador atinge o cômodo de destino predeterminado.

## 📋 Requisitos do Desafio
Para que o desafio seja cumprido, o jogo deve seguir as seguintes regras:
- **Apresentação:** Iniciar sempre apresentando o nome e o objetivo do jogo.
- **Ponto de Partida:** O primeiro espaço/tela deve ser obrigatoriamente a rua (frente da casa).
- **Mapeamento:** Cada rodada deve apresentar o espaço atual e as opções de caminhos, obedecendo a um mapa lógico da casa.
- **Dificuldade:** O jogo **não deve** fornecer dicas explícitas ao jogador, apenas habilitar a navegação pelos espaços.
- **Condição de Vitória:** Ao acessar o cômodo de destino (por padrão, o segundo quarto), o jogo deve exibir uma tela informando que a missão foi concluída com sucesso.

## 🎨 Sugestão de Tema
O tema é livre! Pode ser uma investigação policial, uma casa mal-assombrada, uma caça ao tesouro ou um resgate. 

*Exemplo de narrativa usando o tema de Bombeiros:*
> ### 👨‍🚒 Herói das Chamas
> Você é um bravo bombeiro, sua missão é encontrar o cômodo que ainda tem uma pessoa nessa casa em chamas!
> 
> 🔥 **Depressa! Você está na frente da casa. O que você faz?** 🔥
> - [Entro pela porta](#)
> - [Entro pela janela](#)

## 🚀 Como Jogar
1. Faça o clone deste repositório:
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/vinicisb/atividade-resgate-html)