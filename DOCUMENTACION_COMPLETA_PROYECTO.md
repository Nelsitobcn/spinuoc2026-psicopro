# Psicopro Proseleccion - Documentacion Completa

## SpinUOC 2026 | Plataforma de Evaluacion Psicotecnica con IA

---

# INDICE

1. [Vision General](#1-vision-general)
2. [El Problema](#2-el-problema)
3. [La Solucion](#3-la-solucion)
4. [Funcionalidades de la Plataforma](#4-funcionalidades-de-la-plataforma)
5. [Arquitectura Tecnica](#5-arquitectura-tecnica)
6. [Inteligencia Artificial](#6-inteligencia-artificial)
7. [Modelo de Negocio](#7-modelo-de-negocio)
8. [Metricas y Traccion](#8-metricas-y-traccion)
9. [Competencia](#9-competencia)
10. [Impacto Social](#10-impacto-social)
11. [Roadmap](#11-roadmap)
12. [Equipo](#12-equipo)
13. [Anexos Tecnicos](#13-anexos-tecnicos)

---

# 1. VISION GENERAL

## Mision

**Democratizar el acceso al empleo publico mediante tecnologia e inteligencia artificial, reduciendo el coste de preparacion de 1.200-3.000 EUR a solo 80 EUR.**

## En Una Frase

Psicopro Proseleccion es una plataforma SaaS que permite a cualquier persona preparar oposiciones con tests psicotecnicos adaptativos, explicaciones generadas por IA y simulacros realistas, todo accesible 24/7 desde cualquier dispositivo.

## Propuesta de Valor Unica

| Caracteristica | Academias Tradicionales | Psicopro |
|---------------|------------------------|----------|
| Precio | 1.200 - 3.000 EUR | 80 EUR |
| Disponibilidad | Horarios fijos | 24/7 |
| Acceso | Solo grandes ciudades | Desde cualquier lugar |
| Personalizacion | Clases genericas | IA que analiza errores |
| Explicaciones | Depende del profesor | IA genera explicaciones detalladas |
| Seguimiento | Manual o inexistente | Dashboard con graficos y gamificacion |

---

# 2. EL PROBLEMA

## Contexto del Mercado

Cada año en España, mas de **500.000 personas** se presentan a oposiciones de empleo publico:

- **TMB Barcelona** (Metro y Bus): 80.000 aspirantes/año para ~200 plazas
- **Guardia Civil**: 40.000 aspirantes/año
- **Policia Nacional**: 35.000 aspirantes/año
- **Otros cuerpos**: 50.000+ aspirantes/año

## Barreras de Acceso

### 1. Barrera Economica
- Academia presencial: 1.200 - 3.000 EUR
- Material oficial: 200 - 500 EUR
- Desplazamientos: 50 - 100 EUR/mes
- **Total: 1.500 - 4.000 EUR por preparacion**

### 2. Barrera Geografica
- Academias concentradas en grandes ciudades
- +3.000 municipios en España sin academia de oposiciones
- Zonas rurales completamente desatendidas

### 3. Barrera Temporal
- Horarios fijos (tipico: 18:00-21:00)
- Incompatible con trabajadores a turnos
- Sin opcion de conciliacion familiar

### 4. Barrera Pedagogica
- Material generico no personalizado
- Sin feedback inmediato
- Explicaciones superficiales o inexistentes

## Consecuencia

**Miles de personas con potencial quedan excluidas por falta de recursos, no de capacidad.**

El 70% de candidatos no superan los tests psicotecnicos por falta de preparacion adecuada, no por falta de capacidad.

---

# 3. LA SOLUCION

## Psicopro Proseleccion

Una plataforma web completa que ofrece:

### Tests Psicotecnicos Completos
- **1.308+ preguntas** de examenes reales
- **7 categorias**: Espacial, Verbal, Logica, Numerico, Mecanico, Brujulas, Series
- **20 subcategorias** con diferentes niveles de dificultad
- **Niveles de dificultad**: Basico (68.4%), Intermedio (21.5%), Avanzado (10.1%)

### Simulacros Realistas
- Formato identico a examenes oficiales
- Cronometro con tiempo real de examen
- Analisis detallado de resultados
- Comparativa con otros usuarios

### Inteligencia Artificial Integrada
- Explicaciones automaticas de cada pregunta
- Analisis de patron de errores
- Recomendaciones personalizadas de estudio
- Chat de soporte con IA (Proseleccion IA)

### Gamificacion Avanzada
- Sistema de XP y niveles
- Rachas diarias de estudio
- Logros desbloqueables
- Ranking entre usuarios

### Generador de CV Profesional
- Plantillas optimizadas para oposiciones
- Campos especificos (Carnet D, CAP, Tacografo)
- Exportacion a PDF
- Subida de foto con ajuste automatico

### Test de Personalidad Premium
- 200 preguntas tipo COMPETEA
- Evaluacion de 5 competencias clave
- Informe detallado
- Preparacion para entrevistas

---

# 4. FUNCIONALIDADES DE LA PLATAFORMA

## 4.1 Sistema de Tests

### Estructura de Categorias

```
TESTS PSICOTECNICOS
├── Espacial (10 tests, 500 preguntas)
│   ├── Rotacion mental
│   ├── Visualizacion 3D
│   ├── Plegado de figuras
│   └── Series espaciales
├── Verbal (8 tests, 455 preguntas)
│   ├── Sinonimos/Antonimos
│   ├── Analogias verbales
│   ├── Comprension lectora
│   └── Ortografia
├── Logica (6 tests, 300 preguntas)
│   ├── Secuencias logicas
│   ├── Deducciones
│   └── Razonamiento abstracto
├── Numerico (6 tests, 358 preguntas)
│   ├── Series numericas
│   ├── Calculo mental
│   └── Problemas matematicos
├── Mecanico (5 tests, 150 preguntas)
│   ├── Poleas y engranajes
│   ├── Palancas
│   └── Fisica basica
├── Brujulas (1 test, 20 preguntas)
│   └── Orientacion espacial
└── Series (3 tests, 150 preguntas)
    └── Series graficas
```

### Sistema de Puntuacion
- Respuesta correcta: +1 punto
- Respuesta incorrecta: -0.25 puntos (simula penalizacion real)
- Sin respuesta: 0 puntos
- Tiempo extra: Penalizacion proporcional

### Modos de Practica
1. **Modo Aprendizaje**: Sin tiempo, con explicaciones inmediatas
2. **Modo Examen**: Con cronometro, sin ayudas
3. **Modo Revision**: Repaso de errores anteriores

## 4.2 Simulacros

### Configuracion
- Numero de preguntas configurable (30, 50, 100)
- Tiempo ajustable segun convocatoria
- Mezcla de categorias como examen real
- Aleatorizacion de preguntas y respuestas

### Resultados
- Puntuacion global y por categoria
- Tiempo empleado vs tiempo disponible
- Grafico radar de habilidades
- Comparativa con media de usuarios
- Desglose de aciertos/errores/omitidas

## 4.3 Dashboard de Progreso

### Metricas Visuales
- Grafico de evolucion temporal
- Porcentaje de completitud por categoria
- Racha actual de estudio
- Nivel y XP acumulado

### Gamificacion
- **Niveles**: Novato → Experto → Maestro
- **Rachas**: Dias consecutivos de practica
- **Logros**: Hitos desbloqueables
- **XP**: Experiencia por cada accion

## 4.4 Generador de CV

### Campos Disponibles
- Datos personales
- Foto profesional (con ajuste de encuadre)
- Experiencia laboral
- Formacion academica
- Idiomas
- Licencias especiales (Carnet D, CAP, Tacografo)
- Habilidades

### Opciones de Exportacion
- PDF optimizado para impresion
- Ajuste automatico a 1 pagina
- Multiples plantillas

## 4.5 Accesibilidad

### Certificacion WCAG 2.1
- Navegacion por teclado completa
- Compatible con lectores de pantalla
- Contraste adecuado
- Textos escalables

### PWA (Progressive Web App)
- Instalable en movil como app nativa
- Funciona offline (tests descargados)
- Notificaciones push
- Actualizacion automatica

---

# 5. ARQUITECTURA TECNICA

## 5.1 Stack Tecnologico

### Frontend
| Tecnologia | Uso | Version |
|-----------|-----|---------|
| HTML5 | Estructura | - |
| TailwindCSS | Estilos | 3.x |
| JavaScript | Logica | ES6+ |
| html2pdf.js | Generacion PDF | 0.10.1 |
| jsPDF | Exportacion PDF | 2.x |

### Backend (Serverless)
| Servicio | Uso | Plan |
|---------|-----|------|
| Firebase Auth | Autenticacion | Spark/Blaze |
| Firestore | Base de datos | Blaze |
| Firebase Storage | Almacenamiento | Blaze |
| Firebase Hosting | CDN Global | Blaze |
| Cloud Functions | Backend logica | Blaze |

### Inteligencia Artificial
| Proveedor | Uso | Modelo |
|----------|-----|--------|
| Anthropic Claude | Explicaciones texto | Claude 3 |
| Google Gemini | Explicaciones imagenes | Gemini Vision |
| Replicate | Generacion headshots | PhotoMaker |

## 5.2 Estructura de Base de Datos (Firestore)

### Colecciones Principales

```
firestore/
├── users/
│   └── {userId}/
│       ├── email
│       ├── displayName
│       ├── premium: boolean
│       ├── premiumSince: timestamp
│       ├── xp: number
│       ├── level: number
│       ├── streak: number
│       └── completedTests: array
│
├── test_{categoria}_{numero}/
│   └── {questionId}/
│       ├── texto
│       ├── opciones: array
│       ├── respuesta_correcta
│       ├── imagen_url (opcional)
│       └── dificultad
│
├── ai_explanations/
│   └── {testName}/
│       └── questions/
│           └── {questionId}/
│               ├── explicacion
│               ├── explicacion_detallada
│               └── metodo_generacion
│
├── simulacros/
│   └── {simulacroId}/
│       ├── userId
│       ├── fecha
│       ├── puntuacion
│       ├── tiempo
│       └── desglose
│
└── payments/
    └── {paymentId}/
        ├── userId
        ├── amount
        ├── status
        └── timestamp
```

### Nomenclatura de Colecciones

```
Formato estandar: test_{categoria}_{numero}
Ejemplos:
- test_espacial_1, test_espacial_2 ... test_espacial_10
- test_verbal_1 ... test_verbal_8
- test_numerico_1 ... test_numerico_6
- test_logica_1 ... test_logica_6
- test_mecanico_1 ... test_mecanico_5
- test_brujulas_1
- test_series_1 ... test_series_3

NOTA: Existen colecciones legacy (test_espacial3 sin guion)
que se mantienen por retrocompatibilidad.
```

## 5.3 Arquitectura de Despliegue

```
┌─────────────────────────────────────────────────────────┐
│                    USUARIO                               │
│              (Navegador/PWA/Movil)                       │
└─────────────────────────────────────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────────┐
│                  Firebase Hosting                        │
│                   (CDN Global)                           │
│    psicopro-plataforma.web.app / proseleccion.es        │
└─────────────────────────────────────────────────────────┘
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
┌─────────────┐   ┌─────────────┐   ┌─────────────┐
│  Firebase   │   │  Firestore  │   │   Storage   │
│    Auth     │   │  (NoSQL DB) │   │  (Archivos) │
└─────────────┘   └─────────────┘   └─────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────────┐
│                  Cloud Functions                         │
│   - generateExplanation()                                │
│   - processPayment()                                     │
│   - generateProfessionalHeadshot()                       │
│   - sendEmailNotification()                              │
└─────────────────────────────────────────────────────────┘
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
┌─────────────┐   ┌─────────────┐   ┌─────────────┐
│  Claude API │   │ Gemini API  │   │  Replicate  │
│ (Anthropic) │   │  (Google)   │   │    (IA)     │
└─────────────┘   └─────────────┘   └─────────────┘
```

## 5.4 Flujos Principales

### Flujo de Autenticacion
```
1. Usuario entra a la plataforma
2. Click "Iniciar sesion" → Firebase Auth UI
3. Opciones: Email/Password, Google Sign-In
4. Firebase verifica credenciales
5. Se crea/actualiza documento en users/
6. Redireccion a dashboard
```

### Flujo de Test
```
1. Usuario selecciona categoria y test
2. Frontend carga preguntas de Firestore
3. Usuario responde preguntas
4. Al finalizar:
   a. Calculo de puntuacion
   b. Guardado de resultados
   c. Actualizacion de XP y nivel
   d. Muestra de correccion con explicaciones IA
```

### Flujo de Pago Premium
```
1. Usuario en plan FREE hace click en "Hazte Premium"
2. Redireccion a pasarela (Stripe/PayPal)
3. Usuario completa pago de 80 EUR
4. Webhook notifica a Cloud Function
5. Cloud Function actualiza users/{userId}.premium = true
6. Usuario tiene acceso completo inmediato
```

---

# 6. INTELIGENCIA ARTIFICIAL

## 6.1 Explicaciones con Claude

### Proceso de Generacion
1. Pregunta sin explicacion detectada
2. Cloud Function llama a Claude API
3. Prompt estructurado con contexto de la pregunta
4. Claude genera explicacion detallada
5. Se guarda en ai_explanations/

### Formato de Explicacion
```json
{
  "explicacion": "Resumen breve (1-2 frases)",
  "explicacion_detallada": {
    "tipo_ejercicio": "Categoria del ejercicio",
    "patron_identificado": "Patron o tecnica principal",
    "analisis_detallado": "Explicacion paso a paso",
    "estrategia_resolucion": "Pasos concretos para resolver",
    "respuesta_correcta": "Opcion X"
  },
  "metodo_generacion": "claude_code_task_agent",
  "has_explanation": true
}
```

### Cobertura Actual
| Categoria | Preguntas | Con Explicacion | Porcentaje |
|-----------|-----------|-----------------|------------|
| Espacial | 500 | 250 | 50% |
| Verbal | 455 | 455 | 100% |
| Logica | 300 | 300 | 100% |
| Numerico | 358 | 358 | 100% |
| Mecanico | 150 | 150 | 100% |
| Series | 150 | 150 | 100% |
| Brujulas | 20 | 20 | 100% |

## 6.2 Explicaciones con Gemini Vision

Para preguntas con imagenes (especialmente Espacial):
- Gemini Vision analiza la imagen
- Identifica patrones visuales
- Genera explicacion considerando elementos graficos

## 6.3 Generacion de Headshots (Replicate)

### Flujo
1. Usuario sube 1-4 fotos personales
2. Cloud Function envia a Replicate (PhotoMaker)
3. IA genera foto profesional estilo LinkedIn
4. Usuario puede usar en CV generado

### Opciones de Estilo
- Professional (corporativo neutro)
- Corporate (ejecutivo formal)
- Creative (startup/creativo)

## 6.4 Chat IA (Proseleccion IA)

Asistente virtual integrado que:
- Responde dudas sobre la plataforma
- Explica conceptos de tests
- Recomienda estrategias de estudio
- Soporte tecnico basico

---

# 7. MODELO DE NEGOCIO

## 7.1 Modelo Freemium

### Plan FREE
- 3 tests completos de prueba
- 1 simulacro de muestra
- Dashboard basico
- Sin explicaciones IA

### Plan PREMIUM (80 EUR - Pago Unico)
- Acceso a todos los tests (+1.300 preguntas)
- Simulacros ilimitados
- Todas las explicaciones IA
- Test de Personalidad completo
- Generador de CV
- Dashboard completo con gamificacion
- Acceso de por vida
- Actualizaciones incluidas

## 7.2 Estructura de Costes

### Costes Fijos Mensuales
| Concepto | Coste | Notas |
|----------|-------|-------|
| Firebase (Blaze) | 10-15 EUR | Escala con uso |
| Dominio | 1 EUR | Anual prorrateado |
| APIs IA | 5-10 EUR | Bajo consumo |
| **TOTAL** | **15-30 EUR/mes** | |

### Costes Variables
| Concepto | Coste | Trigger |
|----------|-------|---------|
| Stripe fees | 2.9% + 0.30 EUR | Por transaccion |
| Soporte | Variable | Escala con usuarios |

### Metricas Financieras
- **Margen bruto**: ~99%
- **CAC (Coste Adquisicion)**: ~0 EUR (organico)
- **LTV (Lifetime Value)**: 80 EUR
- **LTV:CAC Ratio**: Infinito

## 7.3 Proyeccion Financiera

| Periodo | Usuarios Premium | Ingresos | Costes | Beneficio |
|---------|-----------------|----------|--------|-----------|
| Actual | 110 | 8.800 EUR | 360 EUR | 8.440 EUR |
| 12 meses | 500 | 40.000 EUR | 500 EUR | 39.500 EUR |
| 24 meses | 2.000 | 160.000 EUR | 1.000 EUR | 159.000 EUR |
| 36 meses | 5.000 | 400.000 EUR | 2.000 EUR | 398.000 EUR |

## 7.4 Modelo B2B (Futuro)

### Sindicatos
- Licencia por volumen de afiliados
- Precio: Negociable segun alcance
- Estado: En negociacion con CCOO

### Academias
- Modelo white-label
- Precio: 500-2.000 EUR/año
- Incluye: Personalizacion de marca

### Empresas
- Formacion para empleados
- Tests de seleccion
- Evaluaciones periodicas

---

# 8. METRICAS Y TRACCION

## 8.1 Metricas Actuales (Febrero 2026)

### Usuarios
| Metrica | Valor |
|---------|-------|
| Usuarios registrados | 500+ |
| Usuarios premium | 120+ |
| Tasa de conversion FREE→PREMIUM | 24.9% |
| Usuarios activos mensuales | 60% |

### Engagement
| Metrica | Valor |
|---------|-------|
| Promedio tests/usuario | 15.3 |
| Promedio simulacros/usuario | 7.5 |
| Tiempo medio sesion | 28 min |
| Racha maxima registrada | 45 dias |

### Financieras
| Metrica | Valor |
|---------|-------|
| Ingresos totales | 9.600+ EUR |
| ARR (Annual Recurring) | ~20.000 EUR |
| Margen neto | 99% |
| CAC | 0 EUR |

## 8.2 Validacion Product-Market Fit

### Indicadores Positivos
1. **Conversion 24.9%** vs industria 2-5%
2. **Crecimiento 100% organico** sin ads
3. **Usuarios pagan 80 EUR sin descuentos**
4. **Tasa de aprobacion 89%** en oposiciones TMB

### Feedback de Usuarios
- "Mucho mas barato que la academia"
- "Puedo estudiar cuando quiero"
- "Las explicaciones de IA me ayudan mucho"
- "El simulacro es igual que el examen real"

## 8.3 Metricas de Impacto

| Indicador | Valor |
|-----------|-------|
| Ahorro colectivo generado | 230.000+ EUR |
| Usuarios de zonas rurales | ~15% |
| Candidatos aprobados TMB | 89% tasa exito |

---

# 9. COMPETENCIA

## 9.1 Analisis Competitivo

| Competidor | Precio | Modelo | IA | Gamificacion | Debilidad |
|-----------|--------|--------|-----|--------------|-----------|
| **Academias presenciales** | 1.200-3.000 EUR | Offline | No | No | Caro, inflexible |
| **Test-oposiciones.es** | 50-100 EUR | Solo tests | No | Basica | Sin explicaciones |
| **OpositaTest** | 30-60 EUR/año | Suscripcion | No | No | Contenido generico |
| **Apps moviles** | 0-20 EUR | Freemium | No | Si | Baja calidad |
| **Psicopro** | 80 EUR | Lifetime | Si | Avanzada | - |

## 9.2 Ventajas Competitivas

### 1. Precio Disruptivo
- 15x mas barato que academias
- Pago unico vs suscripciones
- Acceso de por vida

### 2. IA Personalizada
- Unico con explicaciones generadas por IA
- Analisis de patron de errores
- Recomendaciones personalizadas

### 3. Contenido Curado
- Preguntas de examenes reales
- Actualizado con convocatorias recientes
- Validado por opositores exitosos

### 4. Experiencia de Usuario
- Gamificacion avanzada
- Dashboard completo
- PWA instalable

### 5. Test de Personalidad
- Exclusivo en el mercado
- Preparacion para entrevistas
- Evaluacion de competencias

## 9.3 Barreras de Entrada

1. **Base de preguntas curada** (2+ años de trabajo)
2. **Explicaciones IA generadas** (coste hundido)
3. **Comunidad activa** de usuarios
4. **SEO posicionado** para keywords clave
5. **Conocimiento del dominio** (experiencia en seleccion)

---

# 10. IMPACTO SOCIAL

## 10.1 Democratizacion del Acceso

### Reduccion de Barreras
| Barrera | Antes | Con Psicopro | Reduccion |
|---------|-------|--------------|-----------|
| Economica | 2.000 EUR | 80 EUR | 95% |
| Geografica | Solo ciudades | Cualquier lugar | 100% |
| Temporal | Horarios fijos | 24/7 | 100% |

### Ahorro Generado
- **Ahorro individual**: 1.920 EUR (2.000 - 80)
- **Ahorro colectivo**: 230.000+ EUR (120 usuarios x 1.920)

## 10.2 Perfiles Beneficiados

1. **Trabajadores a turnos**: Flexibilidad horaria
2. **Madres/padres**: Conciliacion familiar
3. **Residentes rurales**: Acceso sin desplazamiento
4. **Desempleados**: Coste accesible

## 10.3 Alineacion con ODS

| ODS | Meta | Contribucion |
|-----|------|--------------|
| 4 - Educacion | 4.3 Acceso igualitario | Formacion por 80 EUR |
| 8 - Trabajo | 8.6 Reducir desempleo | Via al empleo publico |
| 10 - Desigualdades | 10.2 Inclusion economica | -95% barrera economica |
| 11 - Ciudades | 11.a Vinculos urbano-rural | Acceso desde zonas rurales |

## 10.4 Compromiso Social

### Becas Sociales
- 10% de ingresos destinado a usuarios sin recursos
- Acceso gratuito a municipios <1.000 habitantes

### Transparencia
- Publicacion anual de metricas de impacto
- Encuestas trimestrales a usuarios

---

# 11. ROADMAP

## 11.1 Completado (2024-2025)

- [x] Plataforma web funcional
- [x] 1.308+ preguntas en 7 categorias
- [x] Sistema de autenticacion
- [x] Pasarela de pago
- [x] Simulacros con cronometro
- [x] Dashboard con gamificacion
- [x] Explicaciones IA (90%+ cobertura)
- [x] Generador de CV
- [x] PWA instalable
- [x] Cliente anchor TMB (89% tasa exito)

## 11.2 En Desarrollo (Q1 2026)

- [ ] Tests adaptativos con IA
- [ ] Generacion de headshots con IA
- [ ] Mejoras UX generador CV
- [ ] Integracion WhatsApp

## 11.3 Planificado (Q2-Q4 2026)

- [ ] App movil nativa (iOS/Android)
- [ ] Expansion a Guardia Civil y Policia Nacional
- [ ] Sistema de notificaciones inteligentes
- [ ] Acuerdo B2B con sindicatos
- [ ] Panel de academias (white-label)

## 11.4 Vision (2027+)

- [ ] Expansion LATAM (Mexico, Colombia, Argentina)
- [ ] Tests adaptativos con IA avanzada
- [ ] Certificaciones oficiales
- [ ] Partnerships con organismos publicos

---

# 12. EQUIPO

## 12.1 Fundador

### Nelson Salinas
**Founder & Developer**

- Estudiante UOC (Grado Multimedia)
- +15 años experiencia en seleccion de personal
- Especialista en evaluacion psicotecnica
- Desarrollador full-stack autodidacta
- Conocimiento profundo del problema (entorno cercano opositor)

### Contacto
- Email: info@proseleccion.es
- Web: https://psicopro-plataforma.web.app
- GitHub: github.com/Nelsitobcn

## 12.2 Necesidades de Equipo

### Busqueda Activa
1. **Co-founder Tecnico/Growth**
   - Experiencia en SaaS B2C/B2B
   - Marketing digital o desarrollo

2. **Asesores**
   - Sector oposiciones
   - EdTech
   - Expansion internacional

---

# 13. ANEXOS TECNICOS

## 13.1 URLs del Proyecto

| Recurso | URL |
|---------|-----|
| Plataforma produccion | https://psicopro-plataforma.web.app |
| Dominio personalizado | https://proseleccion.es |
| Repositorio GitHub | github.com/soportepsicoproseleccion-ship-it/psicotecnicos-proseleccion |
| Documentacion SpinUOC | github.com/Nelsitobcn/spinuoc2026-psicopro |

## 13.2 Tecnologias Utilizadas

### Frontend
- HTML5, CSS3, JavaScript ES6+
- TailwindCSS 3.x
- html2pdf.js, jsPDF

### Backend
- Firebase Auth, Firestore, Storage, Hosting
- Cloud Functions (Node.js)

### IA
- Anthropic Claude API
- Google Gemini Vision API
- Replicate (PhotoMaker)

### DevOps
- Git + GitHub
- Firebase CLI
- Custom deploy scripts

## 13.3 Metricas Tecnicas

| Metrica | Valor |
|---------|-------|
| Tiempo de carga | <2s |
| Lighthouse Score | 90+ |
| Uptime | 99.9% |
| Regiones CDN | Global |

## 13.4 Seguridad

- Autenticacion Firebase (OAuth 2.0)
- HTTPS obligatorio
- Firestore Security Rules
- Datos encriptados en transito y reposo
- GDPR compliant

---

# CONCLUSION

Psicopro Proseleccion es mas que una plataforma de tests.

Es una **herramienta de movilidad social** que permite a cualquier persona, independientemente de su situacion economica, geografica o temporal, competir por un empleo publico en igualdad de condiciones.

Con tecnologia de vanguardia (IA), un modelo de negocio sostenible (99% margen), y traccion demostrada (24.9% conversion), estamos posicionados para liderar la transformacion digital del sector de oposiciones en España y LATAM.

**Cada usuario que se registra es una barrera menos.**
**Cada usuario premium es una oportunidad recuperada.**

---

*Documento preparado para SpinUOC 2026*
*Ultima actualizacion: Febrero 2026*
