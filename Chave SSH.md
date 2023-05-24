# Dentro do Github navegue
Perfil de usuario > Settings > SSH and GPG keys
New SSH keys

# No terminal (ed25519 é o nome da chave)
ssh-keygen -t ed25519 -C lestathbanger@gmail.com
insira uma senha 

# sera criado as chaves dentro de uma pasta neste caso foi criado no "/home/renato/.ssh/" 
cd 

# no terminal acesse a chave publica com o comando 
cat id_ed25519.pub

-->> ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAINsPRRIt5kUaxhdqZNXQ+eH04rrNDQ2mKUhNXTsFAxoU lestathbanger@gmail.com <<--

# copie o conteudo da chave e cole no Github "ADD SSH Key"

# no terminal use o comando
eval $(ssh-agent -s) 
ssh-add id_ed25519

14:00 min



