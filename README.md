# bibliotecAcessivel
A library administration project grounded in information management principles.

Um projeto de administração de biblioteca fundamentado em princípios da gestão da informação.

# Camada do Modelo (Model):
- É a camada de interação com a base de dados;
- Ela interage com os arquivos do Controller;
- Responsável por resgatar, atualizar, remover e criar dados;
- Normalmente, tabelas serão um Model;

# Camada de visualização (View):
- É onde apresentamos os dados que estão no banco de dados;
- É correto evitar regras de negócio nesta camada ou o mínimo possível;

# Camada de controle (Controller)
- Interação entre Model e View;
- Processamento de dados que foram para o banco ou para a view;


## Estrutura MVC Adotada
- Controllers: pasta que ficam os arquivos de Controller;

- Models: pasta que ficam os arquivos de Model;

- Views: pasta que ficam os arquivos de View;

- Routes: pasta que ficam os arquivos de rotas;

# Projeto bibliotecAcessivel