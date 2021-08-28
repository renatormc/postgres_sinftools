# Como utilizar

## Instalar WSL2

[Link para instalação](https://docs.microsoft.com/pt-br/windows/wsl/install-win10)

## Instalar docker desktop

Instale Docker Desktop no Windows e habilite para utilizar o recurso wsl

## Clonar este repositório
```bash
sudo apt install git
git clone 
```

## Arquivo .env

Crie um arquivo de nome .env e coloque o seguinte conteúdo alterando com seus dados pessoais:
```
POSTGRES_PORT=5433
POSTGRES_USER=user
POSTGRES_PASSWORD=****
PGADMIN_DEFAULT_EMAIL=seuemail@provedor.com
PGADMIN_DEFAULT_PASSWORD=*****
```

## Rode o docker
```
docker-compose up
```