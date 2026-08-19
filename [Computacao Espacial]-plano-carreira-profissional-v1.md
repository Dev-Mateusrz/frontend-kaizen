# Plano de Carreira — Computação Espacial

> Roadmap de longo prazo para alguém começando do zero em programação, com pouca confiança em matemática, e que quer chegar profissionalmente a **Computação Espacial / XR (AR, VR e MR)**.

---

## 0. Log de atualizações

**12/08/2026** — Primeira rodada de pesquisa real incorporada ao roadmap:

- adicionada a plataforma **Android XR** (Google + Samsung + Qualcomm, lançada em out/2025, suporta OpenXR nativamente) às referências e ao panorama de mercado;
- adicionada trilha de **certificações oficiais da Unity** (User → Associate → Professional), com destaque para o track "VR Developer" como marco intermediário verificável;
- nova seção de **mercado de trabalho e cargos intermediários** (Brasil e remoto), com faixas salariais reais e empresas-alvo;
- nova seção de **formação complementar** (cursos pagos vs. gratuitos, pós-graduação reconhecida pelo MEC);
- livro de matemática 3D já indicado no roadmap (seção 7) confirmado pela pesquisa como a escolha certa: *3D Math Primer for Graphics and Game Development* (Dunn & Parberry).

---

## 1. Objetivo principal

Tornar-se um profissional capaz de desenvolver aplicações de **Computação Espacial**, dominando progressivamente:

- programação;
- engenharia de software;
- matemática aplicada a 3D;
- computação gráfica em tempo real;
- Unity e C#;
- XR (VR, AR e MR);
- OpenXR;
- rastreamento espacial;
- âncoras e persistência espacial;
- oclusão e profundidade;
- interação por controladores, mãos, olhar e gestos;
- otimização de aplicações 3D/XR;
- fundamentos de visão computacional e IA;
- ao menos uma plataforma/ecossistema de especialização.

O alvo profissional final pode aparecer com títulos como:

- **XR Developer**
- **XR Software Engineer**
- **Spatial Computing Developer**
- **Spatial Computing Engineer**
- **AR/VR Developer**
- **Immersive Technology Developer**
- **Mixed Reality Developer**

---

# 2. Estratégia geral

Este plano não tenta ensinar tudo ao mesmo tempo.

A ordem principal será:

**Programação → Engenharia de Software → Matemática para 3D → Unity/3D → XR → AR/MR → Computação Espacial avançada → Especialização**

A stack principal sugerida para começar será:

**C# + Unity**

Depois entram:

**Git → Matemática 3D → XR Interaction Toolkit → OpenXR → AR Foundation → ARCore/ARKit**

Somente depois de uma base sólida entram tecnologias como:

- C++;
- Unreal Engine;
- Swift;
- visionOS;
- Python;
- visão computacional;
- machine learning;
- shaders avançados;
- networking/multiusuário.

A regra é simples:

> **Primeiro profundidade em uma stack. Depois amplitude.**

---

# 3. Horizonte de tempo

Este roadmap foi pensado para aproximadamente **4 a 6 anos de evolução consistente em tempo parcial**.

Isso não significa que você precise esperar 4 anos para criar projetos ou tentar oportunidades.

Você começará a produzir projetos desde os primeiros meses.

Uma referência razoável de estudo é:

- **8 a 12 horas por semana:** ritmo sustentável;
- **12 a 20 horas por semana:** ritmo acelerado;
- abaixo disso: o roadmap continua válido, apenas leva mais tempo.

## Sua disponibilidade real (2º semestre de 2026)

**Estágio (SMS-Rio):** segunda, quarta e sexta das 10h às 19h; terça e quinta das 10h às 16h.

**Faculdade (turno manhã):** só duas disciplinas têm horário fixo presencial — quinta-feira das 8h40 às 11h20, e sexta-feira das 9h20 às 11h. As outras três (Modelagem em UML, Sistemas Operacionais, Paradigmas de Linguagens) são on-line, sem horário marcado, mas ainda exigem tempo de estudo.

⚠️ **Ponto de atenção:** quinta e sexta têm sobreposição de horário entre aula e estágio, mas de tipos diferentes:
- **Quinta** é aula **presencial** na MC-708 (10h–11h20 de sobreposição) — conflito real de estar em dois lugares ao mesmo tempo. Precisa de solução com a coordenação/orientador de estágio.
- **Sexta** é aula **remota, via Teams** (10h–11h de sobreposição) — potencialmente contornável se der pra acompanhar a aula de dentro do estágio (fone/notebook), desde que a SMS-Rio permita. Vale confirmar isso, mas o problema é bem menor que o de quinta.

**Conta realista de horas livres pro roadmap:** terça à tarde/noite (a partir das 16h) e sábado são os blocos mais confiáveis; quinta à noite rende um pouco a mais depois de resolvido o conflito de horário. Isso dá algo entre **6h30 e 8 horas por semana** — na faixa de baixo do ritmo sustentável acima, o que é esperado com estágio quase em tempo integral + faculdade rodando junto.

**Marco no calendário:** a faculdade termina em junho de 2027. A partir daí a ideia é entrar numa pós e dedicar bem mais tempo ao roadmap — isso deve liberar boa parte da carga horária que hoje está com a faculdade.

O avanço deve ser decidido principalmente pelos **critérios de domínio**, e não apenas pelo calendário.

---

# 4. Visão geral da trajetória

| Etapa | Período aproximado | Foco |
|---|---:|---|
| Fase 0 | 0–2 meses | Preparação e lógica |
| Fase 1 | 2–8 meses | C# e programação |
| Fase 2 | 2–18 meses | Matemática aplicada em paralelo |
| Fase 3 | 8–16 meses | Engenharia de software |
| Fase 4 | 12–24 meses | Unity e desenvolvimento 3D |
| Fase 5 | 20–32 meses | XR e OpenXR |
| Fase 6 | 28–40 meses | AR, ambiente físico e persistência |
| Fase 7 | 36–48 meses | Engenharia de Computação Espacial |
| Fase 8 | 42–60+ meses | Especialização profissional |
| Contínuo | Sempre | Portfólio, inglês, Git e projetos |

Os períodos se sobrepõem de propósito.

---

# 5. Fase 0 — Começar do zero

**Duração estimada: 1 a 2 meses**

## Objetivo

Aprender como um computador executa instruções e perder o medo de código.

## Aprender

### Fundamentos de computação

- arquivos e pastas;
- extensões de arquivos;
- instalação de programas;
- terminal básico;
- caminhos de arquivos;
- processos;
- diferença entre memória RAM e armazenamento;
- noção de CPU e GPU;
- compilação;
- execução de programas;
- editor de código;
- IDE.

### Lógica de programação

Aprender:

- algoritmo;
- variável;
- constante;
- tipo;
- operador;
- condição;
- repetição;
- função;
- parâmetro;
- retorno;
- entrada e saída;
- estado de um programa.

## Tecnologia

Começar diretamente com:

**C#**

Não é necessário aprender Python antes de C#.

Python poderá entrar posteriormente para IA e visão computacional.

## Projetos

Criar pequenos programas de terminal:

1. calculadora;
2. conversor de temperatura;
3. sistema de notas;
4. contador;
5. jogo de adivinhação;
6. lista simples de tarefas;
7. cronômetro ou temporizador.

## Critério para avançar

Você deve conseguir criar sozinho um pequeno programa utilizando:

- variáveis;
- `if`;
- `switch`;
- `for`;
- `while`;
- funções;
- listas básicas.

---

# 6. Fase 1 — Programação com C#

**Duração estimada: meses 2 a 8**

## Objetivo

Transformar lógica básica em capacidade real de programar.

## C# — Fundamentos

Estudar:

- tipos primitivos;
- strings;
- operadores;
- conversões de tipo;
- arrays;
- listas;
- dicionários;
- métodos;
- escopo;
- classes;
- objetos;
- propriedades;
- construtores;
- encapsulamento;
- herança;
- interfaces;
- enums;
- exceptions;
- generics;
- delegates;
- events;
- LINQ básico;
- leitura e escrita de arquivos;
- debugging.

## Programação orientada a objetos

Entender muito bem:

- classe;
- objeto;
- responsabilidade;
- composição;
- encapsulamento;
- interface;
- dependência.

Não tente decorar padrões de projeto nesta etapa.

## Estruturas de dados iniciais

Aprender:

- array;
- list;
- stack;
- queue;
- dictionary/hash map;
- set.

Entender de forma intuitiva:

- busca;
- inserção;
- remoção;
- custo computacional;
- ideia de Big O.

## Projetos

Criar:

### Projeto 1 — Gerenciador de tarefas

Recursos:

- criar tarefa;
- editar;
- excluir;
- marcar como concluída;
- salvar em arquivo.

### Projeto 2 — Sistema de inventário

Simular o inventário de um jogo:

- itens;
- quantidade;
- categorias;
- busca;
- adicionar/remover.

### Projeto 3 — Simulação orientada a objetos

Exemplo:

- robôs;
- veículos;
- personagens;
- sensores.

O objetivo é trabalhar estado, comportamento e interação entre objetos.

## Critério para avançar

Você deve conseguir:

- criar um projeto C# sem tutorial passo a passo;
- dividir código em classes;
- encontrar bugs usando debugger;
- ler mensagens de erro;
- pesquisar documentação;
- explicar o que cada parte do seu código faz.

---

# 7. Trilha paralela — Matemática para quem não é bom em matemática

**Duração: meses 2 a 24, em paralelo**

Você não precisa dominar matemática avançada para começar.

A matemática deve ser estudada conforme começa a aparecer nos projetos.

## Nível 1 — Recuperação básica

Aprender:

- números negativos;
- frações;
- porcentagem;
- potência;
- raiz;
- regra de três;
- equações simples;
- plano cartesiano;
- funções básicas.

## Nível 2 — Geometria

Aprender:

- ponto;
- linha;
- segmento;
- distância;
- ângulo;
- triângulos;
- Pitágoras;
- graus e radianos.

## Nível 3 — Trigonometria

Aprender:

- seno;
- cosseno;
- tangente;
- círculo trigonométrico;
- relação entre ângulo e direção.

## Nível 4 — Vetores

Este é um dos tópicos mais importantes de toda a carreira.

Aprender:

- vetor 2D;
- vetor 3D;
- magnitude;
- direção;
- normalização;
- soma;
- subtração;
- multiplicação por escalar;
- distância;
- produto escalar;
- produto vetorial.

Aplicações:

- descobrir direção;
- mover objetos;
- calcular distância;
- determinar se um objeto está na frente de outro;
- orientação;
- iluminação;
- física.

## Nível 5 — Matrizes e transformações

Aprender:

- matriz;
- multiplicação de matrizes;
- matriz de transformação;
- translação;
- rotação;
- escala;
- transformação de coordenadas.

Entender os espaços:

- local space;
- world space;
- view/camera space;
- screen space.

## Nível 6 — Rotações

Aprender:

- Euler angles;
- gimbal lock;
- quaternions;
- interpolação;
- `Lerp`;
- `Slerp`.

Não é necessário aprender a derivação matemática completa de quaternions no começo.

Primeiro aprenda a usá-los corretamente.

## Cálculo

Cálculo diferencial e integral é útil, mas **não deve bloquear sua entrada na área**.

Prioridade:

1. álgebra;
2. geometria;
3. trigonometria;
4. vetores;
5. álgebra linear;
6. cálculo, quando necessário.

## Critério de domínio matemático inicial

Você deve conseguir explicar e aplicar:

- posição `(x, y, z)`;
- distância entre pontos;
- direção entre objetos;
- normalização de vetor;
- produto escalar;
- produto vetorial;
- transformação local vs. global;
- rotação;
- interpolação.

---

# 8. Fase 2 — Git e rotina profissional

**Começar por volta do mês 3 e nunca parar de usar**

## Aprender Git

- repository;
- `git init`;
- `git status`;
- `git add`;
- `git commit`;
- `.gitignore`;
- `git log`;
- branch;
- merge;
- remote;
- push;
- pull;
- conflitos básicos.

## Objetivo

Todo projeto relevante deverá estar versionado.

## Regra

Não espere virar profissional para começar a trabalhar como um.

Desde cedo:

- escreva README;
- documente decisões;
- use commits;
- organize pastas;
- registre bugs;
- mantenha histórico do projeto.

---

# 9. Fase 3 — Engenharia de Software

**Duração estimada: meses 8 a 16**

## Objetivo

Sair de "sei escrever código" para "sei construir software".

## Estudar

### Qualidade de código

- nomes claros;
- funções pequenas;
- separação de responsabilidades;
- baixo acoplamento;
- alta coesão;
- refatoração;
- tratamento de erros.

### Orientação a objetos aprofundada

- composição;
- interfaces;
- abstração;
- polimorfismo;
- princípios SOLID.

### Arquitetura inicial

- camadas;
- módulos;
- separação entre domínio e interface;
- gerenciamento de estado;
- eventos.

### Testes

Aprender:

- teste unitário;
- teste de integração;
- assertions;
- casos de borda.

### Assincronismo

Aprender conceitos de:

- threads;
- tarefas;
- `async`;
- `await`;
- concorrência.

Isso será importante quando trabalhar com:

- sensores;
- rede;
- carregamento de recursos;
- serviços;
- processamento em tempo real.

## Projeto de conclusão

Criar uma aplicação C# de médio porte com:

- múltiplos módulos;
- persistência;
- testes;
- Git;
- README;
- tratamento de erros.

---

# 10. Fase 4 — Entrar no mundo 3D com Unity

**Duração estimada: meses 12 a 24**

Agora começa a ponte direta para Computação Espacial.

## Aprender Unity

### Editor

Dominar:

- Scene;
- Game;
- Hierarchy;
- Inspector;
- Project;
- Console;
- Package Manager.

### Modelo de objetos

Aprender:

- GameObject;
- Component;
- Transform;
- Prefab;
- Scene;
- ScriptableObject.

### Ciclo de execução

Entender:

- inicialização;
- atualização por frame;
- física;
- eventos;
- destruição de objetos.

### Input

Criar sistemas para:

- teclado;
- mouse;
- gamepad;
- toque.

## Física

Aprender:

- collider;
- rigidbody;
- trigger;
- gravity;
- force;
- raycast;
- layers;
- collision detection.

## Computação gráfica básica

Entender:

- mesh;
- vertex;
- triangle;
- normal;
- UV;
- material;
- texture;
- shader;
- light;
- shadow;
- camera;
- field of view;
- render pipeline.

Não é necessário escrever shaders complexos ainda.

## Animação

Aprender:

- Animation;
- Animator;
- estados;
- transições;
- interpolação.

## Áudio

Aprender:

- áudio 2D;
- áudio 3D;
- distância;
- espacialização.

## Ferramenta 3D auxiliar

Aprender apenas o básico de **Blender**:

- navegar;
- mover;
- rotacionar;
- escalar;
- modelagem muito simples;
- UV básico;
- exportar modelos;
- otimizar assets.

Seu objetivo é ser desenvolvedor, não artista 3D.

## Projetos

### Projeto 1 — Sala 3D interativa

Criar:

- ambiente;
- iluminação;
- objetos;
- física;
- interação;
- UI.

### Projeto 2 — Simulador simples

Exemplos:

- laboratório;
- montagem de peças;
- treinamento;
- máquina industrial.

### Projeto 3 — Sandbox de física

Implementar:

- objetos manipuláveis;
- gravidade;
- lançamento;
- colisões;
- raycasts.

## Critério para avançar

Você deve conseguir criar sozinho uma aplicação 3D interativa simples, otimizada o suficiente para manter execução fluida no hardware-alvo.

---

# 11. Fase 5 — XR: realidade virtual, aumentada e mista

**Duração estimada: meses 20 a 32**

## Objetivo

Aprender os conceitos universais de aplicações imersivas.

## Primeiro: entender XR

Diferenciar:

- VR — Virtual Reality;
- AR — Augmented Reality;
- MR — Mixed Reality;
- XR — Extended Reality.

## Unity XR

Estudar:

**XR Interaction Toolkit**

Aprender:

- XR Origin;
- Interactor;
- Interactable;
- grab;
- ray interaction;
- direct interaction;
- UI em XR;
- locomotion;
- teleport;
- snap turn;
- continuous movement;
- sockets;
- haptics.

## OpenXR

Depois de entender a experiência XR na prática, estudar OpenXR.

Entender:

- runtime;
- application;
- session;
- reference spaces;
- poses;
- actions;
- action sets;
- interaction profiles;
- extensions.

O objetivo não é decorar a especificação.

O objetivo é entender a camada que permite desenvolver experiências para diferentes dispositivos e runtimes.

## Inputs espaciais

Aprender progressivamente:

- head pose;
- motion controllers;
- hand tracking;
- gaze;
- eye tracking;
- gestures;
- voice input.

Nem todo dispositivo oferece todos esses recursos.

## UX espacial

Estudar:

- conforto;
- escala;
- distância;
- profundidade;
- legibilidade;
- tamanho angular;
- campo de visão;
- movimento;
- enjoo/cybersickness;
- feedback visual;
- feedback sonoro;
- feedback háptico;
- interação direta;
- interação a distância.

## Projetos

### Projeto XR 1 — Laboratório de interação

Implementar:

- pegar;
- soltar;
- lançar;
- pressionar;
- puxar;
- encaixar;
- menus espaciais.

### Projeto XR 2 — Treinamento imersivo

Criar uma sequência:

1. usuário recebe instrução;
2. encontra uma ferramenta;
3. executa procedimento;
4. sistema valida;
5. usuário recebe feedback.

### Projeto XR 3 — Visualizador 3D

Permitir:

- selecionar modelo;
- mover;
- rotacionar;
- escalar;
- explodir peças;
- destacar componentes;
- mostrar informações.

---

# 12. Fase 6 — AR e entendimento do ambiente físico

**Duração estimada: meses 28 a 40**

Aqui você entra diretamente nos problemas típicos de Computação Espacial.

## Unity AR Foundation

Aprender:

- AR Session;
- XR Origin;
- plane detection;
- raycast;
- anchors;
- point clouds;
- image tracking;
- meshing quando suportado;
- occlusion;
- depth;
- light estimation.

## ARCore

Entender conceitualmente:

- motion tracking;
- environmental understanding;
- light estimation;
- anchors;
- depth;
- occlusion;
- geospatial capabilities;
- scene semantics quando aplicável.

## ARKit

Entender:

- tracking;
- anchors;
- plane detection;
- scene reconstruction;
- image tracking;
- hand tracking quando disponível;
- world tracking.

## Problema 1 — Mapeamento espacial

Aprender como sistemas detectam:

- chão;
- paredes;
- superfícies;
- profundidade;
- malha do ambiente.

## Problema 2 — Âncoras

Entender como manter um objeto virtual associado a uma posição estável no mundo.

Estudar:

- local anchors;
- world anchors;
- cloud/shared anchors;
- persistência.

## Problema 3 — Oclusão

Aprender a fazer objetos reais ocultarem corretamente objetos virtuais.

Entender:

- depth maps;
- scene mesh;
- depth testing;
- máscaras;
- limitações de sensores.

## Problema 4 — Iluminação

Estudar:

- light estimation;
- reflection;
- environment probes;
- materiais;
- sombras;
- integração visual entre físico e digital.

## Projeto principal

### Aplicativo de posicionamento espacial

Exemplo:

Um aplicativo no qual o usuário:

1. escaneia um ambiente;
2. detecta piso e mesas;
3. posiciona um objeto virtual;
4. sai do enquadramento;
5. retorna;
6. encontra o objeto na posição correta;
7. observa o objeto sendo ocultado por partes reais do ambiente.

Esse é um dos projetos mais importantes do roadmap.

---

# 13. Fase 7 — Engenharia de Computação Espacial

**Duração estimada: meses 36 a 48**

Agora o objetivo deixa de ser "criar uma experiência XR" e passa a ser "engenheirar sistemas espaciais".

## Tracking

Estudar conceitos de:

- 3DoF;
- 6DoF;
- pose;
- coordinate frames;
- drift;
- relocalization;
- calibration;
- sensor fusion.

## SLAM

Entender os fundamentos de:

**Simultaneous Localization and Mapping**

Não é necessário implementar um SLAM completo do zero.

Você deve entender:

- problema de localização;
- problema de mapeamento;
- landmarks;
- features;
- pose estimation;
- drift;
- loop closure;
- relocalização.

## Sensores

Entender:

- câmera RGB;
- câmera de profundidade;
- LiDAR;
- IMU;
- acelerômetro;
- giroscópio;
- magnetômetro.

## Renderização

Aprofundar:

- rendering pipeline;
- frame;
- draw calls;
- batching;
- GPU;
- CPU;
- shaders;
- lighting;
- post-processing;
- texture memory;
- level of detail;
- culling.

## Performance XR

Aprender a investigar:

- baixa taxa de quadros;
- latência;
- garbage collection;
- memória;
- draw calls;
- excesso de polígonos;
- shaders pesados;
- física excessiva.

Em XR, performance não é apenas otimização técnica.

Ela afeta diretamente conforto e qualidade da experiência.

## Arquitetura

Estudar padrões úteis:

- state machine;
- observer/events;
- command;
- dependency injection;
- object pooling;
- data-oriented thinking.

Não use padrões apenas porque existem.

Use quando resolverem um problema real.

---

# 14. Fase 8 — Escolher uma especialização

**Duração estimada: a partir do ano 4**

Depois da base comum, escolha uma direção principal.

---

## Trilha A — XR corporativo / industrial

Boa para:

- treinamento;
- manutenção;
- simulação;
- indústria;
- arquitetura;
- engenharia;
- educação;
- saúde.

### Prioridades

- Unity;
- C#;
- OpenXR;
- interação;
- física;
- networking;
- backend;
- integração com APIs;
- dados 3D;
- performance.

### Projeto de portfólio

Simulador de treinamento industrial completo.

---

## Trilha B — visionOS / ecossistema Apple

### Aprender

- Swift;
- SwiftUI;
- RealityKit;
- ARKit;
- Reality Composer Pro;
- Xcode;
- USD/USDZ;
- spatial UI;
- volumes;
- immersive spaces.

### Observação

Esta trilha exige acesso ao ecossistema de desenvolvimento Apple em algum momento.

Não é necessário comprá-lo no início do roadmap.

---

## Trilha C — Unreal / visualização avançada

### Aprender

- Unreal Engine;
- Blueprints;
- C++;
- materiais;
- iluminação;
- rendering;
- profiling;
- OpenXR.

Boa para experiências nas quais fidelidade gráfica é prioridade.

Não estude Unreal e Unity profundamente ao mesmo tempo no início.

---

## Trilha D — IA + visão computacional + Computação Espacial

Esta é uma especialização mais avançada.

### Adicionar Python

Aprender:

- sintaxe;
- NumPy;
- manipulação de dados;
- ambientes virtuais.

### Visão computacional

Aprender:

- imagem digital;
- pixels;
- filtros;
- features;
- camera model;
- perspective;
- homography;
- pose estimation;
- object detection;
- segmentation;
- tracking.

### Ferramentas

- Python;
- OpenCV;
- modelos de visão;
- frameworks de machine learning quando necessário.

### Matemática adicional

- álgebra linear;
- probabilidade;
- estatística;
- otimização.

### Projeto

Sistema que reconhece ou acompanha elementos reais e utiliza o resultado dentro de uma experiência espacial.

---

# 15. O que NÃO aprender agora

Nos primeiros 12 meses, evite tentar estudar profundamente ao mesmo tempo:

- Unity;
- Unreal;
- C#;
- C++;
- Swift;
- Kotlin;
- Python;
- inteligência artificial;
- machine learning;
- shaders avançados;
- modelagem 3D avançada;
- backend complexo;
- blockchain;
- DevOps avançado.

Isso cria conhecimento superficial e atrasa a base.

A prioridade inicial deve ser:

**C# → programação → Git → matemática → Unity**

---

# 16. Ordem das tecnologias

## Prioridade 1 — Obrigatório

1. C#
2. Git
3. Unity
4. Matemática 3D
5. XR Interaction Toolkit
6. OpenXR
7. AR Foundation

## Prioridade 2 — Plataforma

Depois:

8. ARCore
9. ARKit

## Prioridade 3 — Especialização

Escolher conforme objetivo:

- Swift + RealityKit + visionOS;
- C++ + Unreal Engine;
- Python + OpenCV + IA;
- networking/multiusuário;
- computação gráfica avançada.

---

# 17. Projetos obrigatórios do portfólio

Ao final da trajetória, tente possuir pelo menos estes projetos.

## 1. Aplicação C# estruturada

Demonstra:

- programação;
- arquitetura;
- Git;
- testes.

## 2. Ambiente 3D interativo

Demonstra:

- Unity;
- física;
- iluminação;
- materiais;
- input;
- arquitetura de componentes.

## 3. Experiência XR

Demonstra:

- interação;
- controladores/mãos;
- UI espacial;
- locomotion;
- OpenXR.

## 4. Experiência AR

Demonstra:

- plane detection;
- raycast;
- anchors;
- depth/occlusion;
- ambiente físico.

## 5. Projeto de Computação Espacial completo

Deve combinar vários elementos:

- mapeamento;
- persistência espacial;
- oclusão;
- interação;
- spatial UI;
- áudio espacial;
- otimização.

## 6. Projeto de especialização

Escolher um:

- visionOS;
- Unreal;
- IA/visão computacional;
- multiusuário;
- industrial/medical simulation.

---

# 18. Como montar um portfólio forte

Cada projeto deverá ter:

- README;
- descrição do problema;
- vídeo curto;
- screenshots;
- tecnologias utilizadas;
- arquitetura;
- principais desafios;
- decisões técnicas;
- limitações;
- aprendizados;
- código quando puder ser público.

Evite portfólio composto apenas por clones de tutoriais.

Uma boa evolução é:

**tutorial → reconstrução sem tutorial → modificação → projeto original**

---

# 19. Inglês técnico

Inglês deve ser estudado em paralelo.

Objetivo inicial:

**ler documentação técnica sem depender totalmente de tradução.**

Prioridades:

- vocabulário de programação;
- leitura;
- documentação;
- vídeos técnicos;
- escrita curta;
- comunicação profissional.

Não espere alcançar inglês avançado para começar a ler documentação.

---

# 20. Rotina semanal sugerida

## Seu bloco real (2º semestre de 2026)

| Dia | Horário livre | Uso sugerido |
|---|---|---|
| Segunda | antes das 10h | opcional: revisão leve / inglês |
| Terça | a partir das 16h | **Roadmap (C#/Unity/matemática) — ~2h** |
| Quarta | antes das 10h | faculdade on-line (UML/SO/Paradigmas) |
| Quinta | a partir das 16h (após resolver a sobreposição com a aula) | **Roadmap — ~1h30** |
| Sexta | a partir das 19h | leve ou descanso (dia mais puxado: aula + estágio) |
| Sábado | dia livre | **Roadmap — bloco principal, ~3h** |
| Domingo | manhã/tarde | faculdade on-line + descanso |

Total estimado dedicado ao roadmap: **~6h30–8h/semana** — dentro do "abaixo do ritmo sustentável, mas ainda válido" da seção 3. Ajuste os blocos conforme sua energia real, principalmente quinta e sexta à noite depois de um dia inteiro de estágio.

## Referência genérica (para quando tiver mais tempo livre — ex.: depois de jun/2027)

Exemplo para **10 horas por semana**:

| Atividade | Horas |
|---|---:|
| Programação / tecnologia principal | 4h |
| Projeto prático | 3h |
| Matemática | 2h |
| Inglês/documentação/revisão | 1h |

Depois que entrar em Unity/XR:

| Atividade | Horas |
|---|---:|
| Unity/XR | 4h |
| Projeto | 3h |
| Programação C# | 1h |
| Matemática/3D | 1h |
| Documentação/inglês | 1h |

---

# 21. Método de estudo

Para cada assunto:

## Passo 1 — Entender

Leia ou assista uma introdução.

## Passo 2 — Reproduzir

Implemente um exemplo.

## Passo 3 — Alterar

Mude o comportamento.

## Passo 4 — Criar

Faça uma versão própria sem copiar.

## Passo 5 — Explicar

Explique com suas palavras:

- o que é;
- para que serve;
- como funciona;
- quando usar;
- quais limitações possui.

Se você não consegue explicar, provavelmente ainda não consolidou.

---

# 22. Regra de progressão

Não avance apenas porque "terminou um curso".

Avance quando conseguir produzir algo.

Cada fase deve terminar com:

- um projeto;
- código versionado;
- README;
- demonstração;
- explicação técnica.

---

# 23. Checklist por ano

## Ano 1 — Base

- [ ] lógica de programação
- [ ] C# básico
- [ ] orientação a objetos
- [ ] estruturas de dados básicas
- [ ] debugger
- [ ] Git
- [ ] terminal
- [ ] matemática básica
- [ ] primeiros projetos

### Resultado esperado

Conseguir programar aplicações pequenas sem depender constantemente de tutoriais.

---

## Ano 2 — 3D

- [ ] C# intermediário
- [ ] engenharia de software
- [ ] Unity
- [ ] vetores
- [ ] trigonometria
- [ ] matrizes
- [ ] transformações
- [ ] física
- [ ] computação gráfica básica
- [ ] Blender básico
- [ ] aplicações 3D

### Resultado esperado

Conseguir desenvolver aplicações 3D interativas.

---

## Ano 3 — XR

- [ ] XR Interaction Toolkit
- [ ] OpenXR
- [ ] controladores
- [ ] hand tracking
- [ ] gaze
- [ ] spatial UI
- [ ] locomotion
- [ ] haptics
- [ ] áudio espacial
- [ ] performance
- [ ] AR Foundation
- [ ] anchors
- [ ] plane detection
- [ ] occlusion

### Resultado esperado

Conseguir construir experiências XR funcionais.

---

## Ano 4 — Computação Espacial

- [ ] tracking
- [ ] spatial mapping
- [ ] scene understanding
- [ ] depth
- [ ] persistência espacial
- [ ] SLAM conceitual
- [ ] sensores
- [ ] otimização XR
- [ ] arquitetura
- [ ] aplicações completas

### Resultado esperado

Conseguir resolver problemas de engenharia espacial, não apenas montar cenas.

---

## Ano 5+ — Especialização e mercado

- [ ] escolher especialização
- [ ] construir projeto avançado
- [ ] aprofundar plataforma
- [ ] contribuir com projetos
- [ ] preparar currículo
- [ ] organizar GitHub
- [ ] publicar demonstrações
- [ ] estudar entrevistas técnicas
- [ ] candidatar-se a vagas relacionadas

---

# 24. Conhecimento mínimo para procurar oportunidades

Você não precisa dominar todo o roadmap antes de procurar experiência profissional.

Um nível inicial competitivo deverá incluir:

- C# sólido;
- Git;
- Unity;
- matemática 3D básica;
- vetores e transformações;
- física;
- criação de interfaces 3D;
- XR Interaction Toolkit;
- noções de OpenXR;
- pelo menos 2 ou 3 projetos relevantes;
- capacidade de explicar decisões técnicas.

O restante pode continuar sendo construído ao longo da carreira.

---

# 25. Marco final

Ao completar a base deste roadmap, você deve ser capaz de receber um problema como:

> "Precisamos colocar uma máquina virtual em uma fábrica real, manter sua posição persistente, permitir manipulação por gestos e fazer partes do modelo desaparecerem corretamente atrás dos equipamentos físicos."

E decompor o problema em:

1. tracking;
2. coordinate systems;
3. spatial mapping;
4. anchors;
5. persistence;
6. depth;
7. occlusion;
8. input;
9. interaction;
10. rendering;
11. performance;
12. arquitetura de software.

Esse é o ponto em que você deixa de apenas "usar Unity" e começa a pensar como um **engenheiro de Computação Espacial**.

---

# 26. Sequência resumida

```text
ZERO
│
├── Lógica
│
├── C#
│   ├── Fundamentos
│   ├── OOP
│   ├── Estruturas de dados
│   └── Engenharia de software
│
├── Git
│
├── Matemática
│   ├── Álgebra
│   ├── Geometria
│   ├── Trigonometria
│   ├── Vetores
│   ├── Matrizes
│   └── Quaternions
│
├── Unity
│   ├── GameObjects
│   ├── Components
│   ├── Physics
│   ├── Input
│   ├── Rendering
│   └── 3D
│
├── XR
│   ├── XR Interaction Toolkit
│   ├── OpenXR
│   ├── Controllers
│   ├── Hands
│   ├── Gaze
│   └── Spatial UI
│
├── AR / MR
│   ├── AR Foundation
│   ├── ARCore
│   ├── ARKit
│   ├── Anchors
│   ├── Mapping
│   ├── Depth
│   └── Occlusion
│
├── Spatial Computing Engineering
│   ├── Tracking
│   ├── Sensors
│   ├── SLAM
│   ├── Scene understanding
│   ├── Spatial persistence
│   └── Performance
│
└── ESPECIALIZAÇÃO
    ├── visionOS / RealityKit
    ├── Unreal / C++
    ├── IA / Visão Computacional
    └── XR corporativo / industrial
```

---

# 27. Primeira ação concreta

Não comece instalando cinco engines ou estudando inteligência artificial.

Comece por:

1. instalar uma IDE/editor adequado para C#;
2. concluir fundamentos introdutórios de C#;
3. criar pequenos programas de terminal;
4. iniciar Git;
5. estudar matemática básica em paralelo;
6. manter uma pasta/repositório chamado, por exemplo, `spatial-computing-roadmap`;
7. registrar nele todos os exercícios e projetos.

**Primeiro objetivo real: tornar-se programador.**

Depois:

**tornar-se desenvolvedor 3D.**

Depois:

**tornar-se desenvolvedor XR.**

Por último:

**tornar-se engenheiro de Computação Espacial.**

---

# 28. Referências oficiais recomendadas

Estas fontes devem ser priorizadas porque representam a documentação dos próprios fornecedores e padrões utilizados na área.

## Documentação e plataformas

- Microsoft Learn — C#: https://learn.microsoft.com/dotnet/csharp/
- Git — Pro Git: https://git-scm.com/book/en/v2
- Unity — XR Interaction Toolkit: https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit/
- Unity — OpenXR Plugin: https://docs.unity3d.com/Packages/com.unity.xr.openxr/
- Unity — AR Foundation: https://docs.unity3d.com/Packages/com.unity.xr.arfoundation/
- Khronos — OpenXR: https://www.khronos.org/openxr/
- Google — ARCore: https://developers.google.com/ar
- Apple — visionOS: https://developer.apple.com/visionos/
- Apple — ARKit: https://developer.apple.com/augmented-reality/arkit/
- Epic Games — XR Development: https://dev.epicgames.com/documentation/unreal-engine/developing-for-xr-experiences-in-unreal-engine
- **Android XR** (Google + Samsung + Qualcomm) — plataforma nova, lançada em out/2025, suporta OpenXR nativamente: https://developer.android.com/develop/xr

## Cursos e trilhas guiadas (verificados)

- Unity Learn — Pathways gratuitos (Junior Programmer → VR Development → AR Foundation): https://learn.unity.com/pathways
- Coursera — "Extended Reality for Everybody" (Univ. Michigan) e "Unity XR: How to Build AR and VR Apps" (Unity), acessíveis via Coursera Plus (~R$ 2.100/ano) ou em modo auditoria gratuita
- Udemy — cursos pontuais de XR Interaction Toolkit e VR multiplayer, geralmente em promoção (R$ 80–160)

## Certificação

- Unity Certifications, trilha oficial User → Associate: Game Developer → Professional: Programmer: https://unity.com/products/unity-certifications
  - o track **"Unity Certified User: VR Developer"** é um marco intermediário concreto e alcançável bem antes do nível profissional

## Livro de matemática 3D

- *3D Math Primer for Graphics and Game Development* — Fletcher Dunn & Ian Parberry (já referenciado na seção 7; confirmado como a escolha certa da área)

---

# 29. Mercado de trabalho e cargos intermediários (Brasil e remoto)

## Panorama

O mercado global de spatial computing/XR vem crescendo por volta de 18–22% ao ano (estimativas variam bastante entre consultorias — trate os valores absolutos com desconfiança, mas a tendência de crescimento é consistente entre todas as fontes).

## Salário — Brasil (por senioridade)

| Nível | Faixa aproximada/mês |
|---|---|
| Júnior | R$ 2.500 – 4.500 |
| Pleno | R$ 5.000 – 7.000 |
| Sênior | R$ 7.000 – 15.000 |

Amostras de mercado ainda são pequenas para cargos específicos de XR no Brasil — use como ordem de grandeza, não como valor exato.

## Salário — remoto internacional (em dólar)

XR Developer nos EUA: média de US$ 108 mil a US$ 113 mil/ano. Existem vagas remotas reais pagando o Brasil nessa faixa (ex.: US$ 100 mil/ano via plataformas como Crossover). O salto de renda mais realista no médio prazo não é "virar sênior no Brasil", é migrar para contrato remoto internacional — o que exige inglês fluente e portfólio público.

## Empresas-alvo no Brasil

- **ARVORE Immersive Experiences** (São Paulo) — a única empresa de VR/AR do Brasil com investimento de VC, premiada internacionalmente
- **RD3 Digital** (SP) — RA/RV corporativa e industrial
- **Casa Mais** (SP) — treinamentos corporativos em VR desde 2011
- **Oniria** (PR) — simulação e treinamento industrial em VR
- **Beenoculus** (PR) — hardware + software XR para educação/saúde/indústria
- **Kokku** (Recife) — maior co-desenvolvedora brasileira de games AAA, tem frente de Metaverso
- **Aquiris / Epic Games Brasil** (Porto Alegre) — hoje mais Unreal do que Unity, mas referência de engenharia

## Ponte para o dólar sem sair do Brasil

Plataformas de staffing que colocam devs brasileiros em vagas remotas Unity/XR pagando em dólar: **Revelo, Turing, Toptal, Amber**. Bom objetivo de médio prazo (1–3 anos de experiência), não de entrada.

## O que não é realista ainda

Meta, Niantic, Snap e Magic Leap concentram engenharia XR presencialmente nos EUA/Europa e **não contratam remoto do Brasil hoje**. São metas de relocação de longo prazo, não de emprego imediato — não coloque isso como marco intermediário do roadmap.

---

# 30. Formação complementar — cursos, certificações e pós-graduação

## Cursos: onde gastar dinheiro (e onde não gastar)

- **Trilha gratuita como espinha dorsal:** Unity Learn (Pathways) + documentação oficial (Apple, Google, Khronos) cobre a maior parte do conteúdo técnico sem custo.
- **Vale o investimento:** Coursera Plus por 1 ano (~R$ 2.100, ou auditoria gratuita) para as especializações estruturadas com certificado.
- **Vale pontualmente:** 1–2 cursos Udemy em promoção (R$ 80–160) para tópicos específicos como XR Interaction Toolkit.
- **Não vale agora:** bootcamps tipo Circuit Stream (US$ 3.950+, ≈ R$ 15–21 mil) — conteúdo bom, mas redundante com o que já dá pra aprender de graça nesse estágio.

## Certificação como marco verificável

Use a trilha de certificações da Unity (seção 28) como critério objetivo de progresso, especialmente o track **VR Developer** — é um "selo" que comprova competência antes de qualquer entrevista.

## Pós-graduação (só depois da graduação em ADS)

**Reconhecidas pelo MEC, EAD, custo acessível (~R$ 135–500/mês):**
- Cruzeiro do Sul Virtual — pós em Game Design / Desenvolvimento de Jogos Digitais (RV/RA)
- Unyleya — pós em Realidade Virtual, Realidade Aumentada e Metaverso
- Senac — pós em Desenvolvimento de Games (360h)

**Acadêmica, aspiracional (mestrado, não lato sensu):**
- PUC-Rio — Depto. de Informática, áreas de Computação Gráfica / Interação Humano-Computador / Jogos e Entretenimento Digital (Lab. Tecgraf). Referência presencial mais forte no Rio, mas seletiva e seguindo trilha acadêmica.

A pós-graduação não é pré-requisito para entrar no mercado — é um diferencial para depois. Priorize portfólio e primeiro emprego antes de investir nela.

---

# 31. Regra final

A Computação Espacial reúne muitas disciplinas.

Você não precisa dominá-las de uma vez.

A trajetória correta é construir camadas:

> **programação → software → matemática → 3D → XR → percepção espacial → especialização**

A consistência ao longo de vários anos será mais importante do que tentar aprender rapidamente todas as tecnologias do mercado.

---

# 32. Glossário

Siglas, tecnologias e termos técnicos usados ao longo do roadmap, para consulta rápida.

## Siglas e acrônimos

- **AR** — Augmented Reality (Realidade Aumentada): sobrepõe conteúdo digital ao mundo físico real.
- **VR** — Virtual Reality (Realidade Virtual): substitui o ambiente real por um ambiente totalmente digital.
- **MR** — Mixed Reality (Realidade Mista): mistura digital e físico com interação entre os dois (ex.: objeto virtual sendo ocluído por um móvel real).
- **XR** — Extended Reality: termo guarda-chuva que engloba AR, VR e MR.
- **SLAM** — Simultaneous Localization and Mapping: técnica pela qual um dispositivo descobre sua própria posição enquanto constrói um mapa do ambiente ao redor, ao mesmo tempo.
- **IMU** — Inertial Measurement Unit: sensor que combina acelerômetro, giroscópio (e às vezes magnetômetro) para medir orientação e movimento.
- **LiDAR** — Light Detection and Ranging: sensor que mede distância disparando pulsos de laser, usado para gerar mapas de profundidade precisos do ambiente.
- **GPU** — Graphics Processing Unit: processador especializado em renderização gráfica e cálculos paralelos.
- **CPU** — Central Processing Unit: processador de uso geral que executa a lógica principal do programa.
- **3DoF / 6DoF** — Degrees of Freedom (Graus de Liberdade): 3DoF rastreia só rotação da cabeça; 6DoF rastreia rotação + posição no espaço.
- **LOD** — Level of Detail: técnica de renderizar objetos com menos detalhe quando estão longe da câmera, para ganhar performance.
- **FOV** — Field of View (Campo de Visão): ângulo do ambiente visível através da câmera ou do headset.
- **UV** — coordenadas usadas para "desenrolar" a superfície de um modelo 3D e mapear uma textura sobre ela (U e V são os eixos, para não confundir com X/Y/Z do espaço 3D).
- **IDE** — Integrated Development Environment: programa com editor de código, debugger e ferramentas de build integrados (ex.: Visual Studio, Rider).
- **POO** — Programação Orientada a Objetos (em inglês, OOP).
- **UI** — User Interface (Interface do Usuário): os elementos visuais com que a pessoa interage.
- **UX** — User Experience (Experiência do Usuário): como a interação é percebida e sentida pela pessoa.
- **API** — Application Programming Interface: conjunto de funções/regras que permite um sistema se comunicar com outro.
- **SDK** — Software Development Kit: conjunto de ferramentas, bibliotecas e documentação para desenvolver para uma plataforma específica (ex.: SDK do Android XR).
- **USD / USDZ** — Universal Scene Description (e sua versão compactada): formato de arquivo da Pixar para descrever cenas 3D, usado pela Apple no ecossistema visionOS/AR.
- **MEC** — Ministério da Educação: órgão que credencia instituições de ensino e valida cursos no Brasil.
- **EAD** — Ensino a Distância.
- **VC** — Venture Capital (Capital de Risco): investimento em empresas com alto potencial de crescimento, geralmente startups.

## Motores, frameworks, plataformas e ferramentas

- **Unity** — motor de jogos/aplicações em tempo real, principal ferramenta deste roadmap; usa C# como linguagem de script.
- **Unreal Engine** — motor de jogos concorrente da Unity, forte em fidelidade gráfica; usa C++ e o sistema visual **Blueprints**.
- **OpenXR** — padrão aberto (mantido pelo **Khronos Group**) que permite que um mesmo app XR rode em diferentes headsets/runtimes sem reescrever o código para cada um.
- **XR Interaction Toolkit** — pacote oficial da Unity para criar interações XR (pegar, apontar, teleportar etc.) de forma padronizada.
- **AR Foundation** — camada da Unity que unifica ARCore e ARKit sob uma única API, para criar apps AR multiplataforma.
- **ARCore** — SDK da Google para desenvolvimento de Realidade Aumentada em Android.
- **ARKit** — framework da Apple para desenvolvimento de Realidade Aumentada em iOS/iPadOS.
- **Android XR** — sistema operacional para XR desenvolvido por Google, Samsung e Qualcomm (lançado em 2025), com suporte nativo a OpenXR.
- **visionOS** — sistema operacional da Apple para o Vision Pro, focado em "spatial computing".
- **RealityKit** — framework gráfico da Apple para renderizar conteúdo 3D/AR em apps visionOS/iOS.
- **Reality Composer Pro** — ferramenta visual da Apple para montar e editar cenas 3D/AR sem programar tudo do zero.
- **Xcode** — IDE oficial da Apple para desenvolver apps iOS/visionOS/macOS.
- **Swift / SwiftUI** — linguagem de programação da Apple e seu framework declarativo para construir interfaces.
- **Blender** — software gratuito de modelagem, animação e edição 3D.
- **Git** — sistema de controle de versão, usado para rastrear o histórico de mudanças em um projeto de código.
- **NumPy** — biblioteca Python para computação numérica e manipulação de arrays, base de praticamente todo código de visão computacional/IA em Python.
- **OpenCV** — biblioteca open-source de visão computacional, usada para processar imagens e vídeo.

## Termos técnicos (matemática, computação gráfica e XR)

- **Quaternion** — forma matemática de representar rotações em 3D que evita o problema do gimbal lock.
- **Gimbal lock** — problema que ocorre ao representar rotação com ângulos de Euler, onde dois eixos de rotação "colam" um no outro e você perde um grau de liberdade.
- **Euler angles** (ângulos de Euler) — forma de representar rotação em 3D usando três ângulos (um por eixo); intuitivo, mas sujeito a gimbal lock.
- **Lerp** (Linear Interpolation) — interpolação linear: calcula um valor intermediário entre dois pontos, em linha reta.
- **Slerp** (Spherical Linear Interpolation) — interpolação esférica: como o Lerp, mas ao longo de uma curva esférica — usado para interpolar rotações (quaternions) de forma suave.
- **Big O** — notação usada para descrever como o tempo ou memória que um algoritmo consome cresce conforme a quantidade de dados aumenta.
- **SOLID** — conjunto de 5 princípios de bom design orientado a objetos (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion).
- **Draw call** — cada "pedido" que a CPU faz à GPU para desenhar algo na tela; muitos draw calls pequenos prejudicam a performance.
- **Culling** — técnica de não renderizar o que não está visível pela câmera, para economizar processamento.
- **Batching** — técnica de agrupar múltiplos objetos em uma única chamada de renderização, para reduzir draw calls.
- **Occlusion** (oclusão) — quando um objeto (real ou virtual) esconde corretamente outro atrás dele, respeitando a profundidade da cena.
- **Anchor** (âncora) — ponto de referência que "prende" um objeto virtual a uma posição real do mundo, mantendo-o estável mesmo quando a câmera se move.
- **Point cloud** (nuvem de pontos) — conjunto de pontos no espaço 3D que representa a superfície de um ambiente ou objeto escaneado.
- **Mesh** — a "malha" de vértices, arestas e faces (triangles) que forma a superfície de um modelo 3D.
- **Raycast** — técnica de "disparar" uma linha invisível no espaço 3D para detectar o que ela atinge (usado para mirar, selecionar objetos, checar colisões etc.).
- **Cybersickness** — mal-estar (náusea, tontura) causado por experiências VR/XR, geralmente por conflito entre o que os olhos veem e o que o corpo sente.
- **Homography** — transformação matemática que relaciona a mesma cena vista de dois pontos de vista diferentes (usado em visão computacional para reconhecer planos e superfícies).
- **Sensor fusion** — combinar dados de vários sensores diferentes (câmera, IMU etc.) para chegar numa estimativa de posição/orientação mais precisa do que cada sensor sozinho conseguiria.
- **Relocalization** — capacidade de o sistema "se encontrar" novamente no mapa depois de perder o rastreamento (ex.: câmera coberta por um instante).
- **Loop closure** — em SLAM, reconhecer que o dispositivo voltou a um lugar já mapeado antes, permitindo corrigir erros acumulados no mapa (drift).
