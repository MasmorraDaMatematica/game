A Masmorra da Matemática é um jogo RPG TopDown desenvolvido como recurso didático no ensino da matemática, como parte do trabalho de conclusão de curso de Yuri Rssiguier e Viviane Magalhães Siqueira. O jogo apresenta uma proposta inovadora ao combinar elementos de jogos e tecnologia com o processo de aprendizagem, proporcionando uma experiência envolvente e estimulante para os estudantes. Com gráficos em pixel art e uma jogabilidade dinâmica, os jogadores são desafiados a resolver puzzles e desafios matemáticos para progredir no jogo, fortalecendo seus personagens e adquirindo novas habilidades ao longo do caminho. A Masmorra da Matemática é uma ferramenta educacional que visa tornar o aprendizado da matemática mais divertido e acessível, explorando o potencial dos jogos como uma forma eficaz de ensino.

# **Etapas de desenvolvimento**

## **1 - Criação da arte em pixel art top down no software Aseprite:**

### **1.1 - Criação do cenário:**
Usando o software Aseprite, foram criados os elementos visuais para o cenário do jogo. Isso inclui a concepção de terrenos, paredes, árvores, pedras e outros elementos ambientais necessários para dar vida ao mundo do jogo. O uso da técnica de pixel art topdown permitiu a representação desses elementos de forma simples e reconhecível, mantendo a estética característica desse estilo visual.

![TileMap no Aseprite](https://github.com/MasmorraDaMatematica/img/blob/main/fig1.png?raw=true)

### **1.2 - Criação de Objetos:**
Foram desenvolvidos objetos interativos como baús, portas, chaves e outros itens necessários para a progressão e interação do jogador no jogo. Cada objeto foi criado com atenção aos detalhes em pixel art, garantindo que eles se encaixem harmoniosamente no estilo visual do jogo.

![Objetos no Aseprite](https://github.com/MasmorraDaMatematica/img/blob/main/fig2.png?raw=true)

### **1.3 - Criação de personagens e suas animações:**
Utilizando o Aseprite, os personagens principais e os inimigos foram desenhados em pixel art, capturando suas características físicas, personalidades e habilidades. Além disso, foram criadas animações para os personagens, como caminhar, correr, atacar e interagir, adicionando movimento e expressão ao jogo.

![Personagens e Animações no Aseprite](https://github.com/MasmorraDaMatematica/img/blob/main/fig3.png?raw=true)

### **1.4 - Desenhar a UI:**
A interface do usuário (UI) foi projetada e desenhada em pixel art, considerando elementos como ícones, barras de vida, contador de itens, menus e outros elementos visuais necessários para a interação do jogador com o jogo. A arte em pixel art da UI foi criada com o objetivo de manter a coesão visual com o restante do jogo.

![UI no Aseprite](https://github.com/MasmorraDaMatematica/img/blob/main/fig4.png?raw=true)

## **2 - Criação de cenário e objetos na Unity 2D:**
### **2.1 - Montar o cenário na Unity utilizando tilemaps:**
Após a criação da arte em pixel art no Aseprite, o cenário do jogo foi montado na Unity utilizando a funcionalidade de tilemaps. Os elementos criados anteriormente, como terrenos, paredes e outros objetos, foram posicionados no cenário para formar os ambientes exploráveis do jogo.

![Cenários na Unity utilizando tilemaps](https://github.com/MasmorraDaMatematica/img/blob/main/fig5.png?raw=true)

### **2.2 - Adicionar colisores nos objetos:**
Para permitir a interação física entre os personagens, objetos e o ambiente do jogo, colisores foram adicionados aos objetos na Unity. Esses colisores definem áreas de detecção de colisão, permitindo que os personagens e objetos interajam corretamente com o ambiente e uns com os outros.

![Colisores nos objetos](https://github.com/MasmorraDaMatematica/img/blob/main/fig6.png?raw=true)

### **2.3 - Trabalhar com Animator para criar as animações dos personagens:**
O sistema de animação da Unity, chamado de Animator, foi utilizado para criar as animações dos personagens. As animações criadas no Aseprite foram importadas para a Unity e configuradas no Animator, permitindo a reprodução suave e correta das animações durante o jogo.

![Animator do Personagem](https://github.com/MasmorraDaMatematica/img/blob/main/fig7.png?raw=true)

### **2.4 - Criar scripts para a personagem e os inimigos, assim como os itens interativos:**
Por meio da linguagem de script da Unity, como C#, através da IDE Visual Studio, foram criados scripts para controlar o comportamento dos personagens, inimigos e itens interativos. Esses scripts definem o movimento dos personagens, as interações com os objetos e outros comportamentos específicos para cada elemento do jogo.

![Classe do Personagem](https://github.com/MasmorraDaMatematica/img/blob/main/fig8.png?raw=true)

## **3 - Criar UI:**
### **3.1 - Criar strips para a UI mostrar os contadores, assim como a barra de vida, experiência, etc:**
Com base no design da UI criada anteriormente no Aseprite, foram desenvolvidas as funcionalidades necessárias para exibir os contadores, como itens coletados, quantidade de vida e experiência do jogador. Por meio de scripts na Unity, as informações relevantes são atualizadas e refletidas na UI durante o jogo.

![Scripts para a UI](https://github.com/MasmorraDaMatematica/img/blob/main/fig9.png?raw=true)

### **3.2 - Criar sistema de diálogo com Ink:**
Foi implementado um sistema de diálogo utilizando a ferramenta Ink na Unity. O Ink permite criar ramificações e escolhas no diálogo, proporcionando uma experiência interativa entre o jogador e os personagens do jogo. Isso permitiu a criação de diálogos educativos relacionados aos temas de matemática nas masmorras do jogo.

![Sistema de diálogo com Ink](https://github.com/MasmorraDaMatematica/img/blob/main/fig10.png?raw=true)

## **Pesquisar temas de matemática para criar puzzles e adicionar no jogo:**
Realizou-se uma pesquisa sobre tópicos de matemática adequados ao contexto do jogo. Com base nessa pesquisa, foram desenvolvidos puzzles e desafios matemáticos que o jogador deve enfrentar durante a exploração das masmorras. Esses puzzles educativos ajudam a reforçar conceitos matemáticos e proporcionam uma experiência de aprendizado dentro do jogo.

# **Projeto e Implementação**

### **Mecânica de Questionários e Influência nos Desafios**
A mecânica de questionários no jogo é apresentada ao jogador nas portas que conectam as salas dentro da Masmorra da Matemática. A fim de avançar e atravessar essas portas, o jogador é desafiado a responder corretamente a um questionário. As opções de resposta estão intrinsecamente relacionadas à lógica e aritmética, abrangendo conceitos matemáticos relevantes.

Caso o jogador responda incorretamente ao questionário, os inimigos presentes na masmorra adquirem uma maior força e resistência, tornando-se adversários mais desafiadores e representando um obstáculo adicional. Em contrapartida, ao responder corretamente, os inimigos enfraquecem, facilitando o progresso do jogador no jogo.

![Mecânica de questionários](https://github.com/MasmorraDaMatematica/img/blob/main/fig11.png?raw=true)

### **Desafios de Movimentação Estratégica de Blocos**

Em determinadas salas da Masmorra da Matemática, o jogador encontrará desafios envolvendo a movimentação estratégica de blocos. Nestes momentos, é necessário aplicar a lógica e o raciocínio para deslocar os blocos e avançar no jogo. O jogador possui a habilidade de arrastar os blocos para posições específicas, com o objetivo de bloquear projéteis que representam ameaças.

A movimentação correta dos blocos é fundamental para a proteção do jogador. Se a movimentação for realizada de maneira inadequada, os projéteis podem atingi-lo, causando danos à sua saúde no jogo. Portanto, é necessário utilizar estratégias inteligentes e aplicar o raciocínio lógico para posicionar os blocos de maneira eficiente, garantindo a segurança do personagem.

![Desafio de movimentação de blocos](https://github.com/MasmorraDaMatematica/img/blob/main/fig12.png?raw=true)

### **Desafios Numéricos e Interação com NPCs**

Em algumas salas da Masmorra da Matemática, o jogador encontrará pisos numerados e terá a oportunidade de interagir com um NPC. O NPC fornecerá instruções sobre a sala e conduzirá diálogos que auxiliarão o jogador em sua jornada. Nessas salas, também haverá ativadores posicionados em números específicos, que devem ser evitados pelo jogador.

Quando o jogador atravessa os pisos numerados pelos ativadores, uma armadilha é ativada na sala, resultando em penalidades para o personagem. No entanto, é importante destacar que sempre existem caminhos alternativos disponíveis, nos quais o jogador pode atravessar a sala sem sofrer qualquer penalidade.

A presença dos ativadores adiciona um elemento desafiador ao jogo, exigindo que o jogador seja cauteloso e preste atenção aos números presentes no piso. Essa mecânica busca estimular o raciocínio e a habilidade de observação do jogador, que deve identificar os caminhos seguros para progredir no jogo. Além disso, a interação com o NPC proporciona uma experiência mais imersiva e auxilia na compreensão das instruções e objetivos das salas.

![Desafio numérico e interação com NPC](https://github.com/MasmorraDaMatematica/img/blob/main/fig13.png?raw=true)

### **Design de Interface: Elementos de Controle, Textos e Informações Relevantes**

A interface do jogo foi planejada visando proporcionar uma experiência intuitiva e informativa aos jogadores. Ela engloba uma variedade de elementos de controle, informações e texto, cada um com um propósito específico. Vamos explorar esses componentes em detalhes:

Os *elementos de controle* são botões interativos que permitem aos jogadores executar ações no jogo. Desde correr, atacar e conversar com NPC até se defender de ataques, alterar modos de ataque, pausar o jogo e utilizar poções de vida para recuperar pontos de saúde, esses controles são fundamentais para a jogabilidade e interação dos jogadores.

Os *elementos de texto* desempenham um papel importante durante os diálogos entre o personagem principal e os NPC. Janelas de texto apresentam conversas, instruções e questionários, fornecendo informações cruciais para a compreensão da narrativa e orientação do jogador em suas escolhas e ações.

*Elementos informativos*, por sua vez, são recursos visuais que oferecem informações essenciais sobre o estado do personagem. Indicadores como barras de vida e energia mostram a quantidade restante de cada recurso. O jogador pode acompanhar seu nível de experiência, nível do personagem, quantidade de moedas coletadas, poções disponíveis e chaves de prata e ouro adquiridas ao longo do jogo.

![Elementos de controle da interface](https://github.com/MasmorraDaMatematica/img/blob/main/fig14.png?raw=true)