# Base_de_dados_de_textos

### Esta base contém algumas categorias de textos tais como:
#### - Religião
#### - Esportes
#### - Educação
#### - Saúde
#### - Política


`create table database_text
(
	id serial primary key,
	classe varchar(30),
	narrativa text
);`
