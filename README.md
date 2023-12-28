# minio.aoirint.com

- [MinIO](https://github.com/minio/minio)

---

- [minio.aoirint.com](https://minio.aoirint.com)
- [minio-console.aoirint.com](https://minio-console.aoirint.com)

---

## Setup

### Prometheus

```shell
mkdir -p volumes/{prometheus_config,prometheus_data}

touch volumes/prometheus_config/prometheus.yml
mc admin prometheus generate YOUR_ALIAS

sudo chown -R "65534:65534" volumes/prometheus_data
```
