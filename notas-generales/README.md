# 📓 Notas Generales del Curso

Apuntes transversales, tips y conceptos que aplican a múltiples módulos.

## Conceptos clave de GCP

### Jerarquía de recursos
- Organization → Folders → Projects → Resources

### Regiones y zonas
- Global, regional, zonal resources
- Latencia y disponibilidad

### Billing y costos
- Proyectos de billing
- Monitoreo de gastos
- Alertas de presupuesto

## 🛠Comandos gcloud esenciales
```bash
# Configuración inicial
gcloud auth login
gcloud config set project PROJECT_ID

# Listar recursos
gcloud compute instances list
gcloud storage buckets list

# Configuración común
gcloud config configurations list
