# 🎲 Números Aleatórios - Parte 1 e 2

Este repositório contém exercícios que envolvem **sorteios e números aleatórios**, aplicados a diferentes contextos utilizando **HTML e JavaScript**.

## 📌 Exercícios

### **Parte 1 - Introdução a Números Aleatórios**

1. **Sorteio de Números**  
   - Ao clicar no botão "Sortear", aparece na página um número aleatório entre **0 e 0.9999**.  
   - Se o número for maior que **0.5**, exibe `"Eu arredondaria para 1"`. Caso contrário, `"Eu arredondaria para 0"`.

2. **Sorteio de Time de Futebol**  
   - Ao clicar no botão "Sortear Time", exibe **apenas um dos escudos** dos **4 principais times de São Paulo**.  
   - Todas as imagens devem ter **150px de altura**.

3. **Jogar Dado D20**  
   - Ao clicar no botão "Jogar Dado", sorteia **um dos 20 números** de um dado D20.  
   - O número é exibido em um **quadrado preto**, com fonte branca e centralizada (**100px de largura e altura**).

4. **Sorteio de Nota para Aluno**  
   - Ao clicar no botão "Sortear Nota para aluno", aparece um número aleatório entre **0 e 10**, podendo conter **uma casa decimal**.

5. **Simulação de Pedra, Papel e Tesoura**  
   - Ao clicar no botão "Jogar", aparece aleatoriamente uma **imagem da pedra, papel ou tesoura** (**200px de altura**).  
   - Exibe o resultado e **atualiza o placar**:
     ```
     O jogador 1 venceu!
     Jogador 1: 1 vitória(s)
     Jogador 2: 0 vitória(s)
     ```

6. **Sorteio de Momento do Dia**  
   - Sorteia uma **hora aleatória entre 0 e 23**.  
   - Exibe uma saudação apropriada:
     - `"Bom dia, flor do dia, são Xh!"` (0h - 11h)
     - `"Boa tarde, já vai tarde! São Xh!"` (12h - 17h)
     - `"Boa noite, durma bem! São Xh!"` (18h - 23h)

7. **Número Cabalístico**  
   - Sorteia um número entre **1 e 15**.  
   - Se for **3, 4, 7, 10 ou 12**, exibe `"Eu ❤️ números cabalísticos!"`.  
   - Caso contrário, `"Ah, me dá um número bom na próxima!"`.

8. **Geração de Nota e Frequência do Aluno**  
   - O botão **"Gerar Nota"** sorteia uma **nota entre 0 e 10**.  
   - O botão **"Gerar Frequência"** sorteia uma **frequência entre 0 e 100**.  
   - Todos os valores aparecem com **2 casas decimais**.  
   - O botão **"Ver Situação"** exibe um alerta com a **situação do aluno**.

9. **Verificação de Aprovação do Aluno**  
   - O botão **"Gerar Nota"** sorteia um valor entre **3 e 10**.  
   - O botão **"Gerar Frequência"** sorteia um valor entre **50 e 100**.  
   - Exibe na tela:  
     `"Com nota X e frequência Y, o aluno está Z!"`  
     - `X`: Nota  
     - `Y`: Frequência  
     - `Z`: Situação (**Aprovado** se `nota ≥ 6` e `frequência ≥ 75%`).

---

### **Parte 2 - Jogos e Comparações Avançadas**

10. **Jogo de Dados - Duelo de Jogadores**  
    - Cada jogador sorteia **um dado de 6 lados**.  
    - Ao clicar em `"Comparar Resultados"`, exibe:
      - `"Jogador [1 ou 2] venceu"`, se um deles for maior.
      - `"Empate!"`, se os valores forem iguais.

11. **Sistema de Avaliação de Atendentes**  
    - Sorteia uma **nota aleatória entre 0 e 5**.  
    - Exibe um **emoji correspondente** à avaliação:
      ```
      😢 Muito Triste (0 - 0.5)
      ☹️ Meio Triste (0.5 - 1.5)
      😐 Neutro (1.5 - 3.5)
      😊 Feliz (3.5 - 4.5)
      😁 Muito Feliz (> 4.5)
      ```

12. **Média de Avaliações**  
    - Calcula a **média geral** das avaliações realizadas.  
    - Exibe **nota média + emoji correspondente**.

13. **Sorteio de Temperatura**  
    - Sorteia um valor entre **-20 e +20** e exibe:
      ```
      ❄️ Dá pra conservar qualquer alimento (temperatura < 1)
      🥶 Conserva a maioria dos alimentos (1 - 10)
      🌡️ Estraga a maioria dos alimentos (> 10)
      ```

14. **Fases da Lua**  
    - Sorteia um **dia do mês (1 a 31)** e exibe uma **fase da lua**:
      ```
      🌑 Lua nova (1 - 7)
      🌕 Lua cheia (8 - 16)
      🌗 Lua minguante (17 - 22)
      🌓 Lua crescente (23 - 31)
      ```

15. **Contagem de Números Ímpares e Pares**  
    - Sorteia números entre **-30 e -9**, **atualizando os contadores** de **pares e ímpares**.

16. **Sorteio de Número da Sorte**  
    - Usuário escolhe um número entre **1 e 10** e faz sorteios até acertar.  
    - Exibe mensagem como:  
      `"Parabéns, YYYYYYY, você foi sorteado(a) após X sorteios!"`

17. **Melhoria no Sorteio de Número da Sorte**  
    - Usuário pode escolher **até 3 números** entre **1 e 100**.

18. **Jogo de Dados com Placar**  
    - Sorteia **um número entre 1 e 6** para cada jogador.  
    - Atualiza o **placar acumulativo** de vitórias.  
    - Exibe `"O jogador X está vencendo!"` ou `"O jogo está empatado!"`.

---

## 💻 Tecnologias Utilizadas

- **JavaScript**
- **HTML5**
- **CSS3 (para estilização dos elementos visuais)**

