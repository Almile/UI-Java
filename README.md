# Sistema de Cadastro e Configuração de Preferências

## Descrição do Projeto

Este projeto contém dois exercícios desenvolvidos em Java utilizando a biblioteca Swing para a construção de interfaces gráficas (UI). O objetivo é aplicar conceitos de orientação a objetos e manipulação de componentes de interface gráfica em Java, como JLabel, JTextField, JRadioButton, JComboBox, entre outros.

### Exercício 1: Sistema de Formulário de Cadastro

Neste exercício, o foco é criar um sistema de cadastro simples com validação de campos. O formulário captura informações de **Nome**, **Idade** e **Sexo** e exibe o resumo dos dados inseridos na tela após o envio.

#### Funcionalidades:

- **Componentes usados:**
  - `JLabel`: Para os títulos "Nome", "Idade" e "Sexo".
  - `JTextField`: Para inserir o nome.
  - `JSpinner`: Para selecionar a idade.
  - `JRadioButton`: Duas opções para selecionar o sexo (masculino ou feminino).
  - `JButton`: Para enviar os dados.

- **Validação:**
  - O sistema garante que todos os campos sejam preenchidos antes de permitir a submissão.
  
- **Resumo:**
  - Os dados capturados são exibidos em um `JLabel` adicional como um resumo das informações preenchidas.

### Exercício 2: Ferramenta de Configuração de Preferências

Este exercício envolve a criação de uma ferramenta de configuração de preferências do usuário. As configurações incluem o tema da interface, ativação de notificações e controle de volume.

#### Funcionalidades:

- **Componentes usados:**
  - `JLabel`: Para os títulos "Tema", "Notificações" e "Volume".
  - `JComboBox`: Para selecionar o tema ("Claro" ou "Escuro").
  - `JCheckBox`: Para habilitar ou desabilitar notificações.
  - `JSlider`: Para ajustar o volume de 0 a 100.
  - `JButton`: Para salvar as preferências.
  - `JTextArea`: Para exibir as preferências salvas.

- **Persistência Temporária:**
  - As configurações são mantidas até o fechamento do programa.
  
- **Alteração de Tema:**
  - A cor do `JFrame` é alterada conforme o tema selecionado.

### Estrutura do Projeto

- **Cliente**: Classe que representa o usuário que se cadastra no sistema. Recebe os dados do formulário.
- **CadastroForm**: Classe que contém os componentes e lógica do formulário de cadastro.
- **Usuário**: Classe que armazena as preferências do usuário.
- **PreferenciasUsuario**: Classe que contém os componentes e lógica da ferramenta de configuração de preferências.

### Tecnologias Utilizadas:

- Java SE
- Swing

## Como Executar

1. Clone o repositório:
   ```bash
   git clone <link-do-repositorio>
   ```
2. Compile as classes:
   ```bash
   javac *.java
   ```
3. Execute o projeto:
   ```bash
   java Main
   ```

