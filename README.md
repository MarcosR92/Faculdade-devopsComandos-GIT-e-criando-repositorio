AC2  
Marcos Roberto de Castro Pinto  
R.A. 1902912  
  
Exemplo comando Clone:  
1 - Criando um repositório via interface web (print_01)  
2 - Mostrando o repositorio criado e o local onde esta o link para efetuar o clone (print_02)  
3 - ls (print_03 mostrando o diretório vazio)  
4 - git clone + link(print_04)  
5 - mostrando o repositório sendo clonado, entrando no repositório e mostrando o conteúdo (print_05)  
  
Exemplo comando Add:  
1 - mostrando os arquivos presentes no 'working directory' (print_06)  
2 - git add +nome_do_arquivo(print_07 mostrando adicionando apenas 1 arquivo ao 'staging area'[em verde] e os demais no 'working directory'[em vermelho])  
3 - git add --all (print_08, comando para adicionar todos arquivos de uma vez)  
4 - git status (print_09 mostrando todos arquivos adicionados ao 'staging area')  
  
Exemplo comando Commit:  
1 - git commit -m "mensagem"(print_10 mostrando o comando e uma mensagem a ser comentada no commit)  
2 - comando efetuado (print_11 mostrando as atualizações)  
  
Exemplo comando Push:  
1 - git status (mostrando que o repositório local esta a 1 commit à frente do master do repositório remoto)  
2 - git push (print_13)  
3 - comando executado (print_14 mostrando as atualizações)  
4 - git status (print_15 mostrando que os repositórios estão atualizados)  
  
Exemplo comando Fetch:  
1 - git fetch (print_16 mostrando que, ao dar o comando git status, mostra que o repositório local estaria atualizado juntamente com o remoto, porém ao efetuar o comando git fetch, ele atualiza e mostra que houve modificações no repositório remoto)  

Exemplo comando Pull:  
1 - git pull (print_17 mostrando a atualização e que ao dar o comando git status, o repositório local esta atualizado com o remoto[saindo o 1 commit atrás que estava presente no print_16])  

Exemplo comando Checkout:  
1 - git checkout + nome da branch(print_18 mostrando a mudança dos arquivos no repositório local conforme muda do master para branch1 e da branch1 para master)  