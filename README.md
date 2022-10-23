# GitGithub
Principais comandos e certificação.
Obs. Não organizado ainda.






---------------ATALHOS VS CODE------------------

! + tab = preenche corpo html
ctrl + k + t = seus temas

------------------------------------------------

--------------COMANDOS BÁSICOS------------------


cd = change directory <br>
como navegar no terminal do git? <br>
ls = mostrar elementos <br>
clear = limpar <br>
cd ../ = volta uma pasta <br> 
tab = auto complete <br>
mkdir = CRIA PASTA <br>
cd./ + pasta = entra numa pasta <br>
../../ = volta duas pastas <br>
<br>
<br>
------------------ESSENCIAIS-------------------
<br>
<br>
git init = começar repositorio dentro do repositorio <br>
git status = usado para saber se salvou algo ou não, se algo foi alterado, etc <br>
git add . = adicionar tudo que foi mudado na pasta para o git monitorar
git commit -m " " = comitar  <br>
git log = ver histórico de alterações, quem fez e quando fez <br>
git remote add origin https://github.com/danubiaborges/NOMEDOREPOSITORIO = adicionar pasta de destino no github <br>
git remote = mostra para onde será enviado <br>
git push -u origin master = enviar para repositorio de destino no github <br>
git pull origin master = puxar informações adicionadas por terceiros <br>
git config = configurar dados do usuario <br>
git config --global user.name "inserir nome" = configurar nome do usuario <br>
git config user.name = mostra o nome do usuário <br>
git config --global user.email "email do usuario" = configurar email do usuario <br>
git config user.email = mostra email do usuario <br>
branch = ramificação para mais de uma pessoa trabalhar no codigo sem alterar o da outra <br>
git branch = mostra que branchs existentes <br>
git branch danubia = adiciona danubia como uma branch para trabalhar no codigo <br>
git checkout + nome da branch = muda a branch para o nome selecionado <br>
git merge + nome da outra branch = juntar o trabalho de uma branch com o de outra <br>
 <br>
 <br>
--------------------------GIT FLOW---------------------------------
 <br>
 <br>
duas branchs principais: master e develop <br> 
só será enviado para a master quando a aplicação estiver pronta para ser lançada <br>
branches de suporte: hotfix(corrgir bugs na master e dar merge para master novamenmte), release, feature <br> 
branch release = braço auxiliar para corrigir bugs da branch develop <br> <br> <br>
git chechout -b develop = ir para uma branch que não existe e criando ela ao mesmo tempo <br> 
git branch -d + nome da branch = deleta a branch que não é mais necessaria <br>

 <br>
 <br>
-----------------------README/MARKDOWN-----------------------------
 <br>
 <br>
<img src = "caminho da pasta"> <br>
"#" = alterar o tamanho, quanto mais inserir, menor fica <br>
windows + . = emoji <br>
## Abra o [link] (link da página de destino) <br>
**palavra** = negrito <br>
< br > quebra linha <br>
```bash <br>
git clone + inserir link  <br>
```
