# bolatkhan-daulet-devops

DevOps laboratory work: Linux → Git → GitHub → Docker → Jenkins.

| Element          | Value                     |
|------------------|---------------------------|
| Student          | Daulet Bolatkhan        |
| Group            | IT2-2301                  |
| Student ID       | 37074             |
| Docker image     | bolatkhan-daulet-devops                  |
| Docker container | bolatkhan-daulet-container              |
| Jenkins job      | Bolatkhan_Daulet_DevOps                    |

## Structure

```
app/        Python application + tests
scripts/    Bash scripts
config/     Configuration files
logs/       Logs (ignored by git)
backup/     Backups (ignored by git)
```

## Run

```bash
./scripts/Bolatkhan_Daulet_system.sh
docker build -t bolatkhan-daulet-devops .
docker run --name bolatkhan-daulet-container bolatkhan-daulet-devops
docker compose up
```
