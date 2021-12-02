# Comandos do docker

## docker ps
Lista todos os containers ativos!

## docker ps -a
Lista todos os containers!

## docker rm "idDoContainer"
### Para remover o container desejado, é necessário que ele esteja pausado
Remove o container especifico

## docker start "idDoContainer" / "nome"
Inicia aquele container

## docker stop "idDoContainer" / "nome"
Para o container selecionado

## docker exec -it "idDoContainer" / "nome"
Acessa o local deste container
Ctrl + D volta para o diretório inicial

## docker logs "idDoContainer" / "nome" 
Exibe os logs anteriores
## docker logs "idDoContainer" / "nome" -f
Mostra todos os logs

# Comandos do  docker-compose

## docker-compose up
Inicia o container somente em tempo de execução

## docker-compose up -d
Inicia o container em background

## docker-compose stop
Para o container em execução

## docker-compose down
Remove tudo que foi criado no serviço (container)

## docker-compose start 
Inicia o container

