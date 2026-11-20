# Banco Escolar — SQL

Exercício didático de modelagem relacional com tabelas de cursos e alunos, dados de exemplo e consultas com `INNER JOIN`. Os nomes da lista foram substituídos por rótulos genéricos e os registros devem ser tratados como dados fictícios de demonstração.

## Como executar

O script `escola.sql` usa sintaxe T-SQL e cria o banco `ESCOLA`. Execute em uma instância local do Microsoft SQL Server usando SQL Server Management Studio, Azure Data Studio ou `sqlcmd -i escola.sql`. Use apenas em uma instância de teste, pois a execução cria um banco com esse nome.

## Conteúdo

- `Curso` — catálogo de cursos.
- `Aluno` — registros de exemplo ligados a um curso por chave estrangeira.
- Consultas finais para listar registros e combinar aluno/curso.

Material educacional. Nenhuma licença de reutilização é concedida neste repositório.

Autor: [@Enhazo](https://github.com/Enhazo)
