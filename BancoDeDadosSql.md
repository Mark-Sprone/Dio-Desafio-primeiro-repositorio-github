**BANCO DE DADOS SQL**

- Tudo são dados
- NoSql 

- Banco de dados= Podemos considerar uma coleção de palavrar, que dentre elas há relacionamentos entre dados, constituindo então um banco de dados.

- SGBD = Sistema de gerenciamento de banco de dados

- DBMS - Data Base Management System



SGBDs:

- Definição: Tipo de dados, estrutura, constrains
- Construção: Inserção de dados
- Manipulação: Relatórios, Recuperação
- Compartilhamento: Simultaneidade, Acesso

- Metadados= Informações que fornecem uma descrição concisa dos dados contidos no BD

- Compartilhamento: Por padrão o BD realiza o bloqueio e a liberação das tabelas.

------------------------------------------



**BREVE HISTÓRICO**

- Modelo relacional surgiu em 1970, criado por Ted Codd, cáculo em álgebra relacional
- Motivação de reduzir o custo com pessoal
- NoSql - Surgiram em 2000

Modelo Hierárquico:
Registros= Links e dados
TAD tree= com raiz

Modelo em Rede:
Relacionamento= N:M

CODASYL
Links= Ponteiros de nós

-----------------------------------------------------------------------------------------------------------------------------------------------------------



**MODELO RELACIONAL**

Usuarios de BDs= User convencional e Administrador do BD ( BD: Banco de dados)

Definição das tabelas e constrains para dados
Comandos traduzidos pelo processador LDD ( Linguagem de Definição de Dados)

Tradução - Mec. Execução - Gerenciador - Metadados e Schema



Usuario Convencional:

- Altera e extrai informações
- Duráveis



Transações: LMD(Linguagem de definição de dados) ( Agrupa para executar)


STORAGE E BUFFER
- Gerenciador de armazenamento (movimento)
- Gerenciador de buffer(troca)
- Ações
- Dados

---------------------------------------------------



**SGBDs MAIS UTILIZADOS NO MERCADO**

1 - Oracle, 2 MySql, 3 Microsoft SQL Server, 4 Postgre SQL, 5 mongoDB, 6 redis.


Influencia na escolha:

popularidade, Tempo de mercado, Documentação, robustez, confiabilidade, segurança, multiplataforma.



A ERA DOS DADOS E O FUTURO DA MODELAGEM

Contexto dos dados:
- Papel central - sistemas corporativos
- Maioria das situações: Min/Max , COUNT, MÈDIA, SOMA.


QUARTO PARADIGMA:
- Instrumentos e simulações que geram grande volume de dados.
- Novo modelo: base na análise e exploração de dados(e-ciencia).
- Modelo anterior: empírico, teórico e computacional.

Requisitos: Composição, execução, análise, abstração, reprodutividade, reutilização, escalabilidade.



Experimentos em larga escala:

- Paralelismo= Múltiplos processadores operando concorrentemente
- Big Data= Processamento paralelo de dados persistentes e particionados.
- Cloud= Recursos de terceiros, soluções de tecnologia como serviço;


HPC - HIGH PERFORMANCE COMPUTING
- Nós de processamento
- Sistema de arquivos paralelos, sem persistência.
- Modelos: MPI, OpenMP, OpenCL
- Acesso: HFF5 e NetCDF


BIG DATA
- Process e Storage: nós de processamento
- Sistema de arquivos paralelos, persistente
- Modelos: MapReduce, Spark, SGBDs paralelos
---------------------------------------------------------------------------------



**MERCADO DE DATA**

- Engenheiro de dados
Desenho, contrução
Sustenação das soluções de dados

- Cientista de dados
Modelagem
Reconhecimento de padrões, predição

- Analista de dados
Criação de dashboards
Apresentação visual dos dados

- Data Driven
Abordagem: análise, interpretação

- Modelos NoSQL
documentos, Wide columms, key value, grafos, orientado a objetos


NoSQL = 

Ex mongoDB (documentos)
- Orientado a documentos
- baixa curva de aprendizado
- baseado em json
- escalabilidade horizontal
- multiplataforma
- Transações ACID para multi documento
- Consultas: Suporta javascript

Wide-Columns = Cassandra

Key-Value = redis

Grafos = neo4j

Orientado a objetos = db4objects
