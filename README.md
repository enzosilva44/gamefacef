# gamefacef

Este projeto é um jogo 2D criado com o Construct 3, onde você controla personagens e interage com objetos como balas e inimigos. O jogo foi desenvolvido como parte de um tutorial para entender os conceitos fundamentais do Construct 3, incluindo a criação de objetos, comportamentos e eventos.

🚀 Tecnologias Usadas
Construct 3: Ferramenta de desenvolvimento de jogos 2D sem a necessidade de programação, utilizada para criar a mecânica do jogo, adicionar comportamentos e eventos.

HTML5: O jogo pode ser exportado como um arquivo HTML5 para ser jogado diretamente em um navegador.

Áudio: Sons e música para melhorar a experiência do jogo.

📂 Estrutura do Projeto
Layout Principal: A cena principal onde o jogo acontece, com a área onde os objetos (jogador, inimigos, balas) são colocados.

Objetos: São os elementos visuais do jogo, como o jogador (personagem), inimigos (goblins), projéteis (balas), e efeitos visuais (sparkflash).

Comportamentos: Cada objeto tem comportamentos específicos, como movimento (Bullet, Fade, etc.), colisões e interações.

🕹️ Como Jogar
Controles:

Espaço: Dispara uma bala (ou feitiço).

Teclas de direção: Movimenta o personagem ou inimigos no jogo.

Objetivos:

O jogador deve evitar os inimigos e disparar as balas para destruí-los.

Balas desaparecem quando atingem os inimigos ou saem da tela.

⚙️ Instruções para Rodar o Jogo Localmente
Pré-requisitos
Construa o jogo usando o Construct 3. Você pode utilizar a versão gratuita ou adquirir uma licença.

Passos:
Clone ou faça o download do projeto para a sua máquina.

Abra o arquivo .c3p no Construct 3.

Edite o projeto conforme necessário (como mudar gráficos, ajustar a jogabilidade ou adicionar novos comportamentos).

Para testar o jogo, clique no botão Play ou pressione F5.

Para exportar o jogo:

Clique em Arquivo > Exportar.

Escolha o formato desejado (ex: HTML5 para web ou .exe para Windows).

🔧 Comportamentos e Eventos Implementados
1. Movimento da Bala (Bullet)
O comportamento Bullet foi adicionado ao objeto Bala para simular um movimento rápido e reto.

As balas se movem na direção em que foram disparadas e desaparecem quando saem da tela (usando o comportamento Destroy Outside Layout).

2. Movimento do Goblin
O objeto Goblin também utiliza o comportamento Bullet, mas com uma velocidade mais baixa, o que o faz se mover de forma mais lenta em direção ao jogador.

3. Comportamento Fade para SparkFlash
O objeto SparkFlash foi adicionado com o comportamento Fade, o que faz ele desaparecer gradualmente depois de ser criado, e ele é destruído automaticamente após o desaparecimento.

4. Eventos de Jogo
Tecla Espaço: Ao pressionar a tecla, uma Bala é criada na posição do jogador.

Movimento: O jogador e os inimigos se movem conforme os comportamentos definidos.

