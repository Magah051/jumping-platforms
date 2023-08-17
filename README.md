# Jumping Platforms

<i>Este é um pequeno projeto contendo uma cena de jogo de plataforma feito em Javascript. Diversos conceitos foram aplicados aqui, dentre eles:
- Animação de personagem
- Movimentação de câmera vertical
- Movimentação de câmera horizontal
- Uso de plataformas
</i>  
<hr>

## Detalhes
Este projeto é uma parte de um jogo 2D feito em JavaScript, onde você controla um personagem em um mundo de plataforma. Pense nisso como um jogo clássico de "pular e correr". A área onde o personagem se move é desenhada em um quadro chamado "canvas". O objetivo é fazer o personagem se mover, pular e interagir com o ambiente.

O jogo começa configurando o quadro do jogo, o que é como criar o espaço onde tudo acontecerá. Existem blocos de colisão que representam as coisas com as quais o personagem pode colidir, como plataformas ou paredes.

O personagem é criado com diferentes animações. Você verá o personagem parado, correndo, pulando e caindo. O jogo monitora as teclas que você pressiona no teclado. Se você pressionar a tecla "d", o personagem vai para a direita, e se pressionar a tecla "a", ele vai para a esquerda. A tecla "w" faz o personagem pular.

A função "animate" é importante. Ela faz o jogo acontecer. A cada quadro, o jogo limpa o quadro, desenha o cenário (o fundo), e então atualiza a posição do personagem. O personagem se move e muda sua animação de acordo com o que você pressiona. Isso cria a sensação de movimento e ação.

O jogo também tem um truque. A câmera se move para cima e para baixo enquanto o personagem pula ou cai, o que dá a sensação de que o personagem está se movendo verticalmente pelo mundo do jogo.

Em resumo, o código é um esqueleto de um jogo 2D onde você controla um personagem que pode correr, pular e interagir com plataformas. O quadro é atualizado constantemente para criar a sensação de movimento, e a câmera ajuda a tornar o jogo mais envolvente.

### Como testar?
- Acesse o link na descrição deste repositório.
- Use as teclas "a", "d", "w" e "s" do seu teclado para mover o personagem.

### Veja o game
![ezgif-5-e8b19a0145](https://github.com/Magah051/jumping-platforms/assets/31749933/ccc5c826-fcf3-4c5a-a67d-6f0a9873d5a5)
