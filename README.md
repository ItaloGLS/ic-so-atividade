[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/_tQACOAA)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=24023432&assignment_repo_type=AssignmentRepo)

### A3. Prática em terminal

Execute os seguintes comandos no terminal (Bash, WSL ou Git Bash) e documente a saída:

| Comando | O que faz | Sua saída (resumida) |
|---------|----------|---------------------|
| `whoami` | Identifica o usuário | mostrou o usuario palmares\igls |
| `pwd` | Diretório atual | mostrou a pasta comandos-shell-ItaloGLS |
| `ls -la` (ou `dir`) | Lista com permissões | mostrou os arquivos do repositorio |
| `cat /etc/os-release` (Linux/WSL) | Info do SO | mostrou informacoes do windows |
| `ps aux \| head -10` (ou `tasklist \| head`) | Processos ativos | mostrou processos ativos do sistema |
| `df -h` (ou `wmic logicaldisk`) | Uso de disco | mostrou o uso do disco c |
| `echo "Hello ADS" > teste.txt && cat teste.txt` | Redirecionamento | criou o arquivo teste.txt com hello ads |
| `Get-ChildItem -Recurse -Filter *.md \| Tee-Object lista-md.txt \| Measure-Object` | Lista e conta arquivos `.md` | mostrou 5 arquivos `.md` no repositório |

### A4. Permissões Unix

Traduza as seguintes permissões e responda:

| Simbólico | Octal | Quem pode ler? | Quem pode executar? |
|-----------|-------|----------------|-------------------|
| `-rwxr-xr--` | 754 | dono, grupo e outros | dono e grupo |
| `-rw-r-----` | 640 | dono e grupo | ninguem |
| `drwxrwxrwx` | 777 | todos | todos |

**Conexão com módulo 04:** Explique em 3 linhas como a representação octal de permissões usa o sistema de numeração octal que você estudou.

as permissoes unix usam numeros octais para representar leitura, escrita e execução.  
cada permissao possui um valor numerico que vai de 0 ate 7.  
isso facilita representar permissoes como 754 e 777 de forma simples.
