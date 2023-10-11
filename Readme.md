# Tutorial Git

## O que é Git?

O **Git** é um sistema de controle de versão de arquivos, usado para rastrear as alterações em arquivos ao longo do tempo. É essencial para o desenvolvimento de software, permitindo o gerenciamento de diferentes versões de arquivos e a colaboração eficiente em projetos. Múltiplos colaboradores podem trabalhar simultaneamente em um projeto, e o Git auxilia na fusão de suas contribuições.

## O que é o GitHub?

O **GitHub** é uma plataforma para hospedar seus repositórios Git. Principais aspectos do GitHub incluem:

- **Repositórios**: É onde você armazena seus projetos e arquivos.
- **Rede social de desenvolvedores**: É uma comunidade de colaboradores que compartilham projetos e ideias.
- **Branch**: É uma ramificação que você cria a partir do projeto principal para trabalhar em recursos ou correções separadamente.
- **Commits**: Representam modificações no código, como adições ou remoções. É necessário enviá-los ao GitHub para atualizar seu projeto.
- **Merge**: É a ação de incorporar as alterações de uma branch em outra, como unir o trabalho em um projeto.
- **Remote**: É uma referência a um repositório remoto, geralmente hospedado no GitHub.
- **Push**: É o ato de enviar commits do seu repositório local para um repositório remoto, como o GitHub.
- **Pull**: É usado para trazer as alterações do repositório remoto para o seu repositório local.
- **Markdown (MD)**: É uma linguagem de marcação usada para escrever READMEs e formatar texto.

### Comandos Git

Aqui estão alguns comandos Git em ordem de uso:

```shell
# Verificar a versão do Git instalada
git --version

# Inicializar um repositório Git vazio, indo diretamente para a branch principal
git init

# Adicionar arquivos à área de "staging" para serem commitados
git add nome-arquivo

# Mostrar o status dos arquivos no repositório
git status

# Comitar as mudanças com uma mensagem descritiva
git commit -m "nome commit"

# Mudar a branch principal para "main"
git branch -M "main"

# Adicionar a referência ao repositório remoto
git remote add origin link-git

# Enviar os arquivos para o GitHub
git push -u origin main

# Adicionar todos os arquivos
git add .

# Limpar mudanças pendentes
git stash

# Criar uma nova branch
git checkout -b nome-da-branch

# Empurrar a nova branch para o repositório remoto
git push -u origin nome-da-branch

# Voltar para a branch principal (geralmente "main")
git checkout main

# Realizar o merge da nova branch na branch principal
git merge nome-da-branch

# Enviar as alterações para o repositório remoto na branch principal
git push origin main

# No GitHub, clique no botão "Code" no repositório que deseja clonar.
# Crie uma nova pasta no seu sistema local.
# Navegue para a pasta onde deseja clonar o repositório.
cd caminho-para-a-pasta

# Clone o repositório
git clone link.git

# Para manter o projeto atualizado, use o comando a seguir no diretório do repositório clonado.
git pull