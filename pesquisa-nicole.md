# **PESQUISA**

# - **GIT**
# **♡  _conceito geral_:** 
- **Oque é?** O Git é uma ferramenta essencial para o desenvolvimento de software moderno, permitindo o controle de versão eficiente e colaboração em projetos de qualquer escala. Dominar os conceitos fundamentais do Git é crucial para maximizar sua eficácia como desenvolvedor. Vamos explorar esses conceitos de forma organizada e clara:

**1. Controle de Versão:**
O controle de versão é a prática de rastrear e gerenciar as alterações feitas em um conjunto de arquivos ao longo do tempo. O Git oferece um sistema distribuído de controle de versão, o que significa que cada desenvolvedor tem uma cópia completa do repositório localmente.

**2. Repositório:**
Um repositório Git é onde todos os arquivos de um projeto são armazenados, juntamente com seu histórico de alterações. Existem repositórios locais, que residem no computador do desenvolvedor, e repositórios remotos, hospedados em servidores como GitHub, GitLab ou Bitbucket.

**3. Commit:**
Um commit é uma operação que registra as alterações feitas nos arquivos do repositório. Cada commit possui uma mensagem descritiva que resume as mudanças realizadas, fornecendo um histórico detalhado do desenvolvimento do projeto.

**4. Branch:**
Um branch é uma ramificação independente do código em um repositório. Os branches permitem que os desenvolvedores trabalhem em novas funcionalidades ou correções de bugs sem afetar o código principal. Isso facilita o desenvolvimento paralelo e a experimentação segura.

**5. Merge:**
O merge é o processo de combinar as alterações de um branch com outro. Isso é comumente usado para integrar uma funcionalidade desenvolvida em um branch de recurso de volta ao branch principal. O Git é capaz de mesclar automaticamente as alterações sempre que possível, mas em casos de conflitos, pode exigir intervenção manual.

**6. Pull Request:**
Um pull request é uma solicitação para que as alterações feitas em um branch sejam revisadas e incorporadas ao branch principal. É uma prática comum em ambientes de desenvolvimento em equipe, permitindo revisões antes da integração das alterações.

**7. Clone:**
Clonar um repositório é o ato de criar uma cópia local de um repositório remoto em seu próprio sistema. Isso permite que os desenvolvedores trabalhem em projetos sem a necessidade de acesso direto ao repositório remoto, garantindo portabilidade e flexibilidade no desenvolvimento.

**8. Pull e Push:**
Os comandos pull e push são usados para sincronizar os repositórios locais e remotos. O pull atualiza o repositório local com as alterações do repositório remoto, enquanto o push envia as alterações do repositório local para o repositório remoto.

# **♡  _comandos_:**

- _git init_: Inicializa um novo repositório Git no diretório atual.

- _git clone [URL]_: Clona um repositório Git existente para o diretório local.

- _git add [arquivo]_: Adiciona um arquivo ao índice (staging area) para ser incluído no próximo commit.

- _git commit -m "[mensagem]"_: Cria um novo commit contendo as alterações adicionadas ao índice, com uma mensagem descritiva.

- _git status_: Exibe o estado atual do diretório de trabalho e do índice.

- _git log_: Mostra o histórico de commits do repositório, exibindo informações como hash do commit, autor, data e mensagem.

- _git branch_: Lista todas as branches no repositório.

- _git checkout [nome da branch]_: Alterna para uma branch existente.

- _git merge [nome da branch]_: Funde as alterações de uma branch específica na branch atual.

- _git pull_: Atualiza o repositório local com as alterações do repositório remoto.

- _git push_: Envia as alterações locais para o repositório remoto.

- _git remote -v_: Lista os repositórios remotos associados ao repositório local, juntamente com suas URLs.

 ![image](https://github.com/nicpesc/AV1/assets/164904151/984d6949-72e3-4dad-aa1c-994537f24e92)

# - GITHUB

- **Oque é?**

O GitHub é uma plataforma de hospedagem de código-fonte e colaboração para desenvolvedores. Ele utiliza o sistema de controle de versão Git e oferece uma ampla gama de recursos para gerenciar projetos de software.

# **♡  _Principais Recursos do GitHub_:**

- **Repositórios:** Locais onde os arquivos do projeto são armazenados, junto com seu histórico de alterações.
  
- **Issues:** Utilizadas para rastrear tarefas, bugs ou solicitações de recursos em um projeto.
  
- **Pull Requests:** Solicitações para incorporar alterações feitas em um branch de volta ao branch principal do projeto.
  
- **Wikis:** Permitem criar e editar documentação diretamente no repositório.

# **♡  _Como Usar o GitHub?_ :**

1. **Criar uma Conta:** Crie uma conta gratuita no GitHub em https://github.com/join.

2. **Criar um Repositório:** Após fazer login, clique no botão "New" para criar um novo repositório.

3. **Clonar um Repositório:** Para trabalhar em um projeto existente, use o comando `git clone` no terminal.

4. **Contribuir com Pull Requests:** Faça alterações no código, adicione novos recursos ou corrija bugs e envie um pull request para contribuir com projetos.

 
![image](https://github.com/nicpesc/AV1/assets/164904151/598df57f-da68-4240-b101-b147faf86ddf)

# - **Visual Studio Code (VSCode)**
# **♡  _Oque é?_ :**
O Visual Studio Code (VSCode) é um editor de código-fonte desenvolvido pela Microsoft, conhecido por sua leveza, rapidez e extensibilidade. Ele é amplamente utilizado pela comunidade de desenvolvedores devido à sua interface intuitiva e aos recursos poderosos que oferece.

# **♡  _Principais Recursos do VSCode_ :**

- Interface Intuitiva

O VSCode possui uma interface limpa e intuitiva, com uma barra lateral para navegação rápida entre arquivos e pastas, e uma barra de status que fornece informações úteis, como o branch Git atual e as mensagens de feedback do sistema.

- Suporte a Diversas Linguagens

Ele oferece suporte a uma ampla variedade de linguagens de programação, incluindo JavaScript, Python, Java, C++, entre outras. Além disso, possui destaque de sintaxe, sugestões inteligentes de código e integração com depuradores para facilitar o desenvolvimento em diferentes linguagens.

- Extensibilidade

O VSCode é altamente extensível, permitindo que os desenvolvedores personalizem e estendam suas funcionalidades com uma ampla variedade de extensões disponíveis no marketplace. Essas extensões podem adicionar novos recursos, temas, suporte a linguagens adicionais e muito mais.

- Integração com Git

Ele possui integração nativa com o Git, o que facilita o controle de versão do código-fonte diretamente do editor. Os desenvolvedores podem visualizar facilmente as alterações, criar novos commits, criar e mesclar branches, tudo dentro do ambiente do VSCode.

- Terminal Integrado

O VSCode inclui um terminal integrado baseado no terminal do sistema operacional, permitindo que os desenvolvedores executem comandos diretamente do editor. Isso evita a necessidade de alternar entre o editor e o terminal externo durante o desenvolvimento.

# **♡  _Comandos_ :**
Abrir o VSCode: Para abrir o Visual Studio Code, você pode usar o atalho de teclado Ctrl + Shift + P (ou Cmd + Shift + P no macOS) para abrir a paleta de comandos e digitar "Visual Studio Code" e pressionar Enter, ou simplesmente clicar no ícone do VSCode em sua barra de aplicativos.

- Abrir um Arquivo ou Projeto: Use o atalho de teclado Ctrl + O (ou Cmd + O no macOS) para abrir um arquivo ou pasta no VSCode.

- Salvar: Pressione Ctrl + S (ou Cmd + S no macOS) para salvar o arquivo atual.

- Fechar uma Aba: Use o atalho de teclado Ctrl + W (ou Cmd + W no macOS) para fechar a aba do arquivo atual.

- Criar um Novo Arquivo: Pressione Ctrl + N (ou Cmd + N no macOS) para criar um novo arquivo.

- Recortar, Copiar e Colar: Use os atalhos de teclado padrão Ctrl + X, Ctrl + C e Ctrl + V (ou Cmd + X, Cmd + C e Cmd + V no macOS) para recortar, copiar e colar texto, respectivamente.

- Desfazer e Refazer: Use os atalhos de teclado Ctrl + Z e Ctrl + Y (ou Cmd + Z e Cmd + Shift + Z no macOS) para desfazer e refazer ações.

- Abrir Terminal Integrado: Pressione Ctrl + (ou Ctrl + Shift + no macOS) para abrir o terminal integrado do VSCode.

- Executar Comandos: Use o atalho de teclado Ctrl + Shift + P (ou Cmd + Shift + P no macOS) para abrir a paleta de comandos e digitar o comando que deseja executar.

- Navegar entre Abas: Use os atalhos de teclado Ctrl + PgUp e Ctrl + PgDn (ou Ctrl + Shift + ] e Ctrl + Shift + [ no macOS) para navegar entre as abas abertas.

![image](https://github.com/nicpesc/AV1/assets/164904151/c761b687-cf00-4fff-ab56-74833f1e6104)



