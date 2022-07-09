# Cadastro de Receitas Culinárias

### Funcionalidades
- Criador da receita
    - Ações
        - Login 
        - CRUD
        - Acessar a página de busca
        - Dados
            - Nome
            - email
            - senha
            - Redes sociais
                - logo do instagram
                - Facebook
                - TW

- Utilizador das receitas
    - Cadastro opcional
    - Busca de receitas
    - Favoritar receita
    - Criar listas de receitas

- Buscador
    - Inteligencia em saber se ta logado ou não
    - sugestões (Próximas versões)
    - filtros (PRÓXIMA VERSÃO)
        - Favoritos
        - Qnt de Likes
        - Qnt de Deslikes
        - Qnt Comentários
        - Ordem Cronológica
        - Alfabética
- Receita
    - Grupo (Sobremesa, Almoço, Café da manhã...)
    - Categoria (Dieta, Fitnes, Vegano, BOMm, Comível)
    - Ingredientes
        - Lista específica para cada receita
        - Quantidade
        - Unidade de medida (Cadastrado no banco)

    - Modo de preparo (Apenas uma String) - Prezamos pela liberdade
    - Duração aproximada
    - Rendimento
    - Likes
    - Deslikes
    - Comentários
    - Avaliação (Próxiimas versões),
    - Data de cadastro da receita
    - Data da ultima atualização

### Objetos
- Usuário
    - id
    - mome
    - email 
    - senha
    - Lista de Listas de recitas(Todas, Favoritas, Avulsos...)

- Lista de Receita
    - nome
    - quantidade de receitas
    - Lista de Receitas
    - 
- Receita
    - Id
    - Grupo (Sobremesa, Almoço, Café da manhã, Outros)
    - Categoria (Dieta, Fitnes, Vegano, Outros)
    - Modo de preparo (Apenas uma String) - Prezamos pela liberdade
    - Duração aproximada
    - Rendimento
    - Data de cadastro da receita
    - Data da ultima atualização
    - Lista de Ingredientes
    - Avaliação

- Ingrediente
    - nome
    - quantidade
    - Unidade de medida (Cadastrado no banco)

- Avaliação
    - Likes
    - Comentários
    - Notas (Próxiimas versões)


### Tecnologias
- Back-End
    - Java 17
    - Spring Boot
        - Spring Data JPA
        - Spring Boot Dev Tools
        - Spring Security
    - Flyway
    - Beans Validation
    - Model Mapper
    - Apache Maven
    - Banco (Postgres, MySQL)
    - Git
        - GitHub
- Mobile
    - React Native
    - Typescrypt
    - Expo
    - Yarn
    - React Routes
    - Biblioteca de ícones
- Web
    - React JS
    - typescrypt
    - bootstrap (obs)
    - Yarn
    - React Routes
    - Biblioteca de ícones
### Práticas
- Branches
        - Develop
        - homolog
        - production
- Commits bem feitos
    - Descrição Bem explicativa
    - Não commitar muita coisa em um único commit
-  Tags
    - Gerenciamento de versões
- Quadro Kanban
- Variáveis, métodos, classes, funções, commits TUDO EM INGLÊS 

### Planejamento

- Cadastro do usuário
    - Nome
    - email
    - senha 
        - Minimo 8 Dígitos

- Login
    - Estudar token de login
            - JWT
    - Excluir  Conta
    - Recuperar senha
        - Envio email
        - Envio de SMS (Na conta do Natanael)
    - Alterar senha
    - Alterar email
    - Mensagens de erro
    - Utilizar criptografia de senha

