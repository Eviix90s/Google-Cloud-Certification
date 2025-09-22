# Google Cloud Computing Foundations - Módulo 1
## "So what's the cloud anyway?"

---

## Objetivos del Módulo

Al completar este módulo, deberías poder:
- ✅ Identificar qué es la nube y su efecto en tecnología y negocios
- ✅ Explorar cloud computing
- ✅ Comparar arquitecturas física, virtual y cloud
- ✅ Diferenciar IaaS, PaaS y SaaS
- ✅ Conocer servicios de Google Cloud (compute, storage, big data, ML)
- ✅ Examinar la red de Google y cómo potencia el cloud computing

---

## 1. Definición de Cloud Computing

### Las 5 Características Fundamentales (NIST)

#### 1. **On-Demand Self-Service** (Autoservicio bajo demanda)
- Usuarios obtienen recursos sin intervención humana
- A través de interfaz web
- Recursos: procesamiento, almacenamiento, red

#### 2. **Broad Network Access** (Acceso amplio de red)
- Acceso desde cualquier lugar con conexión a Internet
- Ubicuidad y movilidad

#### 3. **Resource Pooling** (Agrupación de recursos)
- Proveedor tiene pool grande de recursos
- Asignación según necesidad
- Compras en volumen → ahorros para clientes
- Clientes no necesitan saber ubicación física exacta

#### 4. **Rapid Elasticity** (Elasticidad rápida)
- Recursos pueden **aumentar o disminuir** según necesidad
- Scale up/Scale down rápidamente
- Flexibilidad total

#### 5. **Measured Service** (Servicio medido)
- **"Pay-as-you-go"** - Pagas solo lo que usas o reservas
- Dejas de usar → dejas de pagar

### 💡 Analogía para Recordar
**IT Infrastructure = Infraestructura de ciudad**
- **Usuarios** = Personas en la ciudad
- **Aplicaciones** = Autos, bicicletas, edificios  
- **Infraestructura** = Transporte, comunicaciones, energía, agua

---

## 🌊 2. Evolución: Cloud vs Traditional Architecture

### Las 3 Olas de la Computación

#### **1ª Ola: Colocation (Colocación)**
- Rentar espacio físico vs invertir en bienes raíces de data center
- Ventaja: Eficiencia financiera
- Limitación: Aún infraestructura física

#### **2ª Ola: Virtualized Data Centers**
- Componentes virtuales: servidores, CPUs, discos, load balancers
- Problema: Empresas **aún mantenían la infraestructura**
- Entorno controlado y configurado por el usuario

#### **3ª Ola: Container-Based Architecture** 🚀
- **Google**: No podía moverse lo suficientemente rápido con virtualización
- Características:
  - **Completamente automatizada**
  - **Elástica**
  - **Servicios automáticos** + **datos escalables**
  - **Auto-provisionamiento** de infraestructura

### 🎯 Visión de Google
> *"En el futuro, **toda empresa** se diferenciará de sus competidores a través de tecnología"*

**Cadena de valor**:
1. **Tecnología** → principalmente **software**
2. **Gran software** → basado en **datos de alta calidad**  
3. **Conclusión**: **Toda empresa será una empresa de datos**

### 🌍 Sostenibilidad Ambiental

#### Logros de Google:
- ✅ **Primera certificación ISO 14001**
- ✅ **Primera década**: Carbono neutral
- ✅ **Segunda década**: 100% energía renovable  
- 🎯 **Meta 2030**: Primera empresa major operando libre de carbono

#### Innovación: Data Center Hamina, Finlandia
- Sistema de enfriamiento con **agua marina del Mar de Finlandia**
- **Primero de su tipo en el mundo**
- Reduce significativamente el uso de energía

---

## ⚙️ 3. Modelos de Servicio: IaaS, PaaS, SaaS

### **IaaS (Infrastructure as a Service)**
- **Qué ofrece**: Compute, storage y network **en bruto**
- **Organización**: Recursos virtuales similares a data centers físicos
- **Modelo de pago**: **Pagas por recursos que ASIGNAS** (por adelantado)
- **Control**: Máximo control sobre la infraestructura

### **PaaS (Platform as a Service)**  
- **Qué hace**: **Conecta código con librerías** que dan acceso a infraestructura
- **Ventaja**: Más recursos enfocados en **lógica de aplicación**
- **Modelo de pago**: **Pagas por recursos que REALMENTE USAS**
- **Control**: Menos gestión de infraestructura, más desarrollo

### **SaaS (Software as a Service)**
- **Características**:
  - **NO se instala** en tu computadora local
  - **Corre en la nube** como servicio
  - **Se consume directamente** por Internet
- **Ejemplos Google**: Gmail, Docs, Drive = **Google Workspace**

### 📈 Evolución del Cloud Computing
```
IaaS → PaaS → Managed Services → Serverless
```

### ⚡ Serverless Computing
**Concepto**: Desarrolladores se enfocan en **código**, NO en configuración de servidores

#### Servicios Serverless de Google:
1. **Cloud Run**: Deploy de microservicios containerizados en entorno completamente administrado
2. **Cloud Run Functions**: Código dirigido por eventos, modelo pay-as-you-go

### 💰 Comparación Modelos de Pago

| Modelo | Pago |
|--------|------|
| **IaaS** | Por recursos **asignados** |
| **PaaS** | Por recursos **usados** |
| **Serverless** | **Pay-as-you-go** (eventos) |

---

## 🏗️ 4. Google Cloud Architecture

### Arquitectura en 3 Capas

#### **CAPA BASE: Networking & Security**
- Base que **soporta toda** la infraestructura y aplicaciones de Google
- Fundación de todo el ecosistema

#### **CAPA MEDIA: Compute & Storage**
- **Característica clave**: **Desacoplados** (decoupled)
- **Ventaja**: Pueden **escalar independientemente** según necesidad

#### **CAPA SUPERIOR: Big Data & Machine Learning**
- **Capacidades**: Ingerir, almacenar, procesar y entregar:
  - Business insights
  - Data pipelines  
  - Modelos de ML
- **Ventaja**: **Sin gestionar infraestructura subyacente**

### 🛠️ Servicios Principales

#### **Compute Services**:
- **Compute Engine**
- **Google Kubernetes Engine**
- **App Engine**
- **Cloud Run**
- **Cloud Run Functions**

#### **Storage Options**:
- **Cloud Storage**
- **Cloud SQL** (Relacional)
- **Spanner** (Relacional)
- **Bigtable** (NoSQL)
- **Firestore** (NoSQL)

#### **Big Data & ML**:
- **Cloud Storage**, **Dataproc**, **Bigtable**, **BigQuery**
- **Dataflow**, **Firestore**, **Pub/Sub**, **Looker**
- **Spanner**, **AutoML**, **Vertex AI** (plataforma ML unificada)

---

## 🌐 5. Google Network

### Características
- **La red más grande** de su tipo
- **Inversión**: Miles de millones de dólares
- **+100 content caching nodes** mundiales
- **Objetivo**: Máximo throughput + Mínima latencia

### 🗺️ Geografía Global

#### 5 Ubicaciones Principales:
**Norte América, Sur América, Europa, Asia, Australia**

#### Jerarquía Geográfica:
```
Ubicaciones → Regiones → Zonas
```

#### Definiciones:
- **Región**: Áreas geográficas independientes (ej: London = europe-west2)
- **Zona**: Donde se despliegan recursos de Google Cloud
- **Multi-región**: Recursos replicados en múltiples regiones

#### Ejemplo Práctico:
**London (europe-west2)** = 1 región con **3 zonas**

### 📍 Tipos de Recursos

#### **Zonal Resources**:
- Operan en **una sola zona**
- **Riesgo**: Si zona no disponible → recurso no disponible

#### **Regional Resources**:
- Operan a **nivel región**

#### **Multi-Regional Resources**:
- **Ejemplo**: Spanner multi-región
- **Beneficio**: Réplicas en múltiples zonas Y regiones
- **Resultado**: Lectura con baja latencia desde múltiples ubicaciones

### 📊 Estadísticas Actuales
- **121 zonas** en **40 regiones**
- **Crecimiento constante**
- **Info actualizada**: cloud.google.com/about/locations

---

## 🎯 Conceptos Clave para Exámenes

### Preguntas Frecuentes:
1. **¿Cuáles son las 5 características del cloud computing?** → NIST traits
2. **¿Dónde se despliegan los recursos de Google Cloud?** → **Zonas**
3. **¿Qué es IaaS?** → Raw compute, storage, network
4. **¿Cuál es la 3ª ola del cloud?** → **Container-based architecture**
5. **¿Cuál es la diferencia en pago entre IaaS y PaaS?** → Asignado vs Usado

### Términos Importantes:
- **Desacoplamiento** Compute/Storage = escalabilidad independiente
- **Managed services** = enfoque en lógica de negocio
- **Serverless** = enfoque solo en código
- **Multi-región** = máxima disponibilidad
- **Google = 3ª ola** (container-based)

---

## ✅ Quiz Results - Módulo 1

**Puntuación**: 4/4 = 100% ✅

1. **Atributo fundamental del cloud**: Acceso desde cualquier lugar por Internet
2. **Raw compute, storage, network**: **IaaS**
3. **Dónde se despliegan recursos**: **Zonas**
4. **3ª ola automatizada y elástica**: **Container-based architecture**

---

## 📚 Próximos Pasos

- [x] **Módulo 1 COMPLETADO**: "So what's the cloud anyway?"
- [ ] **Módulo 2**: Por comenzar...

---

*Última actualización: [22/09/2025]*
*Curso: Google Cloud Computing Foundations*