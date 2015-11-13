docker-spigot
=============

Containerized Spigot

## Usage

```bash
docker run -d -v my_config:/usr/src/myserver davetucker/spigot
```

The volume "my_config" should contain your `spigot.yml`, `bukkit.yml`, `plugins` etc...
