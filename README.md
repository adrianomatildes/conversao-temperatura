# Recomendação basica para qualquer aplicação  

# Temos que verficar o tipo de linguagem de programa a aplicação foi feita para podermos utilizar a imagem docker certa , apartir dela criar a imagem com a aplicação empacotada apartir de um dockerfile

# Com a imagem pronta tendo a aplicação empacotada, vamos usa-la criando um container

# Por exemplo:
- docker run -d --name<nome do container> -p<porta-web>:<porta:container> <nome da imagem>

# Acessando a aplicação via web
localhost:<porta web> ou <ip-container><porta web>