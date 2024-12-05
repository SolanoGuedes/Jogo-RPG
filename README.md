# **MVP RPG - Projeto de Jogo RPG 3D/2D**

Este repositório contém o desenvolvimento de um **RPG de combate dinâmico** com mecânicas fluídas, utilizando uma mistura de gráficos 3D e 2D. O objetivo é criar um **MVP (Minimum Viable Product)** para validar o conceito do jogo, que inclui um cenário inicial simples com combate interativo e alguns NPCs. O projeto é realizado utilizando o **Unity** com o template **Universal Render Pipeline (URP)**.

## **Objetivo do Projeto**

O objetivo deste projeto é criar um jogo com um sistema de combate dinâmico onde o jogador pode desviar, rolar e realizar ataques diferentes. A ideia é desenvolver um **MVP** que tenha as funcionalidades básicas e o gameplay essencial para testar as mecânicas de combate e a interação do jogador com o mundo do jogo.

### **Características principais do jogo:**
- **Cenário inicial simples:** Uma pequena vila, uma caverna e/ou dungeon para exploração.
- **Combate dinâmico e interativo:** O jogador pode desviar, rolar e usar ataques diferentes durante o combate com inimigos ágeis.
- **NPCs e missões simples:** Personagens não-jogáveis com missões básicas para o jogador interagir.
- **Gráficos mistos 3D/2D:** O cenário e os personagens serão em 3D, enquanto alguns elementos de combate (como ataques e animações) terão elementos 2D para dar um estilo único ao jogo.


## **Tecnologias e Ferramentas**

- **Unity**: Engine de desenvolvimento de jogos para criar o ambiente 3D e 2D do jogo.
- **C#**: Linguagem de programação usada para implementar a lógica do jogo.
- **Universal Render Pipeline (URP)**: Pipeline gráfico otimizado para suportar uma ampla gama de dispositivos, desde móveis até PCs e consoles.
- **Git**: Sistema de controle de versão utilizado para gerenciar o código e os recursos do projeto.
- **GitHub**: Repositório remoto para armazenamento e colaboração no projeto.

## **Configuração e Instalação**

### **Pré-requisitos**

Antes de começar, verifique se você tem os seguintes requisitos:

- **Unity**: Baixe e instale a versão mais recente do Unity Hub e do editor Unity, preferencialmente a versão que está configurada para este projeto.
- **Git**: Certifique-se de que o Git está instalado em sua máquina. Caso não tenha, pode baixar no [site oficial](https://git-scm.com/).

### **Clone o Repositório**

1. Clone o repositório para sua máquina local:
    ```bash
    git clone https://github.com/SeuUsuario/MVPRPG.git
    ```

2. Abra o projeto no Unity Hub, selecionando o diretório do projeto clonado.

### **Configuração de Controle de Versão (Git)**

O projeto usa **Git** para controle de versão, e arquivos temporários, como pastas `Temp`, `Library`, e `Build`, são ignorados pelo `.gitignore` configurado.

Certifique-se de sempre executar `git status` para verificar se o controle de versão está funcionando corretamente e os arquivos indesejados estão sendo ignorados.

## **Instruções para Contribuição**

Este é um projeto colaborativo! Se você deseja contribuir para o desenvolvimento, siga as etapas abaixo:

1. **Fork** o repositório.
2. Crie uma nova branch para as suas alterações.
    ```bash
    git checkout -b nome-da-branch
    ```
3. Faça suas alterações.
4. Adicione e faça commit das alterações.
    ```bash
    git add .
    git commit -m "Descrição das alterações"
    ```
5. Envie suas alterações para o repositório remoto.
    ```bash
    git push origin nome-da-branch
    ```
6. Crie um **Pull Request** para revisão das alterações.

## **Desenvolvimento**

### **Divisão de Tarefas**

- **Pessoa 1 (Designer/Programador):**
  - Pesquisa e implementação do sistema de combate (movimentação, rolar, desviar, ataques).
  - Criação e implementação dos inimigos ágeis com IA para combate.
  - Pesquisa e implementação de animações (movimentação, ataques, rolar).
  
- **Pessoa 2 (Programador):**
  - Pesquisa e implementação do sistema de NPCs e missões simples.
  - Criação do cenário inicial com uma pequena vila, caverna ou dungeon.
  - Implementação da lógica de interação do jogador com o cenário e NPCs.
  
- **Pessoa 3 (Programador):**
  - Implementação do sistema de controle de versão com Git e Unity.
  - Criação de scripts auxiliares para gerenciar o estado do jogo (início, derrota, vitória).
  - Otimização do projeto para garantir que ele funcione bem em diversas plataformas.

### **Fases do Projeto:**

1. **Fase 1: Configuração inicial do projeto**
   - Criação do projeto no Unity.
   - Configuração do repositório Git e `.gitignore`.
   - Estruturação básica do projeto (cenário inicial, personagem principal).
  
2. **Fase 2: Implementação do combate**
   - Implementação da movimentação básica e sistema de combate.
   - Criação de inimigos e interações no combate (rolar, desviar).
   - Testes de combate para garantir fluidez e interação.

3. **Fase 3: Cenário e NPCs**
   - Criação da vila e da dungeon/caverna.
   - Implementação de NPCs e missões simples.

4. **Fase 4: Ajustes e Refinamento**
   - Correção de bugs.
   - Testes de usabilidade e gameplay.
   - Melhoria nos gráficos e animações.
  
## **Licença**

Este projeto é licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.