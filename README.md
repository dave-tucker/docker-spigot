docker-spigot
=============

Containerized Spigot

## Usage

```bash
docker run -d -v my_config:/etc/spigot davetucker/spigot
```

Your configuration is mounted to `/etc/spigot`
The volume "my_config" should contain your `spigot.yml`, `bukkit.yml`, `plugins` etc...
