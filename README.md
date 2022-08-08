# 👩‍💻 **minecraft-ban-registry**

<br>

## Feature

- It was made using the [PocketMine-MP 4.6.2](https://github.com/pmmp/PocketMine-MP/releases/tag/4.6.2)
- Minecraft version v1.19.11
- Registre o histórico de banimentos do seu servidor
- O rosto do jogador que foi banido aparecera no site
- Possível remover os banimentos também

<br>

## Configure

> **api/src/typeorm/data-source.ts**

```javascript
  type: "mysql",
  host: process.env.DB_HOST || 'localhost',
  port: 3306,
  username: process.env.DB_USERNAME || 'root',
  password: process.env.DB_PASSWORD || 'root',
  database: process.env.DB_DATABASE || 'test',
```
