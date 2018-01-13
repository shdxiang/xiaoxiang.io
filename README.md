# xiaoxiang.io

Start a blog platform with:

- [WordPress](https://wordpress.org/) and [Ghost](https://ghost.org/) supported.

- `HTTPS` supported.

- Redirect `HTTP` to `HTTPS` automatically.

- Store All blog contents and database to directory `./data` for easy migration.

## Usage

- Change domain names, email addresses and paths in the YAML files.

- Start [WordPress](https://wordpress.org/) with:

  ```
  docker-compose -f wordpress.yml up -d
  ```

- Or start [Ghost](https://ghost.org/) with:

  ```
  docker-compose -f ghost.yml up -d
  ```

- Wait for the initialization about 2 minutes.

- Point to `https:/YOU-DOMAIN` with browser.
