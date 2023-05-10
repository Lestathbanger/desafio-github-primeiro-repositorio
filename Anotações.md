Comando:
# Copiar arquivo do github para o computador local
git clone 'link HTTP'

# Visualiza o estado do github
git status 

# Adiciona os arquivos para o github (passa a informação para o Github considerar aquele arquivos como sendo um controle de versão)
# o ponto ( . ) significa que vai ser todos os arquivos
git add .

# Cria um commit
# -m para adicionar uma mensagem
git commit -m "Inclusão no  arquivo de anotações com comandos para envio de arquivo para o Github"

# Termina de enviar o arquivo para o Github
git push origin main
