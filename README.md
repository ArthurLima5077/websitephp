Para conseguir fazer o uso pleno do website é preciso instalar o programa XAMPP que irá servir de servidor para o website ir para o ar.
Outra coisa importante é, após instalar o XAMPP, fazer uma pasta dentro da pasta htdocs chamada "www" e colocar todo o arquivo php desse repositório.
Com o XAMPP aberto, iniciar o Apache e o MYSQL e clicar na opção "Admin"(MYSQL).
Lá será necessário criar seu banco de dados (bd) e criar 3 tabelas. tabela 1: coloque o nome de "sobre" e coloque as seguintes linhas:  (id INT PK AI, titulo VARCHAR(150), descricao TEXT, foto_path VARCHAR(255), created_at TIMESTAMP). tabela 2: coloque o nome de "galeria" e as seguintes linhas: (id INT PK AI, foto_path VARCHAR(255)). tabela 3: coloque o nome de "contato" e as seguintes linhas: (id INT PK AI, titulo VARCHAR(150)), guarde/execute todas essas tabelas.
Com tudo isso feito é só colocar "localhost/www" e clicar enter que o site vai estar disponível.
