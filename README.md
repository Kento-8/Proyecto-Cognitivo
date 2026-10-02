Semana 1
# Proyecto-Cognitivo
Equipo K.D.

- Nombre del equipo: K.D.
- Integrante 1: Kenth Andrey Afanador Pinedo
- Integrante 2: Denis Nicol Garcia Gonzalez

Semana 2 
<img width="1414" height="2000" alt="semana 2" src="https://github.com/user-attachments/assets/7d0b7aaf-d01f-426c-9a20-364452958cf5" />

Semana 3
<img width="1024" height="768" alt="Semana 3" src="https://github.com/user-attachments/assets/cd990f22-392e-41a8-8551-490e04b6865c" />

Semana 4
<img width="1920" height="1080" alt="K D Defensor JURÍDICO Y ESTRAT´ÉGICO jpg" src="https://github.com/user-attachments/assets/1bf59da8-2cb2-4dad-9512-8bbb86f0c31b" />

Semana 5
<img width="1024" height="768" alt="1" src="https://github.com/user-attachments/assets/19511563-651a-4e7a-a769-3437376f2a69" />
<img width="1024" height="768" alt="2" src="https://github.com/user-attachments/assets/f2fccc59-0762-4683-aa61-55c58349b763" />
<img width="1024" height="768" alt="3" src="https://github.com/user-attachments/assets/a3419af7-21b6-48d4-9e0a-ff011fd7c8eb" />

Semana 6
Ruido: Si le subes un contrato escaneado a la IA y el documento tiene manchas, errores tipográficos o páginas repetidas, eso es ruido visual o textual. 
la IA actúa como gatekeeper en la "puerta de entrada" del despacho, se encarga de:
•	Triage automatizado: Recibe al cliente potencial (por WhatsApp o web), entiende su problema mediante lenguaje natural y precalifica el caso. 
•	Filtro de asesoría: Responde preguntas logísticas básicas (horarios, tarifas, si el despacho lleva o no casos de familia) pero, cuando el usuario pide un consejo legal específico, la IA se detiene. 
•	Conversión a pago: Le aclara cordialmente al usuario que no da asesoría legal por esa vía y lo redirige a agendar una consulta formal de pago con un abogado humano
Reglas de Delimitación Legal

Prohibición de Asesoría Directa: La IA no debe emitir dictámenes, resolver estrategias procesales ni dar consejos legales definitivos a clientes finales de forma autónoma.Advertencia de Uso (Disclaimer): Toda respuesta dirigida a un usuario externo debe incluir un mensaje visible que aclare que la interacción es puramente informativa y no constituye una relación abogado-cliente.Escalada Humana Obligatoria: Cuando el usuario realice consultas de alta complejidad o mencione plazos urgentes (como un vencimiento de términos o una demanda en curso), la IA debe cortar la interacción amablemente y transferir el caso a un abogado humano.

Semana 7
## 3. Arquitectura de Memoria

Para que el asistente (K.D) funcione rigurosamente como un defensor jurídico estratégico, su base de datos interna se divide en **Memoria Semántica (LTM)** (su enciclopedia legal, reglas de procesamiento y límites éticos) y **Memoria Episódica (LTM)** (el contexto temporal y probatorio de los usuarios que atiende).

A continuación, se simula el diseño de esta base de datos mediante la siguiente tabla estructurada:

| Tipo de Memoria | Categoría de Datos | Descripción | Ejemplo de Entrada |
| :--- | :--- | :--- | :--- |
| Semántica (LTM) | Perfil y Reglas de Actuación | Configuración de identidad, tono profesional (empatía 5/10), y comunidad a la que asiste (UIS sede Barrancabermeja). | "Audiencia: Comunidad UIS; Tono: Objetivo, directo y basado en pruebas." |
| Semántica (LTM) | Normativa y Jurisprudencia | Base de datos interna con la Constitución, leyes, decretos y jurisprudencia vigentes en Colombia. | "Normativa Laboral: Revisar artículo vigente para validar un posible despido injustificado." |
| Semántica (LTM) | Diccionario de Inputs Crudos | Parámetros para clasificar la información inicial del usuario sin interpretar (amenazas, urgencias, contradicciones, restricciones). | "Urgencia / Pérdida: Detecta plazo o posible perjuicio, Ej: Plazo de 3 días para responder." |
| Semántica (LTM) | Modelos de Análisis Jurídico | Reglas lógicas para transformar inputs crudos en categorías representativas (Riesgo Jurídico, Conflicto Jurídico, Necesidad de Evidencia). | "Necesidad de Evidencia: Demostrar que se trabajaron horas extras mediante contratos y registros de horario." |
| Semántica (LTM) | Reglas de Delimitación Legal (Gatekeeper) | Instrucciones estrictas de compliance para evitar la asesoría directa, realizar triage automatizado y exigir escalada humana. | "Filtro: Si el usuario menciona plazos urgentes (ej. vencimiento de términos de una demanda), transferir a abogado humano." |
| Episódica (LTM) | Perfil y Contexto del Usuario | Datos clave del estudiante actual, historial del caso en curso, narrativa de los hechos y estado de las pruebas solicitadas. | "Usuario: Estudiante; Situación: Recibió una amenaza de sanción de la empresa; Documentos: Contrato escaneado subido." |

