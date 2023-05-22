# <img height="40" src="https://user-images.githubusercontent.com/84249945/219458363-0df46081-95bd-4878-a828-541457541cbd.png"/> Sobre
Repositório a fim de estudos seguindo curso de Git e Github.

# :hammer: Comandos principais
* Iniciar repositório local: `git init`
* Verificar alterações: `git status`
* Adiconar arquivos ao Git: `git add <file>` ou `git add .` (o "." indica que será adicionado todos os arquivos criados/modificados)
* Commitar arquivos: `git commit <file> -m "Mensagem de commit"` ou `git commit -m "Mensagem de commit"` (este último realiza commits para todos os arquivos adicionados)
* Enviar para o repositório: Se desejar pode-se criar e definir a branch principal com o comando `git branch -M main`, em seguida adicionar a origem do repo remoto ao repo local `git remote add origin <link do repo>`. Por fim, enviar os arquivos com `git push -u origin main`
* Receber alterações/atualizações do projeto: `git pull`
* Clonar repositório: `git clone <link do repo>`
* Acessar logs: `git log`
* Reverter arquivos com <b>checkout</b>: `git checkout <file>`
* Resetando arquivos: `git reset --hard origin/main`
