# Acceso al portfolio: [isaamarod.github.io](https://isaamarod.github.io/ehds-course-portfolio/)

Portfolio Módulo Final para el curso titulado: "Espacio Europeo de Datos de Salud: retos y oportunidades en la asistencia sanitaria y en la investigación biomédica"

# 🧬 MED-RAM: One Health & AI Surveillance
> **Vigilancia Inteligente y Predicción de Resistencias Antimicrobianas en el Mediterráneo europeo bajo el enfoque One Health**

## Introducción:
historia del reglamento EEDS resumida  --> Seguir
 
---
## 🚀 SECCIÓN 1: Contexto y Problema
**Mi Rol:** Innovador Tecnológico.

Actualmente trabajo como Data Scientist (DS) y Data Engineer (DE) en el proyecto HealthDataMAD perteneciente a la iniciativa del Espacio Europeo de Datos Sanitarios (EEDS), al estar en contacto con los datos clínicos he podido comprobar el estado de base de datos poblacionales y las problemáticas relacionadas con el estado de estas. El EEDS es una gran oportunidad para mejorar no sólo la calidad los sistemas nacionales e internacionales sino la vida de los europeos y europeas. 

Aunque en muchos contextos los roles de DS y DE comparten ciertos dominios de actuación, sus competencias pueden diferenciarse claramente. Por un lado, en el EEDS y en general, el rol de Data Engineer se centra principalmente en construir estos repositorios de datos garantizandp la seguridad e interoperabilidad a distintos niveles (HL7, OMOP, SNOMED, LOINC...), así como en mantenimiento de repositorios de datos que aseguren la calidad del dato y la seguridad (por ejemplo, consistencia en formatos, estructuras y estándares) dentro del OADS nacional.

Por otro lado, el rol de Data Scientist se orienta a la creación y preparación de bases de datos coherentes con las hipótesis planteadas en los distintos casos de uso. Asimismo, aborda la calidad del dato desde una perspectiva más científica y analítica, enfocada a asegurar que los datos sean adecuados para el análisis, la generación de conocimiento y la validación de resultados. Posteriormente, también realiza los análisis y modelado con los datos proporcionados por los OADS en los Entornos Seguros ,por ejemplo, la creación de los modelos de MED-RAM para el control de la RAM en la Europa Mediterránea.

Mi principal interés en este entregable es aplicar los conocimientos adquiridos en el curso con los previos desde el marco de estas funciones, para ello, aplico lo aprendido a un proyecto ficticio llamado MED-RAM cuyo objetivo es solicitar datos al OADS...la distribución de la RAM puede variar incluso a nivel de la misma poblacion, en concreto, como uno de los factores a gran escala es el clima y la capacidad económica u los países del mediterráneo europeo comparten ... el proyecto MED-RAM trata de analizar y mejorar... --> Seguir

### Desafío
De la hipótesis a resolver:
La resistencia antimicrobiana (RAM) ha sido definida como "pandemia silenciosa" por la OMS. Es un problema que precisa de una visión global ya que involucra salud humana, veterinaria y ambiental lo que dificulta una respuesta coordinada. Como rol con un perfil híbrido científico/técnico, identifico que el problema no es sólo la falta de datos, sino la falta de **interoperabilidad y acceso seguro**.

De forma general como DS y DE:


Por lo tanto el EEDS: 
Permite superar los silos de información mediante:
* **Acceso secundario a datos multisectoriales** (Art. 33).
* **Uso de IA y Machine Learning** para predecir y controlar brotes de RAM, control del uso de antibióticos y la construcción de nuevas guías de salud pública.

---

## ⚖️ SECCIÓN 2: Derechos y Deberes

### A) Derechos del Paciente (Uso Primario)
La ley recoge los siguientes derechos de los pacientes en el EEDS: 

En el ecosistema MED-RAM, garantizamos los derechos de acceso, rectificación y portabilidad. Los pacientes podrán visualizar qué datos de sus antibiogramas han sido utilizados para el bien común a través del nodo nacional de salud. --> Seguir Esto tiene sentido?

### B) Fines Permitidos vs. Prohibidos relacionados con el Raglamento EEDS
* **Fines Permitidos:** Investigación científica e innovación para el control de la RAM en la europa mediterránea (**Art. 53.1.e/f**) y vigilancia de amenazas transfronterizas al utilizar datos de varios países europeos(**Art. 53.1.j**).
* **Fines Prohibidos:** Se bloquea técnicamente cualquier uso para marketing o cálculo de primas de seguros ya que los pacientes que hayan padecido RAM tienen posibilidad de recaídas y, por lo tanto, mayor posibilidad de mostalidad, esto podría afectar a su libertad a la hora de gestiones económicas o en seguros privados (**Art. 54.1.a/b**).

### C) Principios RGPD & Autoexclusión
* **Minimización:** Solo procesamos los biomarcadores de resistencia y variables ambientales necesarias.
* **Derecho de Opt-out:** Respetamos la autoexclusión del paciente, salvo en emergencias sanitarias graves donde el interés público sea prevalente, para esto último necesitaríamos la opinión del EHDS Board en el caso de que los OADs nacionales de los países involucrados lo crean necesario.
 --> Seguir arreglar esto
Si tu proyecto involucra uso secundario, ¿qué fin persigue? (Usos permitidos en el Art. 53 del Reglamento EEDS)
¿Qué usos explícitamente prohíbes? (Usos prohibidos Art. 54 del Reglamento EEDS).
Ejemplo: "Mi investigación persigue mejora de prestación sanitaria (Art. 53.1.f), pero explícitamente evitamos cualquier discriminación en seguros (Art. 54.1.a)"
C) Principios de Protección de Datos

Cita los 6 principios del Reglamento General de Protección de Datos  del Módulo 2.
Explica cómo se aplican al menos 2 de ellos a tu proyecto.
D) Derecho de Autoexclusión (Módulo 2)

¿Cómo respetarías el derecho de autoexclusión (opt-out) de pacientes en tu iniciativa?
¿Cuáles serían las excepciones (emergencias, salud pública)?
E) Mecanismos de Auditoría y Confianza

¿Cómo implementarías registros de acceso (Derecho a obtener información sobre accesos)?
¿Quién supervisa?

F) Consentimiento e Información al Paciente

¿Qué información darías a pacientes de forma transparente?

Redacta un breve párrafo explicativo para los/as pacientes.

**Objetivo:** Demostrar la comprensión de los derechos en el uso primario y las restricciones técnicas en el uso secundario dentro del marco del EEDS.
------------------------------------

### A) Derechos del Paciente en MED-RAM
Los 6 derechos principales son: **acceso, rectificación, portabilidad, restricción, oposición** y el derecho a **no ser objeto de decisiones automatizadas**.

* **Aplicación en el proyecto:** MED-RAM no centralizaría los datos; utiliza el OADS como punto de acceso federado. El OADS habilita un Entorno Seguro de Procesamiento (ESP) donde se ejecuta nuestra analítica avanzada bajo el cumplimiento del ENS por lo tanto relacionado con MED-RAM, los pacientes podrán verificar a través de sus carpetas de salud nacionales qué datos de sus antibiogramas han sido aportados al nodo nacional, se respeta técnicamente el derecho de **restricción**: si un paciente limita el acceso a ciertos datos microbiológicos, estos serán filtrados  y no entrarán en la creación de los modelos matemáticos.

------------------------------------------- ME QUEDO AQUÍ

### B) Fines Permitidos vs. Prohibidos (Art. 53 y 54)
* [cite_start]**Fines Permitidos (Uso Secundario):** El proyecto se fundamenta legalmente en la **investigación científica e innovación** (Art. 53.1.e/f) [cite: 64, 66] [cite_start]y en la protección ante **amenazas transfronterizas graves para la salud** (Art. 53.1.a y j)[cite: 65, 83].
* **Usos Prohibidos:** El sistema MED-RAM prohíbe explícitamente el uso de modelos para la **exclusión de seguros**, el incremento de primas, la publicidad comercial o cualquier **decisión perjudicial individual** basada en el perfil de resistencia del paciente (Art. 54.1.a y b).

### C) Principios de Protección de Datos (RGPD)
Aplicamos los 6 principios: Licitud, Limitación de la finalidad, Minimización, Exactitud, Limitación del plazo e Integridad/Confidencialidad.

* [cite_start]**Minimización:** Solo solicitamos variables estrictamente necesarias (identificador seudonimizado, código ICD-10 y perfil de resistencia R/S/I), eliminando cualquier dato identificativo directo[cite: 45, 46].
* **Integridad y Confidencialidad:** El procesamiento se realiza exclusivamente en **Entornos Seguros de Procesamiento (ESP)** certificados bajo el **Esquema Nacional de Seguridad (ENS)**, garantizando que los datos nunca abandonen el control del OAD.

### D) Derecho de Autoexclusión (Opt-out)
[cite_start]Respetamos el derecho de **opt-out** de forma reversible[cite: 29]. [cite_start]Si un paciente solicita que sus datos no se compartan transfronterizamente, el sistema lo excluirá de la recogida para uso secundario[cite: 26, 27].
* [cite_start]**Excepción:** Solo se anulará la restricción en situaciones de **interés vital** (riesgo de muerte o pérdida de conciencia inminente) o alertas de salud pública críticas[cite: 19].

### E) Mecanismos de Auditoría y Confianza
[cite_start]Implementamos **registros de acceso (logs)** inmutables para cada consulta del algoritmo[cite: 34]. Estos registros permiten la trazabilidad total:
* [cite_start]**Supervisión:** El acceso es controlado por el **OAD (Organismo de Acceso a Datos de Salud)** [cite: 52] [cite_start]y auditado por las autoridades de protección de datos para detectar accesos no lícitos o por "curiosidad"[cite: 21].

### F) Información al Paciente (Transparencia)
La base legal se fundamenta en el **interés público y la investigación científica** (Art. 6 y 9 del RGPD).

**Mensaje para el paciente:**
> [cite_start]*"Tus datos de salud, junto con información ambiental y veterinaria, nos ayudan a predecir qué antibióticos dejarán de ser eficaces en tu región. En MED-RAM usamos esta información de forma anónima y segura para que los médicos elijan el tratamiento correcto más rápido y proteger a toda la comunidad frente a las superbacterias"*[cite: 70, 71].


---

## 🛠️ SECCIÓN 3: Tecnología, Estándares y Seguridad

### 🏗️ Arquitectura de Interoperabilidad
* **Estándares:** Implementación de **HL7 FHIR** para datos clínicos y **OMOP CDM** para la armonización de registros transfronterizos.
* **Modelo:** **Red Federada**. El algoritmo de IA viaja a los datos alojados en los nodos nacionales; los datos brutos nunca salen de su jurisdicción original.

### 🔒 Seguridad
* **Entornos Seguros de Procesamiento (ESP):** El análisis se realiza en infraestructuras certificadas bajo el **Esquema Nacional de Seguridad (ENS)**.
* **Privacidad:** Aplicación de **anonimización por defecto** y técnicas de privacidad diferencial para proteger la identidad del paciente.

---

## 🏛️ SECCIÓN 4: Gobernanza y Actores

| Nivel | Rol en MED-RAM |
| :--- | :--- |
| **Local** | Hospitales y centros veterinarios como **Tenedores de Datos**. |
| **Nacional** | El **OAD** gestiona los permisos y el entorno seguro (ESP). |
| **Europeo** | El **EHDS Board** asegura la coordinación y el impacto transfronterizo. |

### Solicitud al OAD (Simulacro)
*"Como innovador tecnológico, solicito acceso a los datos del Art. 33 para entrenar modelos predictivos RAM. El proyecto se ejecutará íntegramente en el ESP nacional, cumpliendo con los estándares xShare y EUCAIM."*

---

## 📈 SECCIÓN 5: Impacto y Reflexión

### Beneficios Esperados
* **Médicos:** Prescripción de precisión basada en datos locales en tiempo real.
* **Sociedad:** Reducción de la mortalidad por bacterias multirresistentes.
* **Investigadores:** Acceso a un dataset masivo y armonizado único en el mundo.

### KPIs (Indicadores de Éxito)
1.  **Precisión:** >85% en la detección de cepas emergentes.
2.  **Seguridad:** 0 brechas de datos registradas.
3.  **Adopción:** Integración de al menos 3 países del arco mediterráneo en 18 meses.

---

> **Reflexión Personal:** El curso me ha revelado que la innovación en salud no es solo código, sino **gobernanza**. Entender el rol de los OADS y el derecho de acceso secundario cambia mi forma de diseñar soluciones digitales para la UE.
