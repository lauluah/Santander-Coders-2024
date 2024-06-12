<h1 <p align="center">O QUE É GIT?</h1> 

<p align="center"><img src="/image/git.png" alt="Descrição da imagem" width=200 heigth=300>

 - Git é um sistema de controle de versão, que registra mudanças em arquivos, possibilita a recuperação e versões anteriores do codigo. Além disso, permite que os desenvolvedores trabalhem em equipe.
 - É um sistema de controle de versão distribuído, que possibilita o trabalho desconectado, permitindo você faça commits, crie branches e realize outras operações mesmo quando estiver sem conexão com a internet. 
 - É local, então as alterações são instantaneamente registradas, garantindo eficiência e agilidade no processo de desenvolvimento. 

---

<p align="center"><img src="/image/comandos.png" alt="Descrição da imagem" width=200 heigth=300>

1. **git init**:
    - Este comando é usado para iniciar um novo repositório Git em um diretório local. Ele cria um novo repositório vazio ou reinicializa um repositório existente.
2. **git clone [URL]**:
    - Utilizado para criar uma cópia local de um repositório remoto. Ele copia todos os arquivos e histórico de commits do repositório remoto para o seu diretório local.
3. **git add [arquivo(s)]**:
    - Adiciona alterações específicas nos arquivos ao índice (staging area) para prepará-las para o commit. Você pode adicionar arquivos individualmente ou usar "." para adicionar todas as alterações.
4. **git commit -m "[mensagem]"**:
    - Registra as alterações adicionadas ao índice no histórico do repositório. A opção "-m" permite adicionar uma mensagem de commit para descrever as alterações feitas.
5. **git status**:
    - Exibe o estado atual do seu repositório Git. Ele mostra quais arquivos foram modificados, adicionados ou removidos e quais estão prontos para serem commitados.
6. **git push**:
    - Envia os commits locais para o repositório remoto. É usado principalmente para atualizar o repositório remoto com as alterações locais.
7. **git pull**:
    - Atualiza o repositório local com as alterações do repositório remoto. Ele recupera as alterações feitas por outros colaboradores e mescla essas alterações com o seu código local.
8. **git branch [nome_da_branch]**:
    - Cria uma nova branch com o nome especificado. Branches são usadas para trabalhar em novas funcionalidades ou correções de bugs sem interferir no código principal.
9. **git checkout [nome_da_branch]**:
- Altera a branch atual para a branch especificada. Isso permite alternar entre diferentes branches para trabalhar em diferentes partes do projeto.

<h1>COMO ADICIONAR UM CODIGO NO REPOSITÓRIO :</h1>

Passo 1: Inicialização do Repositório Localmente :

 - git init

Este comando inicia um novo repositório Git localmente.

Passo 2: Adicionando Arquivos ao Repositório:

- git add .

Este comando adiciona todos os arquivos ao índice (staging area) para prepará-los para o commit.

Passo 3: Commitando as Alterações:

- git commit -m "First commit"

Este comando registra as alterações no repositório local com uma mensagem de commit.

Passo 4: Conectar ao Repositório Remoto (GitHub) :

- git remote add origin URL_DO_SEU_REPOSITORIO

Este comando conecta seu repositório local ao repositório remoto no GitHub.

Passo 5: Enviando as Alterações para o Repositório Remoto

- git push -u origin master

Este comando envia as alterações do seu repositório local para o repositório remoto no GitHub.

---
# **BRANCHES**

<img src="/image/branch.png" alt="Descrição da imagem" width=200 heigth=300>

<br><p>Uma branch no Git é uma ramificação independente do código, permitindo trabalhar em novas funcionalidades ou correções de bugs sem interferir no código principal. Ela facilita a organização e colaboração em projetos de desenvolvimento, permitindo que diferentes desenvolvedores trabalhem em partes do código simultaneamente. Após concluir o trabalho em uma branch, suas alterações podem ser mescladas de volta ao código principal do projeto.</p>

# **Merging branches**

Merging branches é o processo de combinar o código de uma branch com outra. Isso é útil quando você tem diferentes branches que contêm alterações separadas e deseja incorporar essas alterações em uma única branch.

ex: <br>
git checkout branch_destino <br>
git merge branch_secundaria