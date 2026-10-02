# Ecosistema de Automatización IA para Negocios
Sistema de calificación de leads y envío de propuesta personalizada con aprobación humana.

**Alumno/a:** Rodrigo Murguiarte | **Curso:** AI Automation

## Qué hace
1. Un lead entra a Airtable (Estado = Nuevo).
2. Make lo analiza con Gemini: califica prioridad y puntaje, y redacta una propuesta.
3. El resultado se guarda en Airtable y Slack pide aprobación humana.
4. Una persona aprueba o rechaza.
5. Si aprueba, Gmail envía la propuesta; si rechaza, no se envía nada.
6. Los errores se registran en Airtable y se monitorean en un panel de control.

## Stack
| Categoría | Herramienta |
|---|---|
| Orquestador | Make |
| Base de datos | Airtable |
| Procesamiento IA | Google Gemini |
| Canal de salida | Slack y Gmail |

## Enlaces
- Documentación completa (PDF): Coderhouse - Entrega final.pdf https://github.com/rodrols13/EntregaCoderhouse/blob/c83d716e286cff817c1a1797701a3f04c03fc83c/Coderhouse%20-%20Entrega%20final.pdf 
- Diagrama de arquitectura (PDF): diagrama-arquitectura.drawio (1).pdf https://github.com/rodrols13/EntregaCoderhouse/blob/c83d716e286cff817c1a1797701a3f04c03fc83c/diagrama-arquitectura.drawio%20(1).pdf 
- Base de datos (solo lectura): https://airtable.com/appFdY9lD9Hj0obwd/shrt1byBEwDndDriy
- Panel de control (vista pública): https://airtable.com/appFdY9lD9Hj0obwd/shrXDav3inwCT8PvD/tblFjRuTDOzLVZxLm
- Tablero por estado (vista pública): https://airtable.com/appFdY9lD9Hj0obwd/shrXDav3inwCT8PvD/tblFjRuTDOzLVZxLm
-                                     https://drive.google.com/file/d/1snpsVDOe_tFDU4kaSOb_cl6BTuQ_m4Eh/view?usp=sharing
- Panel de errores (vista pública): https://airtable.com/appFdY9lD9Hj0obwd/shrt1byBEwDndDriy/tbl1eOPv7Wu2Y8rOv/viwaVBDDTPzZB1oP6
- Copia del PDF en Drive: https://drive.google.com/file/d/1M4XdvyG2z96b-UBn4IVW2_bJYEqXKvVt/view?usp=sharing

## Archivos técnicos
- Blueprint de Make, análisis con IA - https://github.com/rodrols13/EntregaCoderhouse/blob/c83d716e286cff817c1a1797701a3f04c03fc83c/E1%20-%20Analizar%20lead%20con%20AI.blueprint.json
- Blueprint de Make, aprobación y envío - https://github.com/rodrols13/EntregaCoderhouse/blob/c83d716e286cff817c1a1797701a3f04c03fc83c/E2%20-%20Aprobacio%CC%81n%20y%20envi%CC%81o.blueprint.json
- Evidencias del flujo, la base de datos y las pruebas - https://drive.google.com/drive/folders/1k3svlu-6HVJ1q-Lje5I7EixmAZ6jlS5R?usp=sharing

## Dónde está cada criterio de la rúbrica
| Criterio | Dónde verlo |
|---|---|
| Mapa de arquitectura | PDF, sección 1, y diagrama-arquitectura.pdf |
| Estructuras de datos | PDF, sección 2 |
| Optimización de costos | PDF, sección 3 |
| Seguridad y resiliencia | PDF, sección 4 |
| Dashboard de control | PDF, sección 5, y los enlaces de arriba |

## Notas
- Todos los datos de prueba son ficticios.
- El proyecto se construyó con planes gratuitos; los escenarios se ejecutan a demanda.
- Las claves de API no se incluyen en el repositorio.
