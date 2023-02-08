# Desafio Nginx com Node.js
Desafio Docker e Node do curso FullCycle 3.0.

### Descrição do desafio
Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

__O retorno da aplicação node.js para o nginx deverá ser:__
```html
<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrada no banco de dados.
```

### Requisitos
1. O docker-compose deve ser gerado de uma forma que basta apenas executarmos o comando: docker-compose up -d que tudo deverá estar funcionando e disponível na porta: 8080.

2. O código deve ser disponibilizado em um repositório.

  
### Para rodar :zap:
```
git clone https://github.com/eltoncosta939/desafioDockerNginxNodeMysql.git

cd desafioDockerNginxNodeMysql

docker-compose up -d
```
<br/>
<br/>