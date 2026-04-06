## Checkpoint

### INFORMAÇÕES DO ALUNO (Individual / Dupla / Trio)

Nome: ________________________________  
RM: _________________________________  

Nome: ________________________________  
RM: _________________________________  


Nome: ________________________________  
RM: _________________________________  


## O Desafio

O desafio é uma releitura do jogo de blackjack, onde o objetivo é processar o vídeo e identificar os valores das cartas de cada jogador. O programa deve ser capaz de ler o vídeo, identificar as cartas e determinar o vencedor da rodada com base nos valores das cartas. 

## Regras gerais

- **CP individual / Dupla / Trio.**
- A prova contém **1 questão**.
- Não é permitido o uso de técnicas de Machine Learning ou Deep Learning para resolver o desafio. 
- Não é permitido o uso de llms ou ferramentas de inteligência artificial (gpt, gemini, claude e outros).
- Não é permitido o uso de tecnicas que não foram estudadas em aula.
- **O objetivo é aplicar os conceitos de visão computacional aprendidos em aula**.
- A estratégia para resolver o desafio deve obrigatóriamente envolver técnicas de visão computacional estudadas em aula para detecção de objetos e reconhecimento de padrões. 


## Saída esperada

A cada frame processado, escreva na tela o valor das cartas de cada jogador. Ao final do vídeo, escreva o nome do jogador vencedor da rodada. O programa deve ser capaz de processar o vídeo e exibir os valores das cartas, bem como determinar o vencedor da rodada com base nos valores das cartas.

## Restrições

- No video podem ocorrer variações na posição, iluminação ou qualidade da imagem.
- `O programa deve funcionar para qualquer video com características semelhantes`.
- O programa deve ser capaz de processar o vídeo e exibir os valores das cartas.
- O programa deve ser capaz de determinar o vencedor da rodada com base nos valores das cartas.

## Rúbrica

1. Nota: 2 - O programa processa o vídeo e exibe corretamente os valores de `pelo menos algumas cartas`.
2. Nota: 4 - O programa processa o vídeo, exibe corretamente os valores de `todas` as cartas e determina o vencedor, mas com algumas imprecisões.
3. Nota: 5 - O programa processa o vídeo, exibe corretamente os valores de `todas` as cartas e determina o vencedor corretamente em todos os casos testados.

---

## Configuração do ambiente

1. **Criar a virtualenv**:

   ```bash
   python -m venv venv
   ```

2. **Ativar o ambiente**:

   - macOS / Linux:

     ```bash
     source venv/bin/activate
     ```
   - Windows:

     ```bash
     venv\Scripts\activate.bat
     ```

3. **Instalar as dependências**:

   ```bash
   pip install -r requirements.txt
   ```

## Testar a infraestrutura

- Execute o script de exemplo:

  ```bash
  python main.py
  ```
  Uma janela mostrará a transmissão da câmera. Pressione `q` para sair. Como pode observar, o arquivo `main.py` já carrega um video, mas não estão fazendo nada.
