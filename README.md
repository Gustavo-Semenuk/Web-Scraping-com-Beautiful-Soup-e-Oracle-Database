# Web Scraping com Beautiful Soup e Oracle Database

O algortimo de Web Scraping utiliza a biblioteca Beautiful Soup do Python para realizar a raspagem de dados e utiliza também a biblioteca requests para se conectar ao banco de dados Oracle, que é um banco de dados relacional e foi o banco escolhido para aramzenar o texto coletado.

Para conseguir rodar o código com sucesso é necessário realizar algumas alterações de credenciais e da tabela do banco. Nos campos de conexão do banco oracle é necessário você preencher com os seus dados de user, password, dsn e em relação ao comando insert do SQL é necessário você passar o nome da tabela e seus atributos (Lembrando que a tabela que será criada deverá ter três atributos: cd_arquivo, nm_arquivo, ds_conteudo) o atributo cd_arquivo dependendo da sua necessidade poderá ser modificado para um valor aleatório ou sequencial já que o programa roda em loop While poderá continuar coletando e subindo arquivos de forma sequencial.
 