![logo](https://assets.zabbix.com/img/logo/zabbix_logo_500x131.png)

# Passos para provisionar containers:

## Obtenha arquivos para prover container:
```bash
git clone https://github.com/zabbix/zabbix-docker.git
```
## Mude para a versão necessária:
```bash
git checkout 6.4
```

## Arquivo de configuração do compose, criação e inicialização dos containers:
```bash
docker compose -f ./docker-compose_v3_alpine_mysql_latest.yaml up -d
```

## Para acessar o zabbix no navegador:
```bash
localhost/zabbix
```
## Observação pode demorar um pouco para o mesmo ser provisionado.