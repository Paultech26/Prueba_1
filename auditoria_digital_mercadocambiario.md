# Auditoría de Presencia Digital — mercadocambiario.pe
**Fecha de auditoría:** Marzo 2026
**Analista:** Claude Code (Anthropic)

---

## 1. PERFIL DEL NEGOCIO

| Campo | Detalle |
|---|---|
| **Nombre** | Mercado Cambiario S.A. |
| **Web** | https://www.mercadocambiario.pe/ |
| **Tipo de negocio** | Fintech — Primer marketplace digital de compra/venta de dólares en Perú |
| **País** | Perú |
| **Inicio de operaciones** | Febrero 2025 (idea y desarrollo desde 2021) |
| **Modelo** | Marketplace con libro de órdenes visible en tiempo real (B2C y B2B) |
| **Co-fundadores** | Fernando Balbuena (ex-BCP/Mibanco, 20 años) / Hugo Ortiz (25 años en banca digital) / José Agois (30+ años: Banco Santander, Banco Sur, Mibanco) |
| **Directorio** | Oscar Rivera (ex-presidente ASBANC y FELABAN) / Francis Stenning (ex-Gerente General BVL) |

### Propuesta de Valor
Mercado Cambiario se posiciona como **el primer marketplace digital de compra y venta de dólares en Perú**, diferenciándose de las ~40 casas de cambio digitales que operan como modelo OTC (precio fijo del intermediario) al mostrar en tiempo real un libro de órdenes abierto donde compradores y vendedores publican sus propuestas y se casan directamente. El resultado: transacciones en menos de **5 minutos** vs. 30–45 minutos del estándar del sector, y un precio determinado por el mercado, no por el intermediario.

---

## 2. PRESENCIA DIGITAL — ESTADO ACTUAL

### 2.1 Sitio Web
- **Accesibilidad:** El sitio responde con código HTTP 403 en algunos crawlers, lo que puede indicar bloqueo a bots — potencialmente problemático para el SEO y para herramientas de análisis de terceros.
- **Antigüedad del dominio:** Muy reciente (dominio nuevo), lo que reduce la autoridad de dominio (DA) ante Google.
- **App Móvil:** No se encontró evidencia pública de una app nativa en Google Play o App Store. El servicio opera vía web.
- **Velocidad / UX:** No auditada directamente, pero plataformas fintech recientes en Perú tienden a tener diseños limpios y mobile-first.

### 2.2 SEO (Posicionamiento Orgánico)
- **Situación actual:** Al ser una plataforma lanzada en febrero 2025, prácticamente no existe historial de backlinks ni autoridad de dominio consolidada.
- **Palabras clave objetivo del sector:** "comprar dólares online", "tipo de cambio hoy", "casa de cambio online Peru", "cambiar soles a dólares" — todas altamente competidas por Rextie, Tucambista, Kambista y Cambi.
- **Contenido:** No se evidencia un blog o sección de contenidos educativos que genere tráfico orgánico sostenido.
- **Bloqueo a bots:** El error 403 al acceder desde crawlers puede impedir la indexación correcta por Google.

### 2.3 Redes Sociales

| Red | Estado | Detalle |
|---|---|---|
| **LinkedIn** | ✅ Activo (mínimo) | Página de empresa con al menos 1 post publicado. Hashtags: #mercadocambiario #elmejortipodecambio #transparenciafinanciera |
| **Instagram** | ❌ No detectado | Sin cuenta indexada para @mercadocambiario ni @mercadocambiariope |
| **Facebook** | ❌ No detectado | Sin resultados públicos atribuibles a la empresa |
| **TikTok** | ❌ No detectado | Sin presencia detectada |
| **X / Twitter** | ❌ No detectado | Sin presencia detectada |
| **YouTube** | ❌ No detectado | Sin canal encontrado |

**Brecha crítica:** Kambista (454,000 usuarios registrados, 80,000 activos) y Rextie (líder con US$ 4,000M/año) tienen comunidades activas, campañas de contenido educativo y presencia robusta en Instagram, TikTok y YouTube. Mercado Cambiario no tiene estrategia de social media documentada ni ejecutada en canales de consumo masivo.

### 2.4 Reputación Online
- **Reviews/reseñas:** Menos de 14 meses de operación → base de reseñas en Google Maps prácticamente inexistente.
- **Mención en medios:** Aparece en Startups Latam (entrevista al fundador) y como caso de éxito de Odoo. **No aparece** en medios de primer nivel: Gestión, El Comercio, RPP, Semana Económica.
- **Aparición en rankings:** No figura en los top 7–10 de casas de cambio online de los principales comparadores peruanos (miciudad.pe, comparaeldolar.com, cambioseguro.com).

### 2.5 Regulación y Confianza Digital
- **SBS:** ✅ Registro SBS **03053-2024** publicado visiblemente en el footer del sitio — cumple con el estándar del sector.
- **Google Business Profile:** ✅ Perfil activo en Google Maps bajo el nombre "Mercado Cambiario".
- **Pendiente de reforzar:** Sello UIF visible, políticas de privacidad visibles, FAQs de seguridad y badges de certificaciones.

---

## 3. STACK TECNOLÓGICO

| Componente | Tecnología / Estado |
|---|---|
| **ERP / Back-office** | ✅ **Odoo** (confirmado vía caso de éxito oficial en odoo.com) — gestión contable, CRM, facturación electrónica, KYC básico y reportes regulatorios |
| **Motor del marketplace** | Desarrollo propio (no hay indicios de solución white-label conocida) |
| **Integración bancaria** | API propia con bancos para liquidación en <5 minutos (mencionado por fundadores) |
| **KYC / Identidad digital** | Probable uso de API RENIEC o proveedores biométricos (obligatorio por normativa SBS/UIF) |
| **Hosting / CDN** | No determinado — el sitio bloquea fingerprinting por HTTP 403 |
| **App móvil** | ❌ Sin app nativa en stores |

**Ventaja técnica confirmada:** El equipo fundador construyó la primera billetera electrónica de Mibanco en 2012. El back-office propio (no dependiente de proveedor externo) es la base de la velocidad de <5 minutos.

**Riesgo técnico:** Al ser un desarrollo propio con equipo pequeño, cualquier incidente de uptime o fallo en las APIs bancarias puede eliminar la ventaja competitiva principal.

---

## 4. ANÁLISIS COMPETITIVO

| Plataforma | Fundación | Registro SBS | App Móvil | Volumen / usuarios | Fortaleza |
|---|---|---|---|---|---|
| **Rextie** | ~2016 | ✅ | ✅ | US$ 4,000M/año; líder empresas | Liderazgo, 40% del segmento corporativo |
| **Kambista** | ~2016 | ✅ | ✅ | US$ 631M en 2025; 454K usuarios | Primera online, marca reconocida |
| **Tucambista** | ~2017 | ✅ | ✅ | n/d | Alta confianza, segmento retail |
| **Global66** | ~2019 | ✅ | ✅ | Crece 3x en 2026 | UX moderna, expansión regional |
| **Mercado Cambiario** | 2025 | ✅ 03053-2024 | ❌ | 350+ clientes activos | Modelo marketplace innovador |

**Contexto de mercado:**
- Mercado total de cambio de divisas en Perú: **US$ 12,000 millones anuales**
- Las fintech capturan solo **1.24%** del mercado total — el **99% sigue en bancos**
- ~500,000 clientes usan fintech cambiarias (casi el doble de hace 2 años)
- Spread bancos es **4 veces mayor** que el de las fintech

---

## 5. PUNTOS FUERTES

1. **Modelo diferenciado:** Libro de órdenes abierto en tiempo real — el único en Perú. Las ~40 casas de cambio digitales existentes son OTC (precio fijo del intermediario). Este modelo es análogo a lo que fue la BVL frente a la compra directa en ventanilla bancaria.
2. **Velocidad superior:** Menos de 5 minutos vs. 30–45 min de la competencia — ventaja operacional concreta y medible, sustentada en back-office propio.
3. **Equipo co-fundador excepcionalmente sólido:** Fernando Balbuena (BCP/Mibanco), Hugo Ortiz (25 años banca digital), José Agois (Banco Santander, Banco Sur, Mibanco). Tres perfiles complementarios: negocio, tecnología y operaciones.
4. **Directorio de primer nivel:** Oscar Rivera (ex-presidente ASBANC y FELABAN — máximos organismos bancarios del Perú y Latinoamérica) y Francis Stenning (ex-Gerente General de la Bolsa de Valores de Lima). Este directorio aporta una legitimidad institucional extraordinaria para una startup.
5. **Track record técnico probado:** Billetera electrónica de Mibanco (2012) — validador fuerte ante inversores y socios estratégicos.
6. **Alta tasa de operaciones repetidas:** Señal temprana de product-market fit y satisfacción del usuario.
7. **350+ clientes activos** en los primeros meses — ritmo de crecimiento inicial positivo.

---

## 6. PUNTOS A MEJORAR (Urgentes)

### 6.1 Presencia en rankings y comparadores
- **Problema:** No aparecen en comparaeldolar.com, miciudad.pe, cambioseguro.com.
- **Acción:** Gestionar alta en estos directorios. El tráfico referido desde comparadores es altísimo en este nicho.

### 6.2 Señales de confianza en el sitio
- **Lo que ya está bien:** Registro SBS 03053-2024 en el footer ✅ y Google Business Profile activo ✅.
- **Lo que falta:** Sello UIF visible, sección "Sobre Nosotros" con fotos del equipo y directorio, testimonios reales de clientes, FAQs de seguridad. Mostrar el directorio (Rivera, Stenning) sería un diferenciador de confianza único.

### 6.3 SEO y contenido
- **Problema:** Sin blog, sin contenido, sin backlinks = invisibilidad en búsquedas orgánicas.
- **Acción:** Blog sobre tipo de cambio, tips, noticias financieras + contenido explicativo del modelo marketplace.

### 6.4 Redes Sociales
- **Problema:** Solo LinkedIn activo. Sin Instagram, TikTok, Facebook ni YouTube.
- **Acción:** Activar Instagram + TikTok + LinkedIn con contenido educativo. El concepto "marketplace de divisas" requiere educación activa — ideal para formato Reels/TikTok de 60–90s. YouTube para explicar el modelo con mayor profundidad.

### 6.5 App Móvil
- **Problema:** Sin app nativa. El mercado peruano opera masivamente desde móvil.
- **Acción:** PWA (Progressive Web App) como paso intermedio antes de app nativa.

### 6.6 Bloqueo de crawlers
- **Problema:** HTTP 403 a bots/crawlers impide indexación y análisis legítimos.
- **Acción:** Revisar robots.txt y reglas de firewall para permitir Googlebot y herramientas de análisis.

### 6.7 Visibilidad en medios de primer nivel
- **Problema:** Sin cobertura en Gestión, El Comercio, RPP, Semana Económica.
- **Acción:** Estrategia de PR activa — el directorio (Rivera, Stenning) facilita apertura de puertas con medios financieros especializados.

---

## 7. OPORTUNIDADES

### 7.1 Mercado con 99% por capturar
- El mercado total de cambio de divisas en Perú es de **US$ 12,000 millones anuales** y los bancos controlan el 99%. Las fintech solo capturan el 1.24%. El potencial de crecimiento es estructuralmente inmenso.

### 7.2 Elecciones 2026 — Catalizador de demanda
- Elecciones generales el 12 de abril de 2026. La incertidumbre electoral históricamente dispara la demanda de dólares como cobertura. El dólar podría superar S/ 4.00 en escenario de candidato radical. Más volumen = más oportunidad para el marketplace.

### 7.3 Plan de Interoperabilidad Digital BCRP (Fase 4)
- Vigente desde abril 2026 (Circular N° 0022-2025-BCRP): incorpora fintech y bigtech como iniciadores de pago (PSIP). Abre la puerta a integraciones con Yape, Plin y otros wallets masivos.

### 7.4 Sandbox Regulatorio Ampliado
- Resolución SBS N° 04142-2025: permite a empresas no supervisadas probar modelos innovadores sin autorización previa. Mercado Cambiario puede iterar producto con menor riesgo regulatorio.

### 7.5 Segmento B2B (Empresas)
- Ticket promedio en empresas: **US$ 11,900** vs. US$ 1,300 en personas naturales (~9x). Rextie captura el 40% del segmento corporativo — hay espacio para un competidor especializado con modelo de precios más transparente.

### 7.6 Integración con SUNAT / tributación
- Reportes automáticos de operaciones en formato SUNAT (tipo de cambio oficial, ITF) — diferenciador enorme para empresas y contadores.

### 7.7 Alianzas estratégicas
- El directorio de Mercado Cambiario facilita alianzas con Yape, Plin, apps de contabilidad (Alegra, Concar) y bancos. Stenning (ex-BVL) tiene acceso directo al ecosistema institucional.

### 7.8 IA aplicada al tipo de cambio
- Rextie ya implementa IA para predicción de tipo de cambio en 2025. Oportunidad para Mercado Cambiario de diferenciar con algoritmos de matching y pricing dinámico en el libro de órdenes.

### 7.9 Expansión regional
- El modelo marketplace replica en Colombia, Chile, Bolivia — mercados con alta dolarización parcial y poco desarrollo en exchange digital.

---

## 8. DESAFÍOS

### 8.1 Educación del usuario sobre el modelo marketplace
- El concepto "marketplace de divisas" es más complejo de explicar que "te cambio soles por dólares". Los usuarios deben entender el libro de órdenes y la dinámica de matching. La curva de adopción es más larga que para una casa de cambio OTC. El CEO lo reconoce como el principal reto comunicacional.

### 8.2 Liquidez del libro de órdenes
- El modelo marketplace requiere masa crítica en compradores Y vendedores simultáneamente. Con 350 clientes activos, el libro puede ser delgado. Si no hay suficientes contrapartes, las órdenes no se casan y la propuesta de valor principal colapsa.

### 8.3 Credibilidad vs. incumbentes establecidos
- Rextie (US$ 4,000M/año, 40% del segmento corporativo) y Kambista (454,000 usuarios, 9 años) tienen reputación consolidada. El CEO de Kambista reconoció que la confianza fue su principal barrera inicial. Para un modelo más complejo, la curva es aún más larga.

### 8.4 Acceso a servicios bancarios
- Los bancos frecuentemente niegan o cierran cuentas a fintech sin justificación, alegando riesgos AML. Esto es un obstáculo operacional crítico: sin cuentas bancarias, la liquidación en <5 minutos no es posible.

### 8.5 Compliance UIF en escala
- El costo de compliance (KYC, AML, reportes RO/ROS, Oficial de Cumplimiento) crece conforme escala el volumen. Las empresas pequeñas tienen menor capacidad para absorberlo. La normativa se amplía constantemente.

### 8.6 Velocidad de adquisición de usuarios
- El CAC (Costo de Adquisición de Cliente) en fintech es alto. Sin capital de marketing significativo, el crecimiento orgánico puede ser lento frente a competidores con presupuestos establecidos.

### 8.7 Dependencia tecnológica
- La ventaja de los <5 minutos es tecnológica y propia. Un incidente de uptime o fallo en las APIs bancarias puede eliminar instantáneamente esa ventaja competitiva.

---

## 9. RIESGOS

### 9.1 Riesgo Electoral 2026 — ALTO
- Elecciones el 12 de abril de 2026. En escenario de candidato populista/radical: dólar puede superar S/ 4.00 → alta volatilidad → riesgo de liquidez en el libro de órdenes (uno de los lados puede agotarse). En escenario moderado: S/ 3.70–3.80, más volumen = positivo para el negocio.

### 9.2 Riesgo Regulatorio / UIF — MITIGADO PARCIALMENTE
- ✅ Registro SBS 03053-2024 confirmado. Pendiente: cumplimiento continuo de SIPLAFT, Oficial de Cumplimiento, reportes RO/ROS, Ley N° 32209. La SBS puede ordenar bloqueo de plataforma ante incumplimiento.

### 9.3 Riesgo de Liquidez del Libro — CRÍTICO (corto plazo)
- Con 350 clientes activos, el libro de órdenes puede ser demasiado delgado. Sin volumen en ambos lados, el precio no se forma eficientemente y la propuesta de valor se destruye.

### 9.4 Riesgo de Lavado de Activos / Fraude
- Velocidad de <5 min reduce la ventana para detección de anomalías. Una sola operación vinculada a lavado puede desencadenar intervención de la UIF. Un caso documentado en Perú: fintech sancionada por abrir cuentas sin verificación de identidad.

### 9.5 Riesgo de Imitación
- Rextie y Kambista tienen recursos para copiar el modelo marketplace en meses si ven tracción real.

### 9.6 Riesgo de Competencia de Bancos Digitales
- BCP (Yape), BBVA e Interbank están construyendo capacidades de cambio de divisas dentro de sus apps. Si llegan a spreads competitivos con distribución masiva (Yape: >10M usuarios), el mercado addressable para fintechs independientes se reduce.

### 9.7 Riesgo de Acceso Bancario
- Cierre de cuentas bancarias por parte de bancos = paralización operacional inmediata.

### 9.8 Riesgo de Reputación Temprana
- Con 350 clientes activos, una experiencia negativa viral puede afectar desproporcionadamente la percepción de marca.

---

## 10. RECOMENDACIONES PRIORITARIAS (Roadmap 90 días)

| Prioridad | Acción | Impacto | Esfuerzo |
|---|---|---|---|
| ✅ Hecho | Registro SBS 03053-2024 publicado en footer | Confianza | — |
| ✅ Hecho | Google Business Profile activo en Google Maps | SEO local | — |
| 🔴 Crítico | Aparecer en cuantoestaeldolar.pe, cambioseguro.com y otros comparadores | Tráfico | Bajo |
| 🔴 Crítico | Escalar reseñas en Google Business Profile (pedir activamente a clientes) | Confianza | Bajo |
| 🔴 Crítico | Publicar directorio (Rivera, Stenning) en el sitio web — diferenciador de confianza único | Confianza | Bajo |
| 🟠 Alto | Activar TikTok + Instagram con contenido educativo sobre el modelo marketplace | Marca | Medio |
| 🟠 Alto | Lanzar blog con contenido de tipo de cambio + explicación del modelo marketplace | SEO orgánico | Medio |
| 🟠 Alto | Estrategia de PR hacia Gestión, Semana Económica, RPP | Visibilidad | Medio |
| 🟠 Alto | Desarrollar PWA o versión mobile optimizada | Conversión | Alto |
| 🟡 Medio | Implementar programa de referidos | CAC | Medio |
| 🟡 Medio | Lanzar producto B2B (tesorería corporativa) | Ticket | Alto |
| 🟡 Medio | Integrar reportes SUNAT automáticos | Retención | Alto |
| 🟡 Medio | Estrategia de crecimiento del libro de órdenes (más vendedores activos) | Liquidez | Alto |
| 🟢 Largo plazo | API pública de tipo de cambio | Ecosistema | Alto |
| 🟢 Largo plazo | Integración con BCRP Fase 4 (Yape/Plin como canal) | Escala | Alto |

---

## 11. CONCLUSIÓN

**Mercado Cambiario** tiene los ingredientes para convertirse en un actor relevante del sector fintech cambiario peruano: modelo genuinamente diferenciado (único marketplace con libro de órdenes en un mercado de ~40 OTCs), equipo co-fundador con trayectorias bancarias de primer nivel, y un directorio institucional (ex-presidente ASBANC, ex-CEO BVL) extraordinario para una startup de este tamaño.

El mercado disponible es enorme: US$ 12,000 millones anuales en Perú, con el 99% todavía en manos de los bancos y un spread 4 veces mayor al de las fintech.

Sin embargo, los dos riesgos más inmediatos no son tecnológicos ni regulatorios — son **liquidez del libro de órdenes** (masa crítica de usuarios en ambos lados) y **visibilidad** (sin presencia en comparadores, medios ni redes sociales de consumo masivo). La empresa también tiene un activo completamente subutilizado: su directorio. Rivera y Stenning son nombres que abren puertas en medios, inversores y socios institucionales — y no aparecen en ninguna comunicación pública.

Con ejecución focalizada en estos puntos, y con el viento a favor de las elecciones 2026 (que históricamente disparan la demanda de dólares), el siguiente año es una ventana de oportunidad crítica.

---

*Fuentes: Startups Latam, Odoo Customer Cases, Gestión PE, Kambista Blog, Rextie Blog, Tucambista Blog, SBS Peru, Chambers and Partners Fintech Peru 2025, EY Guía Fintech Peru 2024/2025, BCRP, Infobae Peru, SURA Investments, CEPEG, ESAN, Infomercado.*
