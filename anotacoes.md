

# Anotações de estudo em Git/GitHUb :books:

**GIT - COMANDOS BASICOS (PROMPT DE COMANDO)**

 Windows - Linux   

- Listar = comando dir - ls

- ls -a ( mostra itens ocultos)

- Navegar entre as pastas = cd/ - cd/

- Voltar na navegação = cd.. - cd..

- Limpar tela = cls - clear

- Atalho de autocompletar = tecla TAB

- Criar pasta = mkdir (nome pasta) - mkdir

- Criar arquivo - echo (nome arquivo)>(nome arquivo).txt

- Deletar arquivo = del - 

- Deletar Pasta = rmdir (nome pasta) /s /q

  
------------------------------------------------------------------------------

   **COMO O GIT FUNCIONA POR BAIXA DOS PANOS - (GIT BASH)**

- SHA1 = Algoritmo de criptografia, 40 digitos(unico).

- Comando = openssl sha1 (nome arquivo) = faz a criptografia

  

   **OBJETOS FUNDAMENTAIS (BLOBS, TREES, COMMITS)**

- BLOBS = bloco basico de composição

- TREES = armazena os blobs, aponta para um blob

- COMMIT - Mais importante, aponta para as tree e para os blobs.

- Sistema distribuído seguro

  

**CHAVES SSH E TOKENS**

- Gerar chave SSH =  ssh-keygen -t ed25519 -C (email do github)

ir ate a pasta onde esta a chave ssh
= cd /c/Users/marki/.ssh

ls = para listar chaves

No github se usa a chave publica
= cat id_ed25519.pub

eval $(ssh-agent -s)

ssh-add id_ed25519


-------------------------------------------------------------------

**INICIAR O GIT**

- git init = iniciar o git (criar repositorio)

- git add = mover arquivos

- git commit - fazer o commit

- Markdown é a forma humanizada de escrever o html



----------------------------------------------------------------------

- Untracked - nao se tem conhecimento ainda
- Unmodified - nao foi modificado
- Modified - sofreu modificação
- Staged - Se preparando para outro tipo de agrupamento
- Servidor = Repositorio Remoto
- Ambiente de desenvolvimento = Working directory, Staging Area, Local Repository

COMANDOS:
git status = Fornece o status do arquivo

> git add nomeArquivo
> git add*
> git add.
> git push = empurrar
---------------------------------------------------------------------------

**INTRODUÇÃO AO GITHUB:**


git remote add origin (LINK) = comando repositorio local para o repositorio remoto.

-----------------------------------------------------------------------------------

**RESOLVENDO CONFLITOS:**

Conflito de merge = quando existe uma versão mais atual do mesmo arquivo no github.