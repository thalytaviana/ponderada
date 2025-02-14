# Git na Prática: Controlando as Versões de seu Código

## Requisitos do software para um jogo de forca online

&nbsp;&nbsp;&nbsp;&nbsp; O jogo será para jovens e adultos que desejam se tornar profissionais no jogo da velha, e para isso ofereceremos um sistema diferente, sendo que integrará com as redes sociais do usuário para compartilhar resultados e garantir que mais pessoas joguem junto com o usuário.

- Requisitos Funcionais:
    - Partidas Multiplayer com Chat por Voz
        O sistema deve permitir que jogadores conversem em tempo real via chat de voz ou texto durante as partidas.
        Quando a forca estiver prestes a “derrubar” alguém, podem rolar dicas ou “toca” de conversas, aumentando a imersão.

    - Desafios Diários
        O sistema deve disponibilizar desafios diários (semelhante ao Wordle) com palavras especiais ou temas sazonais.

    - Múltiplos Modos de Jogo
        - Modo Clássico: O forca tradicional, com tentativas limitadas.
        - Modo Cooperativo: Dois ou mais jogadores colaboram para adivinhar a palavra antes que as tentativas acabem.
        - Modo Competitivo: Cada jogador tem a sua própria “forca” e quem adivinhar primeiro ganha pontos extras.

    - Suporte a Vários Idiomas com Reconhecimento Automático
        - O sistema deve permitir a escolha de múltiplos idiomas (português, inglês, espanhol, etc.).
        - Ao mudar o idioma, os menus e as palavras do jogo são adaptados automaticamente.
        - O jogador pode alternar entre idiomas durante a partida, se houver permissão do criador da sala.

    - Cadastro e Login
        - O sistema deve permitir que jogadores criem uma conta ou joguem como convidados.
        - Se houver autenticação, o usuário deve poder recuperar senha por meio de e-mail ou outro método definido.
 
    - Gerenciamento de Palavras
        - O sistema deve contar com um banco de palavras, categorizadas por tema ou de forma simples.
        - O sistema deve permitir que um administrador inclua, edite ou remova palavras do banco.

    - Seleção e Exibição da Palavra
        - O sistema deve sortear uma palavra a cada partida de forma aleatória (levando em conta nível de dificuldade ou categorias, se houver).
        - O sistema deve exibir somente a quantidade de letras da palavra, representadas por sublinhados ou traços no lugar das letras.

    - Entrada de Letras e Verificação
        - O sistema deve permitir que o jogador selecione ou digite uma letra por tentativa.
        - O sistema deve verificar se a letra existe na palavra:
        - Se existir, deve revelar todas as ocorrências dessa letra.
        - Se não existir, deve registrar uma tentativa incorreta e atualizar o “boneco” da forca.

    - Controle de Tentativas
        - O sistema deve permitir um número limitado de tentativas (por exemplo, 6 ou 7) antes que o jogador perca a partida.
        - O sistema deve encerrar a partida quando o limite for atingido ou quando a palavra for descoberta.

    - Modo Multiplayer
        - O sistema deve permitir a criação de salas para que dois ou mais jogadores joguem simultaneamente.
        - O sistema deve coordenar turnos ou permitir que todos vejam a mesma palavra, de modo que cada um faça suas tentativas (modo competitivo) ou colaborem (modo cooperativo).

- Requisitos não-funcionais

    - Desempenho
        - O sistema deve carregar a página inicial em até **2 segundos** em condições de conexão com Wi-Fi.
        - O sistema deve processar a entrada de letras em tempo praticamente **instantâneo** para manter a fluidez do jogo.

    - Usabilidade
        - A interface deve ser intuitiva, com botões ou campo de entrada para letras bem destacados.
        - A área visual da “forca” e a indicação das letras certas ou erradas devem ser de fácil compreensão.
        - Em dispositivos móveis, a tela deve se adaptar (layout responsivo) para que o teclado virtual não prejudique a visualização do jogo.

    - Compatibilidade
        - O sistema deve ser compatível com os principais navegadores (Chrome, Firefox, Safari, Edge).
        - O design deve ser responsivo, ajustando-se a diferentes resoluções de tela (desktop, tablet e smartphone).

    - Segurança
        - Se houver cadastro de usuários, os dados de login e senha devem ser armazenados de forma segura (criptografia, HTTPS).
        - Se houver integração com redes sociais ou cadastros externos, utilize protocolos seguros de autenticação (OAuth).

    - Confiabilidade
        - Caso o servidor sofra interrupção, o sistema deve ser capaz de retomar o funcionamento sem perder dados críticos (palavras, pontuações, etc.).
        - Para jogos multiplayer, se a conexão cair, deve haver uma forma de o jogador reconectar-se à partida, se possível.

    - Acessibilidade
        - O sistema deve seguir, na medida do possível, critérios básicos de acessibilidade.
        - Para usuários com limitações, o jogo pode oferecer teclas de atalho para digitar letras, uso de leitores de tela, etc.
