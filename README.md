# git
Comandos do GIT.



================================================COMANDOS GIT================================================

git config --global user.name "nome" => Registrar um nome no git
git config --global user.email "email@email.com => Registar um e-mail no git

git init => Iniciar um reposit�rio local
git init --bare => Iniciar reporit�rio compartilhado (Rede)

git clone "http://endereco..." => Baixa o reposit�rio remoto para maquina local.
git remote => Visualizar o nome do remoto.
git push origin master => Enviar os arquivos "commitados" para remoto (origin e master s�o default).
git pull origin master => Atualiza repositorio local com o remoto.
git fetch origin "branch" => Atualiza outra brach com reposit�rio remoto.

git status => Verificar o status dos arquivos, (Working Directory, Stage Area, Git Directory).
git add arquivo.txt => Adiciona os arquivos a Stage Area (Trocar o arquivo.txt por "." para subir todos os 
		       arquivos ou ".txt" para subir todos os arquivos com extens�o .txt ou outra).
git commit -m "mensagem" => Adiciona os arquivos da Stage Area para o Git Director).
git commit -a -m "mensagem" => Faz o commit direto sem a necessidade de ir para Stage Area.

git diff => Visualiza as mudan�as do Working Directory.
git diff --Staged => Visualiza as mudan�as da Stage area.
git log => Hist�rico dos commits com id e detralhes.
git log -p => Mostra os commits em ordem cronologica (adicionar -1 ao final do comando para 1 commit).
git log --pretty=oneline => Mostra somente o ID e a mensagem dos commits.

git commit --amend -m "Editar um commit" => Editar um commit j� realizado.

git k => visualizar mudan�as na interface grafica.

git reset head arquivo.txt => Voltar ao Working Diretor arquivos da Stage Area.
git checkout -- arquivo.txt => Voltar o commit para a Staged Area.
git rm arquivo.yxy => deletar do git.

git tag => Visualizar todas as tag's.
git tag v1.0 -m "mensagem" => Cria um tag chamada v1.0.
git tag -a v1.0 -m "mensagem" => Cria uma tag anotada chamada v1.0 (Armazena nome e data de quem criou).
git show v1.0 => Mostra detalhes da tag v1.0.

git checkout v1.0 => Mudar para tag v1.0.
git checkout 'master' => Mudar para master.
git tag -d v1.0 => Deleta a tag.

git branch teste => Cria uma branch chamada teste.
git checkout teste => Muda para branch teste.
git merge teste => Merge do teste com a brach atual.
git branch -d teste => Deleta a brach teste.


================================================COMANDOS GIT================================================
