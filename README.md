## ETL-процессы в Apache NiFi

Для запуска NiFi используется запущенный Podman с образом NiFi:

```bash
docker run --name nifi \
  -p 8443:8443 \
  -v ~/Documents/nifi-files \
  -d \
  -e SINGLE_USER_CREDENTIALS_USERNAME=admin \
  -e SINGLE_USER_CREDENTIALS_PASSWORD=ctsBtRBKHRAx69EqUghvvgEvjnaLjFEB \
  apache/nifi:latest
```
