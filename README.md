
# 🧩 Sudoku Java com Interface Gráfica

Este é um jogo de **Sudoku** desenvolvido em **Java**, apresentando uma interface gráfica intuitiva construída com `javax.swing`. O objetivo é proporcionar uma experiência agradável do clássico jogo de lógica.

## ✨ Funcionalidades

- **Geração de Tabuleiro**: Criação de um tabuleiro 9x9 parcialmente preenchido.
- **Validação de Jogadas**: Verificação em tempo real conforme as regras do Sudoku.
- **Interface Interativa**: Campos editáveis para inserção de números.
- **Botão de Verificação**: Confirma se a solução inserida está correta.
- **Feedback Visual**: Destaque de células com valores inválidos.
- **Reinício de Jogo**: Opção para iniciar um novo jogo a qualquer momento.

## 🛠️ Tecnologias Utilizadas

- **Java 17+**: Linguagem principal do projeto.
- **`javax.swing`**: Biblioteca para construção da interface gráfica.
- **IntelliJ IDEA**: IDE recomendada para execução e desenvolvimento.

## 🚀 Como Executar o Projeto

### 1. Clonar o Repositório

```bash
git clone https://github.com/barbara-dsv/sudoku-java.git
cd sudoku-java
```

### 2. Alternar para a Branch `ui`

O desenvolvimento da interface gráfica está na branch `ui`. Para acessá-la:

```bash
git checkout ui
```

### 3. Abrir no IntelliJ IDEA

1. **Inicie o IntelliJ IDEA**.
2. **Abra o Projeto**: Vá em **File > Open...** e selecione a pasta do projeto clonado.
3. **Configurar SDK**:
    - Navegue até **File > Project Structure > Project**.
    - Certifique-se de que o **Project SDK** está configurado para **Java 17** ou superior.
4. **Aguarde a Indexação**: O IntelliJ irá indexar e sincronizar os arquivos do projeto.

### 4. Executar o Projeto

1. No painel de projeto, navegue até `src/sudoku/UIMain.java`.
2. Clique com o botão direito no arquivo `UIMain.java` e selecione **Run 'UIMain.main()'**.

> **Nota**: A classe `UIMain` é o ponto de entrada para a versão com interface gráfica do jogo.

---

### 🧠 Como Jogar

- O tabuleiro será exibido com alguns números já preenchidos.
- Clique nas **células vazias** e insira números de **1 a 9**.
- Após preencher o tabuleiro, clique no botão **Verificar** para validar sua solução.
- Células com valores incorretos serão **destacadas**.
- Use o botão de **Reiniciar** para gerar um novo tabuleiro e começar novamente.


## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. **Fork** o projeto.
2. **Crie uma Branch**: (`git checkout -b feature/nova-funcionalidade`)
3. **Commit** suas alterações: (`git commit -m 'Adiciona nova funcionalidade'`)
4. **Push** para a branch: (`git push origin feature/nova-funcionalidade`)
5. **Abra um Pull Request**.

## 👩‍💻 Autora

Desenvolvido com 💙 por [@barbara-dsv](https://github.com/barbara-dsv).
