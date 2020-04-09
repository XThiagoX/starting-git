# Git and Github
# Scenes

- [X]  Possibilita criar pontos na história da produção do seu projeto.{<br>
        git add landingpage.html<br>
        git commit -m "added landind page"<br>
}

- [x]  Possivel verificar mudanças feitas no seu projeto(Ver o pontos).{<br>
        git log<br>
        git show -> git show 34e53d40f839a923f29da<br>
}

`  Observe que o termial do git diz que você está na linha master -> Thiago@DESKTOP-CUS2S2G MINGW64 ~/Documents/Git (master)`  
`   É tipo um linha do tempo principal. E se quiser tentar algo novo você pode peger tudo o que tem e alterar em uma linha do tempo alternativa. o que é possivel com o BRANCH `

- [X] É posivel começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.(Universo paralelo){<br>
     git branch arquivo -> Brabch significa ramificação  <br>
     git checkout feature/cart -> se mover para a branch feature/cart<br>
     
     ` Voltar para linha do tempo principal{ git checkout master } `
     ` verificar linhas do tempo{ git Branch } `

}
- [X] Adicionar as novas funcionalidades ao seu projeto em produção.{<br> git merge feature/cart<br> }

- [X] É possivel deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.{ <br> git branch -D feature/cart<br> }

= ` git init ` // Inicia a linha do tempo.<br>
= ` git add ` // Adiciona ou atualiza mudanças para irem para linha todo tempo.<br>
= ` git commit ` // Adiciona um ponto na linha do tempo.<br>
= ` git log ` // Vemos os pontos na linha do tempo / commit.<br>
= ` git status ` // Informa o estado das alerações do nosso projeto.<br>
= ` git show ` // Apresenta determinado show na hitória.<br>
= ` git branch ` // Gerencia novas linha do tempo. <=> `git checkout -b teste` // Cria um nova linha do tempo e já entra nela).<br>
= ` git checkout ` // Manipula as linhas do tempo.<br>
= ` git merge ` // Uni linhas do tempo.<br>
= ` git push ` // Envia alterações de locais para o repositório remoto.<br>
= ` Vim ` Nome do arquivo  // Abre arquivos.<br>
= ` git clone ` // Clonar um projeto/repositório.<br>
= ` git pull ` // Puxa repositório remoto.<br>



