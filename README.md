# Postgres Minio backups

A simple Docker application to backup your PostgreSQL database to Minio via a cron.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.com/template/girFDE?referralCode=ve12LK)

## Configuration

- `MINIO_ENDPOINT` - Minio endpoint. Example: `http://minio:9000`.

- `ACCESS_KEY` - Minio access key.

- `SECRET_KEY` - Minio secret key.

- `MINIO_BUCKET` - Minio bucket. Example `my-bucket`.

- `BACKUP_DATABASE_URL` - The connection string of the database to backup. Example: `"postgresql://username:password@host:port/database"`

- `CRON_SCHEDULE` - The cron schedule to run the backup on. Example: `* * * * *`
