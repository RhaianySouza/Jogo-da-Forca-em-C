<h1> Jorgo da Forca desenvolvido em C</h1>
Este é um Jogo da Forca desenvolvido em linguagem C, onde o jogador deve adivinhar uma palavra secreta antes de esgotar o número máximo de tentativas. 
O jogo exibe o progresso da palavra, aceita entradas do usuário e verifica se a letra faz parte da palavra secreta.
<h2>Funcionalidades</h2>
✅ Exibe a palavra oculta com _ para letras desconhecidas<br/>
✅ Permite ao jogador inserir letras uma por vez<br/>
✅ Conta o número de tentativas erradas<br/>
✅ Exibe as letras já tentadas<br/>
✅ Condição de vitória e derrota<br/>

<h2>Requisitos do Projeto</h2>

<b>Exibição do jogo:</b>
- Mostrar a palavra oculta, substituindo letras desconhecidas por _.<br/>
- Exibir as tentativas restantes e as letras já tentadas.<br/>

<b>Interação com o jogador:</b>
- Pedir ao jogador para inserir uma letra por tentativa.<br/>
- Validar se a entrada é uma única letra válida (sem números ou caracteres especiais).<br/>

<b>Mecânica do jogo:</b>
- Se a letra estiver na palavra, ela deve ser revelada nas posições corretas.<br/>
- Se a letra não estiver na palavra, reduzir o número de tentativas disponíveis.<br/>
- O jogo continua até o jogador adivinhar a palavra ou esgotar as tentativas.<br/>

<b>Condições de vitória e derrota:</b>
- O jogador vence se adivinhar todas as letras da palavra.<br/>
- O jogador perde se esgotar todas as tentativas antes de completar a palavra.<br/>

<b>Extras (Opcional - Desafio Adicional):</b>
- Adicionar um banco de palavras para escolher aleatoriamente.<br/>
- Desenhar um boneco da forca ASCII conforme os erros aumentam.<br/>
- Permitir que o jogador jogue novamente após ganhar ou perder.<br/>
