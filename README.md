# go-echo-rest

## ローカル開発

### Docker立ち上げ

```bash
docker-compose up -d
```

### DB migration

```bash
GO_ENV="dev" go run ./migrate/migrate.go
```

### サーバー立ち上げ

```bash
GO_ENV="dev" go run ./main.go
```

## デプロイSaaS

- render: https://render.com/

## Link

- API: https://go-rest-api-hpy7.onrender.com

### frontend

- リポジトリ: https://github.com/jion-kozono/react-todo
- API:
