# 1Trabalho-git-hub
# Trabalho sobre Comandos Git

## Integrantes
- Joardson
- Juliana Sayuri
- Yago
- Emanuelly
- Arthur

---

# Comandos do Git e suas Funções

## `git init`
O comando `git init` é usado para inicializar um novo repositório Git.  
Ele cria a estrutura necessária para começar o controle de versões do projeto.

### Exemplo:
```bash
git init
```

---

## `git add`
O comando `git add` prepara as alterações dos arquivos locais para serem confirmadas no próximo commit.  
Ele adiciona os arquivos para a área de *staging*.

### Exemplo:
```bash
git add .
```

---

## `git status`
O comando `git status` serve para verificar o estado atual do repositório.  
Ele mostra:
- Em qual branch (ramificação) você está;
- Quais arquivos foram modificados;
- Quais arquivos estão preparados para o commit.

### Exemplo:
```bash
git status
```

---

## `git config`
O comando `git config` serve para visualizar e definir preferências e variáveis que controlam a aparência e o comportamento do Git.

### Exemplo:
```bash
git config --global user.name "Seu Nome"
```

---

## `git commit`
O comando `git commit` serve para criar um instantâneo do código no repositório local.  
Ele funciona como um ponto de salvamento das alterações realizadas.

### Exemplo:
```bash
git commit -m "Primeiro commit"
```

---

## `git log`
O comando `git log` serve para visualizar o histórico de commits, mostrando as versões salvas no repositório.

---

# 7 Versionamento em Nuvem

O versionamento em nuvem permite armazenar projetos em servidores online, facilitando o acesso, backup e trabalho em equipe.

---

## 7.1 Serviços

Existem diversas plataformas que oferecem hospedagem para repositórios Git.

---

### 7.1.1 GitHub

O GitHub é a plataforma mais popular para hospedagem de projetos Git.

Principais funcionalidades:
- Armazenamento de código
- Controle de versões
- Trabalho em equipe
- Pull Requests
- Issues

Site oficial:
https://github.com

---

### 7.1.2 BitBucket

O BitBucket é um serviço de hospedagem Git desenvolvido pela Atlassian.

É bastante utilizado por empresas e integrado com ferramentas como Jira e Trello.

Principais funcionalidades:
- Repositórios privados
- Integração com ferramentas Atlassian
- Controle de versões
- Colaboração em equipe

Site oficial:
https://bitbucket.org

---

### 7.1.3 Azure Repository

O Azure Repos faz parte do Azure DevOps da Microsoft.

Ele oferece hospedagem Git para equipes de desenvolvimento.

Principais funcionalidades:
- Controle de versões Git
- Integração com Azure DevOps
- Pipelines de CI/CD
- Gerenciamento corporativo

Site oficial:
https://azure.microsoft.com/products/devops

---

## 7.2 Pull Requests

Pull Request é uma solicitação para adicionar alterações feitas em uma branch para outra branch do projeto.

Esse recurso permite:
- Revisão de código
- Comentários
- Aprovação de alterações
- Trabalho colaborativo

Fluxo básico:
1. Criar uma branch
2. Fazer alterações
3. Enviar para o repositório remoto
4. Abrir Pull Request
5. Revisar e aprovar alterações

---

## 7.3 Resolução de Conflitos

Conflitos acontecem quando duas pessoas alteram a mesma parte de um arquivo.

O Git identifica os conflitos e solicita que o desenvolvedor escolha quais alterações devem permanecer.

Etapas:
1. Identificação do conflito
2. Edição manual do arquivo
3. Salvamento das alterações
4. Novo commit

Exemplo de comandos após resolver:

```bash
git add .
git commit -m "Conflito resolvido"
```

---

# Conclusão

Aprendemos que o Git é uma ferramenta essencial para o controle de versões, permitindo registrar alterações em projetos, voltar versões anteriores e organizar o desenvolvimento de forma mais segura. Além disso, o uso de plataformas de versionamento em nuvem, como GitHub, BitBucket e Azure Repos, facilita o armazenamento online e o trabalho em equipe, tornando a colaboração mais eficiente e organizada.
