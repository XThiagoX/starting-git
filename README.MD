# Scenes

- [X]  Possibilita criar pontos na história da produção do seu projeto.{
        git add landingpage.html
        git commit -m "added landind page"
}

- [x]  Possivel verificar mudanças feitas no seu projeto(Ver o pontos).{
        git log
        git show -> git show 34e53d40f839a923f29da
}

#    Observe que o termial do git diz que você está na linha master -> Thiago@DESKTOP-CUS2S2G MINGW64 ~/Documents/Git (master)
#   É tipo um linha do tempo principal. E se quiser tentar algo novo você pode peger tudo o que tem e alterar em uma linha do tempo alternativa. o que é possivel com o BRANCH 

- [X] É posivel começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.(Universo paralelo){
     git branch arquivo -> Brabch significa ramificação  
     git checkout feature/cart -> se mover para a branch feature/cart
     
     # Voltar para linha do tempo principal{ git checkout master }
     # verificar linhas do tempo{ git Branch }

}
- [X] Adicionar as novas funcionalidades ao seu projeto em produção.{ git merge feature/cart }

- [X] É possivel deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.{  git branch -D feature/cart }

= ` git init ` // Inicia a linha do tempo.
= ` git add ` // Adiciona ou atualiza mudanças para irem para linha todo tempo.
= ` git commit ` // Adiciona um ponto na linha do tempo.
= ` git log ` // Vemos os pontos na linha do tempo / commit.
= ` git status ` // Informa o estado das alerações do nosso projeto.
= ` git show ` // Apresenta determinado show na hitória.
= ` git branch ` // Gerencia novas linha do tempo(`git checkout -b teste` // Cria um nova linha do tempo e já entra nela).
= ` git checkout ` // Manipula as linhas do tempo.
= ` git merge ` // Uni linhas do tempo.
= ` git push ` // Envia alterações de locais para o repositório remoto.
= ` Vim ` Nome do arquivo  // Abre arquivos.
= ` git clone ` // Clonar um projeto/repositório.
= ` git pull ` // Puxa repositório remoto.
= `  ` //
= `  ` //



