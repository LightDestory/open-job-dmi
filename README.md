# open-job-dmi

## Run with Docker Compose
```yaml
version: '2'
services: 
  open-job-dmi:
    build: .
    environment:
      - TELEGRAM_TOKEN=<your-telegram-token>
      - CHANNEL_ID=<your-channel-id>
      - ADMIN_GROUP_ID=<your-admin-group-id>
    ports:
      - 8080:8080
```