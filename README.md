# Carlos Alejandro de Antuñano

**Analista de Datos con criterio de auditor.** Pasé más de diez años en el Poder Judicial de la Federación, donde ninguna conclusión vale si no resiste la revisión de otra persona. Ahora aplico esa regla a los datos: cada modelo que construyo se compara contra una alternativa simple, y si no la supera, lo digo.

SQL · Python · Estadística · Series temporales · Ciudad de México

---

### El proyecto que mejor me representa

**[Chronos Risk Pipeline](https://github.com/AlejandroDeAntu/Chronos-Risk-Pipeline)**: vigila 7 activos financieros cada 15 minutos sin intervención humana, registra cada predicción, la compara después con lo que realmente pasó y se reentrena solo cuando el candidato supera al modelo base.

- El modelo de volatilidad GARCH(1,1)-t le ganó al promedio móvil de 20 días en **7 de 7 activos**.
- El detector de anomalías **no** le ganó al azar (F1 0.085 frente a 0.084). Está documentado en el README y lo uso como filtro de atención, no como predictor.
- Historial auditable en SQLite, contratos de datos con Pandera, 69 pruebas y CI en GitHub Actions.

### Otros análisis

| Proyecto | Pregunta | Resultado |
|---|---|---|
| [Predicción de cancelación de clientes](https://github.com/AlejandroDeAntu/Interconnect-Churn-Prediction) | ¿Qué clientes de una telecom van a cancelar? | LightGBM con ROC-AUC 0.892 sobre 7,043 clientes |
| [Viajes en taxi en Chicago](https://github.com/AlejandroDeAntu/Analisis-Viajes-Chicago-SQL) | ¿La lluvia alarga los viajes al aeropuerto? | Sí, de forma significativa los sábados (SQL + prueba de hipótesis) |
| [Ventas de videojuegos](https://github.com/AlejandroDeAntu/Analisis-de-ventas-de-videojuegos) | ¿Qué plataformas y géneros conviene impulsar en 2017? | Una estrategia por región con plataformas maduras y los géneros más rentables |
| [Preferencias musicales](https://github.com/AlejandroDeAntu/Analisis-Musical-Ciudades) | ¿Dos ciudades escuchan música distinta? | Menos de lo esperado: el pop domina en ambas |

### Contacto

aledeantu@gmail.com · [LinkedIn](https://www.linkedin.com/in/carlos-alejandro-de-antu%C3%B1ano-jass%C3%A1n-618807201/)
