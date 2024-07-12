# Reel CRUD

In-memory **Movie REST API** in Go with Gorilla Mux. Full CRUD, UUID ids, JSON only — no database required.

## Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | `/movies` | List movies |
| GET | `/movies/{id}` | Get one |
| POST | `/movies` | Create |
| PUT | `/movies/{id}` | Update |
| DELETE | `/movies/{id}` | Delete |

## Tech

Go · Gorilla Mux · UUID

## Run

```bash
git clone https://github.com/bugship/reel-crud.git
cd reel-crud
go run .
# API on :8000 (see main.go)
```

## License

MIT
