# API Escola

Uma API em Django Rest Framework para gerenciar um sistema escolar, incluindo gestão de alunos, cursos e matrículas.

## Funcionalidades

- **Gerenciamento de Alunos**: Criar, ler, atualizar e excluir registros de alunos.
- **Gerenciamento de Cursos**: Gerenciar cursos, incluindo criação, atualização e exclusão de informações de cursos.
- **Gerenciamento de Matrículas**: Gerenciar matrículas de alunos em cursos, com a capacidade de adicionar, visualizar e remover matrículas.
- **Autenticação**: Proteger endpoints da API com autenticação de usuários.
- **Documentação da API**: Documentação da API gerada automaticamente com ferramentas como Swagger.

## Arquivos Principais

- **manage.py**: Ponto de entrada para o projeto Django, usado para executar tarefas administrativas.
- **settings.py**: Arquivo de configuração para as configurações do Django, incluindo configuração do banco de dados e aplicativos instalados.
- **urls.py**: Roteamento de URLs para a aplicação, mapeando endpoints para views.
- **models.py**: Modelos de banco de dados para alunos, cursos e matrículas.
- **views.py**: Views da API que manipulam requisições e respostas para cada endpoint.
- **serializers.py**: Serializadores de dados para converter instâncias de modelos em JSON e vice-versa.
- **admin.py**: Configuração para a interface de administração do Django para gerenciar modelos.