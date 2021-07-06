# Bootcamp Santander - DIO

Olá, bem vindo ao meu repositório do curso de GIT & GitHub da **DIgital Inovation One**

Create By Jorge Luiz de Alencar, :eagle:



### Então, vamos lá?

- Primeiro crie uma pasta;
- Use o comando "_cd_ " no terminal do windows para navegar para dentro dessa pasta
- use "_git init_ " para criar um repositório local
- quando adicioanar vários arquivos use o comando "_git add *_"
- Agora, se tiver adicionado apenas um arquivo, use "_git add **nome do arquivo**_"
- Depois de ter movido os arquivos da área "**untraked**" para "**Staged**", use o comando "_Git commit -m **DESCRIÇÃO** " para mover os arquivos do diretório Staged para o diretório "**Unmodified**";
- Se quiser ver se tem alguma alteração, use o comando "_git status_", se tiver alguma coisa para commitar ele vai mostrar.



## ESTADOS DOS ARQUIVOS DO GIT (TRACKED)

- [ ] **UNTRAKED** - Não traçado, ou seja, não está no diretório do GIT
- [ ] **UNMODIFIED** - Não Modificado
- [ ] **MODIFIED** - Modificado (precisa ser Adicionado ao Staged e depois Commitado)
- [ ] **STAGED** - Arquivos esperando para serem Commitados, ou seja, voltam para o estado de Unmodified e subscrevem os arquivos originais. 



## Subindo arquivos para o github

```
-----------------------------------------------------------------------
git remote add origin https://github.com/fergod14nova/DIO_GIT.git
git branch -M main
git push -u origin main
---------------------------------------------------------------------------
```

o comando _git remote -v_ vai listar as listas de repositórios remotos cadastrados.

o comando _git push origin master_ serve para subir os arquivos para o repositório. 

**É necessário fazer autenticação com a conta do github**



### PUXANDO ARQUIVOS DE DENTRO DO GITHUB

<<<<<<< HEAD
Então... O comando é o _git push -u origin main_ ou _git pull origin master_
=======
Então... O comando é o seguinte. git pull origin master

>>>>>>> 7938bf8a8498affc09170fec5a23bd116813ca39

