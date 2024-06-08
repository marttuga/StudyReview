*MONGODB - base de dados NOSQL - orientada a DOCUMENTOS*


## Visualização e Seleção de Bases de Dados
*show dbs* - todas as bases de dados

*use nome_da_base_de_dados* - seleciona a base de dados, se a base de dados não existir, ela será criada na primeira inserção de dados

*show collections* - lista todas as coleções na base de dados atual



## Criação de Coleções
*db.createCollection( "produtos" )* - cria nova coleção produtos



## Inserção de Documentos
*db.produtos.**insertMany**( object )* - object(array de documentos), o insertMany insere todos os documentos duma vez

*db.produtos.**insertOne**({ chave: "valor" })* - insere um único documento na coleção especificada



## Consulta de Documentos
*db.produtos.**find**( {category: "Tech"} )* - encontra todos com a categoria Tech

*db.produtos.find( { preço: { **$gt**: 10 }})* - encontra todos com um $gt preço maior que 10

*db.produtos.find()* - retorna todos os documentos na coleção

*db.produtos.**findOne**({ chave: "valor" })* - retorna um único documento que corresponda ao critério de busca

*db.produtos.find().**sort**({ chave: 1 })* - ordena os resultados da busca (1 para crescente, -1 para decrescente)

*db.produtos.find().**limit(5)*** - limita o número de resultados retornados

*db.produtos.**countDocuments**({ chave: "valor" })* - conta o número de documentos que correspondem ao critério de busca

*db.produtos.find({ "subdocumento.chave": "valor" })* - busca documentos com critérios aplicados a campos de subdocumentos

*db.produtos.find({ **$text**: { **$search**: "termo" }})* - realiza uma busca full-text



## Atualização de Documentos
*db.produtos.**update**({ nome:"livro"}, { **$set**: {preço : 10 }}, { **upsert: true** })* - set substitui valor e o upsert atualiza documento existente, caso não haja, insere um novo

*db.produtos.**updateMany**({ nome:"livro"}, { $set: {preço : 10 }}, { upsert: true })* - atualiza valores de todos os docs

*db.produtos.**updateOne**({ nome: "livro" }, { $set: { preço: 10 }}, { upsert: true })* - atualiza o primeiro documento que corresponde ao critério de busca ou insere um novo documento se não houver correspondência

*db.produtos.updateMany({ nome: "livro" }, { $set: { preço: 10 }}, { upsert: true })* - atualiza todos os documentos que correspondem ao critério de busca ou insere novos documentos se não houver correspondência

*db.produtos.updateOne({ chave: "valor" }, { **$inc**: { contador: 1 }})* - incrementa o valor de um campo numérico

*db.produtos.updateOne({ chave: "valor" }, { **$push**: { array: "novo_elemento" }})* - adiciona um novo elemento ao array especificado

*db.produtos.updateOne({ chave: "valor" }, { **$pull**: { array: "elemento_a_remover" }})* - remove um elemento específico de um array



## Exclusão de Documentos
*db.produtos.**deleteMany**( {category: "Tech"} )* - apaga todos com a categoria Tech

*db.produtos.**deleteOne**({ chave: "valor" })* - exclui um único documento que corresponda ao critério de busca



## Indexação
*db.produtos.**createIndex**({ chave: 1 })* - cria um índice para um campo, melhorando o desempenho de consultas (1 para crescente, -1 para decrescente)

*db.produtos.createIndex({ campo: "text" })* - cria um índice de texto para busca full-text



## Agregação
*db.produtos.**aggregate**( [ { **$match**: {data: { **$gte**: new Date("2024-03-01")}}}, { **$group**: { _id: "$produto", total_vendas: { **$sum**: "$valor"}}}])* - juntar vários estágios, calcular o total de vendas de cada produto($sum) nos últimos três meses($match,$gte)

*db.produtos.aggregate([ { $match: { chave: "valor" }}, { $count: "total_documentos" }])* - conta documentos que correspondem ao critério de busca usando o pipeline de agregação
