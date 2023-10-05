(01) Um banco de dados é um conjunto organizado de informações inter-relacionadas, destinado a armazenar e disponibilizar dados relevantes para um contexto específico, 
abrangendo registros, fatos ou conhecimentos, e que tem a finalidade de atender às demandas operacionais e estratégicas de uma organização ou projeto.

(02) Os usuários do banco de dados são indivíduos, aplicativos ou sistemas que interagem com o banco de dados para realizar diversas operações. Podem ser: usuários finais, desenvolvedores, administradores e usuários de consulta.

O esquema define a maneira pela qual as tabelas, campos, relacionamentos, restrições e outros elementos do banco de dados são definidos e organizados. Pode ser: lógico (abstração de alto nível sobre a estrutura dos dados) ou físico
(organização física a nível de disco).

A Linguagem de Definição de Dados é uma categoria de linguagem de programação ou comandos específicos em um Sistema de Gerenciamento de Banco de Dados
que permite aos usuários definir e gerenciar a estrutura do banco de dados. Possibilita CRUD, definições de acesso, restrições, consultas e otimização. 

Consultar os dados em um banco de dados refere-se ao processo de recuperar informações específicas armazenadas no banco de dados de acordo com condições definidos pelo usuário. É possível especificar, filtrar, refinar resultados e ordenar.

Modificar os dados em um banco de dados refere-se ao processo de fazer alterações nos registros existentes para atualizar, adicionar ou excluir informações armazenadas. Modificações podem ser agrupadas em transações tratas como uma
única unidade.

A Linguagem de Consulta em Bancos de Dados é projetada exclusivamente para consulta e recuperação de dados, sem a capacidade de modificar a estrutura do banco de dados ou os dados em si. SELECT, FROM, WHERE, ORDER BY.

A Linguagem de Manipulação de Dados permite aos usuários realizar operações de manipulação, inserção, atualização e exclusão de dados em um banco de dados. INSERT, UPDATE, DELETE, SELECT

Armazenar grande volume de dados em bancos de dados refere-se à capacidade de um sistema de gerenciamento de banco de dados de armazenar, organizar e gerenciar eficientemente um grande volume de informações sem deixar de lado o desempenho,
a escalabilidade, a eficiência, a compreensão e a recuperação.

O acesso eficiente em bancos de dados refere-se à capacidade de recuperar e manipular dados de forma rápida e eficaz, minimizando o tempo e os recursos necessários para realizar operações de consulta e atualização. Utiliza recursos de
otimização, memorização em cache e índices.

A durabilidade garante que, uma vez que uma transação tenha sido confirmada (ou seja, marcada como concluída), todas as mudanças ou modificações feitas durante essa transação permaneçam permanentemente gravadas no banco de dados,
mesmo em face de falhas ou interrupções do sistema. Conta com conceitos de persistência de dados, integridade e recuperação.

A recuperação após falhas em bancos de dados é um processo fundamental que envolve a restauração de um sistema de gerenciamento de banco de dados a um estado consistente e confiável após a ocorrência de falhas ou interrupções inesperadas.
Usa artifícios como Checkpoints, Rollback, Logs de transações e Backups.

Essas falhas podem ser causadas por uma variedade de fatores, como falhas de hardware, falta de energia, erros de software, panes no sistema ou até mesmo desastres naturais.

O uso indevido intencional em bancos de dados refere-se a ações deliberadas e não autorizadas que visam comprometer a segurança, integridade ou confidencialidade dos dados armazenados em um sistema de gerenciamento de banco de dados.Os
ataques podem ser caracterizados como acesso não autorizado, roubo de dados, modificações fraudulentas, negação de serviço, ransomware e demais vulnerabilidades.

Interferências inesperadas entre os usuários em bancos de dados referem-se a situações em que múltiplos usuários ou processos concorrentes acessam e modificam os dados simultaneamente,
resultando em conflitos, inconsistências ou problemas de consistência nos dados armazenados. São caracterizadas como conflitos, concorrência, bloqueios, Deadlocks.

Transações nos dados que são realizadas parcialmente em bancos de dados referem-se a situações em que uma operação que faz parte de uma transação não é executada completamente, 
seja devido a uma falha no sistema, erro de aplicativo ou outra interrupção. Para evitar transações parciais são usados, Rollbacks, Commits, Checkpoints, ACID Atomicidade (todas as operações da transação são executadas ou nenhuma delas é),
Consistência (a transação leva o banco de dados de um estado consistente para outro), Isolamento (as transações concorrentes não interferem umas nas outras) e Durabilidade (as alterações feitas por uma transação são permanentes).

