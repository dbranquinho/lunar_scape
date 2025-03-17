## `Coding With Google AI Studio` - An Experience...

Creating a Game with prompts *`The Coders will be gone?`*

<hr>

![](https://img.shields.io/badge/IA-LLM-yellow) ![](https://img.shields.io/badge/html-5.0-blue) ![](https://img.shields.io/badge/css-3.0-lightblue) ![](https://img.shields.io/badge/Licence-MIT-lightgray) ![](https://img.shields.io/badge/status-Release-darkgreen) ![](https://img.shields.io/badge/pipeline-passed-green) ![](https://img.shields.io/badge/testing-passing-green) ![](https://img.shields.io/badge/Java-Script-brown)



### Desenvolvimento do Jogo Lunar Scape: Uma Odisseia de Códigos na Lua

Este projeto, intitulado "Lunar Scape", representa uma jornada desafiadora através do desenvolvimento de um jogo web que combina elementos de estratégia, simulação e exploração lunar. O jogo foi concebido para ser executado diretamente em navegadores, sem a necessidade de instalação de pacotes, utilizando HTML, CSS e JavaScript como tecnologias principais.

### Tecnologias Empregadas:
**HTML** (HyperText Markup Language): Utilizado para estruturar a página web, definindo os elementos como containers, imagens, botões e texto. O HTML forneceu a base para a interface do jogo e a organização dos componentes visuais.

**CSS** (Cascading Style Sheets): Empregado para estilizar a aparência do jogo, definindo cores, fontes, layouts e o posicionamento dos elementos na tela. O CSS foi essencial para criar um ambiente visual imersivo e agradável, refletindo o tema lunar e futurista do jogo.

**JavaScript**: A espinha dorsal da interatividade e da lógica do jogo. JavaScript foi usado para:

- Gerenciar o estado do jogo (recursos, posição do jogador, inventário).
- Implementar a lógica de movimento do jogador e as restrições do ambiente.
- Criar elementos dinamicamente (como a matriz do mapa).
- Manipular o DOM (Document Object Model) para atualizar a interface do usuário em resposta às ações do jogador.
- Implementar os pop-ups de descarte e de morte.
- Gerenciar a comunicação entre diferentes páginas do - jogo (scape.html, bunker.html, lab.html).
- 

### Abordagem de Desenvolvimento:

O desenvolvimento do Lunar Scape seguiu uma abordagem iterativa e incremental, com foco na construção de um esqueleto funcional do jogo e, em seguida, adicionando complexidade e recursos gradualmente.

**Estrutura Básica**: Inicialmente, foram criados os arquivos HTML básicos (index.html, scape.html, bunker.html, lab.html) e a estrutura de diretórios para organizar os arquivos CSS e de imagem.

**Interface Inicial**: O index.html foi estilizado com uma imagem de fundo temática e um botão "Iniciar Jogo", utilizando CSS para posicionamento e aparência. Um console rolante foi adicionado para fornecer contexto ao jogador.

**Mapa e Movimento**: A página scape.html foi desenvolvida para exibir um mapa lunar gerado dinamicamente como uma matriz de células. A lógica de movimento do jogador foi implementada, juntamente com restrições de movimento e decaimento de recursos.

**Cenários Adicionais**: As páginas bunker.html e lab.html foram criadas para representar ambientes internos, com seus próprios layouts, restrições de movimento e desafios.

**Persistência de Dados e Comunicação entre Páginas**: Um dos desafios mais complexos foi garantir que os dados do jogo (recursos, inventário, posição do jogador) fossem preservados ao navegar entre as páginas. Isso foi resolvido utilizando parâmetros na URL para transmitir os dados entre as páginas.

**Refinamento e Correção de Bugs**: Ao longo do processo de desenvolvimento, vários bugs e inconsistências foram identificados e corrigidos, incluindo problemas com a lógica de movimento, a exibição da posição do jogador e o tratamento de erros.

**Complexidade e Desafios:**

### O desenvolvimento do Lunar Scape envolveu vários desafios complexos.

**Gerenciamento de Estado**: Manter o controle do estado do jogo em um ambiente sem servidor exigiu o uso cuidadoso de variáveis globais e a transmissão de dados entre páginas.

**Restrições de Movimento**: Implementar restrições de movimento complexas (por exemplo, permitir o movimento apenas em certas linhas e colunas) exigiu lógica precisa e testes rigorosos.

**Interação com o DOM**: A manipulação dinâmica do DOM para criar a matriz do mapa, atualizar a interface do usuário e exibir pop-ups exigiu um bom entendimento do JavaScript e do DOM.

**Coordenação entre Páginas**: Garantir que as páginas do jogo funcionassem em conjunto, preservando o estado do jogo e permitindo a transição perfeita entre os ambientes, foi um desafio significativo.

### Conclusão

O projeto Lunar Scape demonstrou a viabilidade de criar um jogo web complexo e envolvente utilizando apenas HTML, CSS e JavaScript. Embora o jogo ainda possa ser expandido com novos recursos e melhorias, ele representa um marco importante no desenvolvimento de jogos web sem a necessidade de frameworks ou bibliotecas externas. A experiência adquirida neste projeto certamente será valiosa para futuros empreendimentos de desenvolvimento web.