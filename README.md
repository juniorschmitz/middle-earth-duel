# Middle Earth Duel

API criada para que QAs utilizem no treinamento de aprendizado sobre documentação, planejamento de testes e implementação de testes automatizados em APIs REST.

Para executar o servidor localmente, deve-se ter o ambiente Ruby configurado.

Após ter Ruby instalado, deve-se executar o comando:
```
bundle install
```

Recomendação é que seja utilizado um container Docker com o banco de dados PostgreSQL.

Após configurar o banco de dados, deve-se colocar no arquivo config/database.yml o usuário e password do banco, e executar os comandos:

```
rails db:migrate
rails db:seed
```

Para subir o servidor Rails, deve-se executar o comando:
```
rails s
```
