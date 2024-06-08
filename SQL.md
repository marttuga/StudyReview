**MYSQL - base de dados RELACIONAL**

## Seleção de Dados  
**SELECT** - selecionar  
**SELECT MIN ( _ )** - selecionar valor mínimo  
**SELECT MAX ( _ )** - selecionar valor máximo  
**SELECT COUNT ( * )** - selecionar a contagem de todos  
**SELECT COUNT ( pessoas ) FROM _ GROUP BY país** - nº de pessoas por país  
**SELECT AVG ( _ )** - selecionar a média  
**SELECT SUM ( _ )** - selecionar a soma  
**SELECT DISTINCT** - selecionar todos os diferentes  
**SELECT _ AS _** - referir o valor por outro nome  

## Filtragem de Dados  
**WHERE** - condição  
**WHERE NOT _** - condição onde não  
**WHERE _ IS NULL** - condição onde é nulo  
**WHERE _ IS NOT NULL** - condição onde não é nulo  

**WHERE 'city' LIKE 'a%'** - cidade começa com a  
**WHERE 'city' LIKE '%a'** - cidade acaba com a  
**WHERE 'city' LIKE '%a%'** - cidade contém a  
**WHERE 'city' LIKE 'a%b'** - cidade começa com a e acaba com b  
**WHERE 'city' NOT LIKE 'a%'** - cidade não começa com a  
**WHERE 'city' LIKE '_a%'** - cidade segunda letra é a  
**WHERE 'city' LIKE '[acs]%'** - cidade começa com a ou c ou s  
**WHERE 'city' LIKE '[a-f]%'** - cidade começa com qualquer letra de a-f  
**WHERE 'city' LIKE '[!acf]%'** - cidade não começa com a ou c ou f  

**WHERE 'city' IN ('a', 'b')** - cidade é a ou b  
**WHERE 'city' NOT IN ('a', 'b')** - cidade não é a nem b  

**WHERE _ BETWEEN 10 AND 20** - valor entre 10 e 20  
**WHERE _ NOT BETWEEN 10 AND 20** - valor não está entre 10 e 20  

## Ordenação de Dados  
**ORDER BY** - ordenar alfabeticamente  
**ORDER BY DESC** - ordenar reversamente  
**ORDER BY a, b** - ordenar primeiro tabela a e depois tabela b  

## Junção de Tabelas  
**FROM** - de  
**FROM c**  
**LEFT JOIN d ON c._ = d._** - tudo de c + as matches de d  
**RIGHT JOIN d ON c._ = d._** - tudo de d + as matches de c  
**INNER JOIN d ON c._ = d._** - os valores iguais nos dois  
**FULL OUTER JOIN d ON c._ = d._** - todos os valores e sem match fica NULL  

## Modificação de Estrutura de Dados  
**CREATE DATABASE _** - criar base de dados  
**DROP DATABASE _** - apagar base de dados  

**CREATE TABLE _** - criar tabela  
**DROP TABLE _** - apagar tabela estrutura e dados  
**TRUNCATE TABLE _** - apagar os dados todas as linhas  

**ALTER TABLE _** - alterar estrutura da tabela  
**ADD _** - adicionar valores na tabela  
**DROP COLUMN _** - apagar uma coluna e os valores da tabela  

**RENAME _ TO _** - renomear para  

## Inserção, Atualização e Exclusão de Dados  
**INSERT INTO _ ( nome, anos, sexo) VALUES ('jorge', 32, masculino)** - inserir valores numa tabela  
**UPDATE _ SET a = 'l'** - alterar o valor de a para l na tabela  
**DELETE FROM _** - eliminar linhas/valores específicos da tabela  

## Condições e Operadores  
**AND** - e  
