# LAMP Infrastructure

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

To turn off the infrastructure:

```
docker-compose down
```

- Open phpmyadmin at [http://127.0.0.1:8000](http://127.0.0.1:8000)
- Open web browser to look at a simple php example at [http://127.0.0.1:80](http://127.0.0.1:80)
- Clone YourProject on `www/` and then, open web [http://127.0.0.1/YourProject](http://127.0.0.1/YourProject)

Run MySQL client:
`docker-compose exec db mysql -u root -p`

Infrastructure as code!