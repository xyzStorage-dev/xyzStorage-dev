```yaml
services:
  itbob-discordbot:
    image: 'ghcr.io/developmentstorage/itbob-discordbot:latest'
    container_name: itbob-discordbot
    volumes:
      - itbob_data:/app

volumes:
  itbob_data:
