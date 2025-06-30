
📦 Comandos Básicos do Git
🔧 Configuração Inicial
bash
Copiar
Editar
# Configura o nome de usuário
git config --global user.name "Seu Nome"

# Configura o e-mail do usuário
git config --global user.email "seuemail@exemplo.com"

# Verifica as configurações atuais
git config --list
📁 Criar e Iniciar um Repositório
bash
Copiar
Editar
# Cria um novo repositório Git
git init
📄 Trabalhando com Arquivos
bash
Copiar
Editar
# Verifica o status dos arquivos
git status

# Adiciona um ou mais arquivos à área de staging
git add nome-do-arquivo     # Para um arquivo específico
git add .                   # Para todos os arquivos alterados

# Faz um commit com mensagem descritiva
git commit -m "Mensagem do commit"
🌐 Conectando ao GitHub
bash
Copiar
Editar
# Adiciona um repositório remoto
git remote add origin https://github.com/usuario/repositorio.git

# Verifica os repositórios remotos
git remote -v
⬆️ Enviando para o GitHub
bash
Copiar
Editar
# Envia os commits para o repositório remoto (primeiro push)
git push -u origin main

# Envia as próximas alterações
git push
⬇️ Clonar um Repositório
bash
Copiar
Editar
# Clona um repositório existente
git clone https://github.com/usuario/repositorio.git
🌀 Atualizando o Repositório Local
bash
Copiar
Editar
# Puxa as últimas alterações do repositório remoto
git pull
