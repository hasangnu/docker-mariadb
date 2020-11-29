# mariadb

```yalm
version: "3"
services:
  db:
    image: hasangnu/mariadb
    volumes:
      - ./mariadb-data:/var/lib/mysql
    environment:
      - MYSQL_ROOT_PASSWORD=example
      - MYSQL_DATABASE=example
      - MYSQL_USER=example
      - MYSQL_PASSWORD=example
    restart: unless-stopped
```
