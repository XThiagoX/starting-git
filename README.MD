# Git and Github
        Tutorial para os passos iniciais para versionamento de código com Git e GitHub.
# Scenes
- [X]  Possibilita criar pontos na história da produção do seu projeto.{<br>
        git add landingpage.html<br>
        git commit -m "added landind page"<br>
}

- [x]  Possível verificar mudanças feitas no seu projeto(Ver o pontos).{<br>
        git log<br>
        git show -> git show 34e53d40f839a923f29da<br>
}

`  Observe que o terminal do git diz que você está na linha master -> Thiago@DESKTOP-CUS2S2G MINGW64 ~/Documents/Git (master)`  
`   É tipo um linha do tempo principal. E se quiser tentar algo novo você pode pegar tudo o que tem e alterar em uma linha do tempo alternativa. o que é possível com o BRANCH `

- [X] É possível começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.(Universo paralelo){<br>
     git branch arquivo -> Branch significa ramificação  <br>
     git checkout feature/cart -> se mover para a branch feature/cart<br>
     
     ` Voltar para linha do tempo principal{ git checkout master } `
     ` verificar linhas do tempo{ git Branch } `

}
- [X] Adicionar as novas funcionalidades ao seu projeto em produção.{<br> git merge feature/cart<br> }

- [X] É possível deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.{ <br> git branch -D feature/cart<br> }

= ` git init ` // Inicia a linha do tempo.<br>
= ` git add ` // Adiciona ou atualiza mudanças para irem para linha todo tempo.<br>
= ` git commit ` // Adiciona um ponto na linha do tempo. <=> ` git commit -am "mensagem" ` Adiciona mudanças e cria o ponto na história.<br>
= ` git log ` // Vemos os pontos na linha do tempo / commit.<br>
= ` git status ` // Informa o estado das alterações do nosso projeto.<br>
= ` git show ` // Apresenta determinado ponto na história.<br>
= ` git branch ` // Gerência novas linha do tempo. <=> `git checkout -b teste.js` // Cria um nova linha do tempo e já entra nela).<br>
= ` git checkout ` // Manipula as linhas do tempo. <=> `git checkout -- teste.html` // Restaura o arquivo desejado na sua ultima versão. Se desejar em algum ponto específico, é só passar o ponto antes dos hifens.<br> 
= ` git merge ` // Uni linhas do tempo.<br>
= ` git push ` // Envia alterações de locais para o repositório remoto.<br>
= ` Vim ` Nome do arquivo  // Abre arquivos.<br>
= ` git clone ` // Clonar um projeto/repositório.<br>
= ` git pull ` // Puxa repositório remoto.<br>

Alterações sendo feitas....
// Criando alterações no arquivo pelo GitHib para usar o `git pull` 



