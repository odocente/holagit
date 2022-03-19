```bash
# Creamos directorio en local e entramos
mkdir holagit
cd holagit
# Creamos os arquivos de texto 
nano hola.txt
nano git.txt
# Configuramos rama por defecto como main
git config --global init.defaultBranch main
# Iniciamos repositorio 
git init 
# Engadimos os arquivos ao repositorio 
git add .
# "Commiteamos" os cambios indicando unha descrición
git commit -m "primeiros arquivos"
# Accedemos a github para crear o repositorio na nube "holagit"
# Conectamos o repositorio local co repositorio na nube
git remote add origin git@github.com:odocente/holagit.git
# Subimos a rama local ao repositorio remoto
git push -u origin main

```
