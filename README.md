# phpmyadmin-docker

Docker setup untuk phpMyAdmin dengan MariaDB.

## Prasyarat

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Menjalankan

```bash
docker compose up -d
```

## Service

| Service     | Image                    | Port |
| ----------- | ------------------------ | ---- |
| MariaDB     | mariadb:10.11            | 3306 |
| phpMyAdmin  | phpmyadmin/phpmyadmin    | 8080 |

## Akses

- **phpMyAdmin**: http://localhost:8080
- **Server**: `db`
- **User**: `root`
- **Password**: `123`

## Menghentikan

```bash
docker compose down
```
