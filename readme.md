# Curso de Git e GitHub

Este repositório contém o material e exercícios do curso de **Git e GitHub**, cobrindo desde os conceitos básicos de controle de versão até o uso avançado de ferramentas de colaboração no GitHub.

## 📚 Conteúdo do Curso

1. **Introdução ao Git**
   - Instalação e configuração do Git
   - Conceitos de repositórios, commits e branches
   - Controle de versão distribuído
2. **Trabalhando com Git**
   - Comandos essenciais: `git init`, `clone`, `add`, `commit`, `push`, `pull`
   - Gerenciamento de branches: `git branch`, `checkout`, `merge`
   - Resolução de conflitos
3. **Introdução ao GitHub**
   - Criando repositórios remotos
   - Trabalhando com Pull Requests
   - Issues e colaboração em projetos
4. **Fluxo de Trabalho no GitHub**
   - Forks e contribuições para projetos open-source
   - GitHub Actions e automações
   - Versionamento semântico

## 🛠️ Ferramentas e Tecnologias

- **Git**: Sistema de controle de versão distribuído.
- **GitHub**: Plataforma de hospedagem de código e colaboração.

## 📈 Próximos Passos

Ao final deste curso, você estará apto a utilizar o **Git** para gerenciar versões de código e o **GitHub** para colaborar em projetos com outras pessoas, contribuindo para repositórios open-source ou gerenciando seus próprios projetos.

## ⚙️ Principais Comandos do Git

Aqui está uma lista dos comandos Git mais utilizados:

- **Configuração Inicial:**
  ```bash
  git config --global user.name "Seu Nome"
  git config --global user.email "seuemail@example.com"
  ```

- **Iniciar um Repositório:**
  ```bash
  git init
  ```

- **Adicionar arquivos para o stage:**
  ```bash
  git add .
  ```

- **Fazer um commit:**
  ```bash
  git commit -m "Mensagem do commit"
  ```

- **Verificar o status do repositório:**
  ```bash
  git status
  ```

- **Verificar histórico de commits:**
  ```bash
  git log
  ```

- **Criar uma nova branch:**
  ```bash
  git checkout -b nome-da-branch
  ```

- **Trocar de branch:**
  ```bash
  git checkout nome-da-branch
  ```

- **Fazer merge de uma branch:**
  ```bash
  git merge nome-da-branch
  ```

- **Adicionar um repositório remoto:**
  ```bash
  git remote add origin https://github.com/seuusuario/seurepositorio.git
  ```

- **Enviar commits para o repositório remoto:**
  ```bash
  git push origin nome-da-branch
  ```

- **Enviar commits forçando a operação (com `-f`):**
  > **Atenção:** Use `-f` com cautela, pois ele pode sobrescrever o histórico remoto.
  ```bash
  git push -f origin nome-da-branch
  ```

- **Puxar atualizações do repositório remoto:**
  ```bash
  git pull origin nome-da-branch
  ```

- **Reverter alterações forçadamente:**
  ```bash
  git reset --hard commit-hash
  git push -f origin nome-da-branch
  ```

O uso do `-f` (force) nos comandos `push` e `reset` força a operação mesmo que possa sobrescrever mudanças no repositório remoto. Utilize com cuidado, especialmente em ambientes colaborativos, pois pode afetar o histórico de commits.

## 📜 Ordem de Comandos para Depositar em um Repositório já Existente

Caso você já tenha um repositório Git configurado localmente e queira enviar seus arquivos para um repositório existente no GitHub, siga esses passos:

1. **Inicializar o repositório (se ainda não estiver inicializado):**
   ```bash
   git init
   ```

2. **Adicionar todos os arquivos ao stage:**
   ```bash
   git add .
   ```

3. **Fazer o commit dos arquivos:**
   ```bash
   git commit -m "Primeiro commit"
   ```

4. **Adicionar o repositório remoto (substitua pelo seu repositório no GitHub):**
   ```bash
   git remote add origin https://github.com/seuusuario/seurepositorio.git
   ```

5. **Enviar os arquivos para o repositório remoto:**
   ```bash
   git push -u origin main
   ```

Se sua branch principal não for `main`, substitua por `master` ou o nome da sua branch padrão.

## 🤝 Contribuição

Contribuições são bem-vindas! Se encontrar problemas ou tiver sugestões, fique à vontade para abrir uma issue ou enviar um pull request.
