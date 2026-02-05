# INFORME COMPLETO - PLATAFORMA PSICOPRO

**Fecha:** Febrero 2026
**Version:** 1.0
**Autores:** Nelson Vicente Ordonez (CTO) y Dolores Gonzalez Diaz (Gerente)

---

## 1. DESCRIPCION DE LA PLATAFORMA

### Que es PsicoPro

**PsicoPro** es una plataforma SaaS (Software as a Service) de preparacion de oposiciones impulsada por Inteligencia Artificial. Esta diseñada para ayudar a opositores a preparar los tests psicotecnicos que forman parte de los procesos selectivos de empleo publico en España.

### Mision

**Democratizar el acceso al empleo publico**, eliminando las barreras economicas, geograficas y de accesibilidad que tradicionalmente excluyen a miles de personas de una preparacion de calidad.

### Vision

Convertirnos en la plataforma de referencia en España para la preparacion de oposiciones, siendo un ejemplo de accesibilidad e inclusion en el sector EdTech.

---

## 2. FUNCIONALIDADES PRINCIPALES

### 2.1 Motor de Tests Psicotecnicos

| Caracteristica | Detalle |
|----------------|---------|
| **Total de tests** | +2,200 preguntas |
| **Categorias** | Espacial, Verbal, Logica, Numerico, Mecanico, Series, Brujulas |
| **Niveles** | Basico, Intermedio, Avanzado |
| **Tiempo** | Configurable por el usuario |

### 2.2 Sistema de IA Personalizada (DeepSeek)

- **Tutoria adaptativa:** La IA ajusta la dificultad segun el rendimiento del usuario
- **Explicaciones detalladas:** Cada pregunta incluye explicacion paso a paso
- **Identificacion de debilidades:** Detecta areas de mejora y sugiere ejercicios
- **Feedback inmediato:** Correccion en tiempo real con analisis de errores

### 2.3 Simulacros de Examen Oficial

Reproducimos las condiciones reales de examen para las siguientes oposiciones:

| Oposicion | Formato | Tiempo |
|-----------|---------|--------|
| **TMB Barcelona** | 36/47/60 preguntas | Variable |
| **Correos** | Test psicotecnico completo | 60 min |
| **Guardia Civil** | Aptitudes + personalidad | 90 min |
| **Policia Nacional** | Test aptitudinal | 50 min |
| **EMT Madrid** | Psicotecnicos conduccion | 45 min |
| **RENFE** | Maquinistas/personal | 60 min |
| **ADIF** | Tecnicos/administrativos | 50 min |
| **Bomberos** | Aptitudinal + espacial | 60 min |
| **Mossos d'Esquadra** | Test psicotecnico | 45 min |
| **Metro Madrid** | Conductores | 45 min |

### 2.4 Test de Personalidad Profesional

- **160 preguntas** basadas en el modelo Big Five (NEO-PI-R)
- **5 competencias laborales** evaluadas
- **Informe detallado** para preparar la entrevista psicologica
- Adaptado a perfiles de seguridad y transporte

### 2.5 Dashboard de Progreso

- Graficos de evolucion por categoria
- Sistema de gamificacion: XP, niveles, rachas, logros
- Comparativa con percentiles
- Historico de resultados

### 2.6 Generador de CV Profesional

- Plantillas optimizadas para oposiciones
- Campos especificos para licencias de transporte (Carnet D, CAP, Tacografo)
- Exportacion a PDF
- Opcion de foto profesional con IA

---

## 3. TECNOLOGIA

### Stack Tecnico

| Componente | Tecnologia |
|------------|------------|
| **Frontend** | HTML5, TailwindCSS, JavaScript vanilla |
| **Backend** | Firebase (Firestore, Auth, Storage, Cloud Functions) |
| **IA** | DeepSeek API |
| **Hosting** | Firebase Hosting (CDN global) |
| **Pagos** | Stripe |
| **Accesibilidad** | WCAG 2.1 Nivel AA (100%) |

### Caracteristicas Tecnicas

- **PWA (Progressive Web App):** Funciona como app nativa en movil
- **Offline-first:** Contenido disponible sin conexion
- **Responsive:** Adaptado a todos los dispositivos
- **CDN Global:** Carga rapida desde cualquier ubicacion

---

## 4. ACCESIBILIDAD

### Cumplimiento WCAG 2.1 Nivel AA

PsicoPro es la **unica plataforma del mercado español** con cumplimiento total de los estandares de accesibilidad web.

| Principio WCAG | Implementacion |
|----------------|----------------|
| **Perceptible** | Alt text en imagenes, contraste minimo 4.5:1, textos redimensionables |
| **Operable** | Navegacion completa por teclado, sin limites de tiempo, saltos de navegacion |
| **Comprensible** | Lenguaje claro, errores identificados, instrucciones explicitas |
| **Robusto** | Compatible con NVDA, JAWS, VoiceOver, TalkBack |

### Hoja de Ruta Normativa

| Año | Hito | Estado |
|-----|------|--------|
| 2025 | WCAG 2.1 AA (100%) | **COMPLETADO** |
| 2026 | Certificacion UNE-EN 301549 | EN PROCESO |
| 2027 | Auditoria externa anual | Planificado |

### Origen del Compromiso

Ambos fundadores tienen reconocida una discapacidad:
- **Nelson Vicente Ordonez:** 41% de discapacidad
- **Dolores Gonzalez Diaz (Loli):** 33% de discapacidad

Este compromiso nace de la experiencia vital de no poder acceder a formacion adaptada.

---

## 5. MODELO DE NEGOCIO

### Planes y Precios

| Plan | Precio | Caracteristicas |
|------|--------|-----------------|
| **Basico** | 150 EUR/año | Tests ilimitados + IA basica |
| **Premium** | 299 EUR/año | Todo + simulacros + soporte prioritario |
| **CCOO (Basico)** | 99 EUR/año | Descuento exclusivo afiliados |
| **CCOO (Premium)** | 199 EUR/año | Descuento exclusivo afiliados |

### Programa Capacidad (Becas)

| Tipo de Beca | Descuento | Requisitos |
|--------------|-----------|------------|
| **Beca Parcial** | 50% | Certificado discapacidad ≥33% |
| **Beca Completa** | 100% | Discapacidad ≥65% o vulnerabilidad economica acreditada |

Las becas son gestionadas directamente por los fundadores, evaluando cada caso individualmente.

---

## 6. TRACCION Y USUARIOS ACTUALES

### Metricas a Febrero 2026

| Metrica | Valor |
|---------|-------|
| **Usuarios totales** | 80 |
| **Usuarios de pago (sin descuento)** | 75 |
| **Usuarios con descuento discapacidad (50%)** | 2 |
| **Usuarios becados 100% (Programa Capacidad)** | 3 |

### Desglose de Becados

Los **3 usuarios becados al 100%** son personas sin recursos economicos, gestionados directamente por nosotros mismos. Reciben acceso completo a la plataforma sin coste alguno como parte de nuestro compromiso social.

Los **2 usuarios con discapacidad** tienen el descuento del 50% correspondiente al Programa Capacidad para personas con certificado de discapacidad reconocida.

### Validacion del Modelo

- **Producto en produccion:** No es un prototipo, sino una plataforma activa
- **Ingresos recurrentes:** Suscripciones mensuales y anuales validadas
- **Ratio LTV/CAC:** 24x (excelente)
- **Break-even:** Alcanzado con 15-20 usuarios

---

## 7. ALIANZAS ESTRATEGICAS

### Alianza Activa: CCOO

| Aspecto | Detalle |
|---------|---------|
| **Partner** | Comisiones Obreras (CCOO) |
| **Estado** | **ACTIVO** |
| **Beneficio** | Precios especiales para afiliados (99/199 EUR) |
| **Codigo** | CCOOBUS |

### Alianza en Negociacion: ONCE/Inserta Empleo

| Aspecto | Detalle |
|---------|---------|
| **Partner** | Inserta Empleo (Fundacion ONCE) |
| **Estado** | EN NEGOCIACION |
| **Objetivo** | Auditoria tecnica + difusion entre comunidad discapacidad |
| **Timeline** | Q1-Q2 2026 |

---

## 8. EQUIPO FUNDADOR

### Nelson Vicente Ordonez - CTO y Fundador

| Aspecto | Detalle |
|---------|---------|
| **Formacion** | Psicologo, Programador, Gestion RRHH, IA, Neuropsicologia |
| **Discapacidad** | 41% reconocida |
| **Rol** | Desarrollo tecnico, IA, producto |
| **Dedicacion** | 100% |

### Dolores Gonzalez Diaz (Loli) - Gerente y Cofundadora

| Aspecto | Detalle |
|---------|---------|
| **Formacion** | Administracion, Operaciones, Atencion al cliente |
| **Discapacidad** | 33% reconocida |
| **Rol** | Operaciones, soporte, gestion becas |
| **Dedicacion** | 100% |

---

## 9. IMPACTO SOCIAL

### Problema que Resolvemos

Segun datos de **Inserta Empleo (ONCE, 2022)**:
- El **46% de las plazas reservadas para discapacidad quedan DESIERTAS**
- Solo el **3% de los nuevos funcionarios** tienen discapacidad reconocida
- Causa principal: falta de formacion accesible y adaptada

### Nuestra Contribucion

1. **Accesibilidad total:** Unica plataforma con 100% WCAG 2.1 AA
2. **Programa Capacidad:** Becas 50-100% para personas con discapacidad
3. **Precio accesible:** 77-90% mas economico que academias tradicionales
4. **Enfoque rural:** Acceso desde cualquier ubicacion sin desplazamiento

### Alineacion con ODS

- **ODS 4:** Educacion de calidad accesible
- **ODS 8:** Trabajo decente para personas con discapacidad
- **ODS 10:** Reduccion de desigualdades
- **ODS 11:** Desarrollo rural sostenible

---

## 10. CONTACTO

**Plataforma:** https://psicopro-plataforma.web.app

**Equipo:**
- Nelson Vicente Ordonez - CTO
- Dolores Gonzalez Diaz - Gerente

**Programa Capacidad (Becas):** Formulario disponible en la plataforma

---

*PsicoPro - Democratizando el acceso al empleo publico*
*Febrero 2026*
