# Entrega: Jornada DevOps com AWS - Impulso
##  Script de Criação de Estrutura de Usuários, Diretórios e Permissões
 
### Diretórios
- /publico
- /adm
- /ven
- /sec

### Grupos 
- GPR_ADM
- GPR_VEN
- GPR_SEC

### Usuários
#### Usuários do grupo GRP_ADM
- Carlos
- Maria
- Joao
#### Usuários do grupo GRP_VEN
- Debora
- Sebastiana
- Roberto
#### Usuários do grupo GRP_SEC
- Josefina
- Amanda
- Rogerio

## Regras
- Provisionamento será feito via script;
- O dono de todos os diretórios será o usuário root;
- Todos os usuários terão permissão total dentro do diretório público;
- Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
- Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem;
