# GitGithub
Principais comandos e certificação.
Obs. Não organizado ainda.






---------------ATALHOS VS CODE------------------

! + tab = preenche corpo html
ctrl + k + t = seus temas

------------------------------------------------

--------------COMANDOS BÁSICOS------------------


cd = change directory <br>
como navegar no terminal do git?
ls = mostrar elementos
clear = limpar
cd ../ = volta uma pasta
tab = auto complete
mkdir = CRIA PASTA
cd./ + pasta = entra numa pasta
../../ = volta duas pastas

------------------ESSENCIAIS-------------------

git init = começar repositorio dentro do repositorio
git status = usado para saber se salvou algo ou não, se algo foi alterado, etc
git add . = adicionar tudo que foi mudado na pasta para o git monitorar
git commit -m " " = comitar
git log = ver histórico de alterações, quem fez e quando fez
git remote add origin https://github.com/danubiaborges/NOMEDOREPOSITORIO = adicionar pasta de destino no github
git remote = mostra para onde será enviado
git push -u origin master = enviar para repositorio de destino no github
git pull origin master = puxar informações adicionadas por terceiros
git config = configurar dados do usuario
git config --global user.name "inserir nome" = configurar nome do usuario
git config user.name = mostra o nome do usuário
git config --global user.email "email do usuario" = configurar email do usuario
git config user.email = mostra email do usuario
branch = ramificação para mais de uma pessoa trabalhar no codigo sem alterar o da outra
git branch = mostra que branchs existentes
git branch danubia = adiciona danubia como uma branch para trabalhar no codigo
git checkout + nome da branch = muda a branch para o nome selecionado
git merge + nome da outra branch = juntar o trabalho de uma branch com o de outra

--------------------------GIT FLOW---------------------------------

duas branchs principais: master e develop
só será enviado para a master quando a aplicação estiver pronta para ser lançada
branches de suporte: hotfix(corrgir bugs na master e dar merge para master novamenmte), release, feature
branch release = braço auxiliar para corrigir bugs da branch develop
git chechout -b develop = ir para uma branch que não existe e criando ela ao mesmo tempo
git branch -d + nome da branch = deleta a branch que não é mais necessaria


-----------------------README/MARKDOWN-----------------------------
<img src = "caminho da pasta">
"#" = alterar o tamanho, quanto mais inserir, menor fica
windows + . = emoji
## Abra o [link] (link da página de destino)
**palavra** = negrito
<br> quebra linha
```bash
git clone + inserir link 
```
