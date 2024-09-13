Vamos a aprender a escoger y evaluar modelos de manera sistemática

A la hora de escoger, no siempre necesitamos decantarnos por el modelo más potente. También hay que considerar:
* coste (por uso o por hardware)
* velocidad
* transparencia (con qué datos se ha entrenado)
Los _small language models_ son chiquitos pero matones ;) [https://www.salesforce.com/blog/small-language-models/]
  
Para evaluar, podemos:
* Utilizar benchmarks (datos de prueba para tareas pre-existentes)
* Recurrir a métricas (idealmente que sean específicas para la tarea, como GEval, o al menos para tareas similares)
* Utilizar LLMs como evaluadores de otros LLMs

En nuestras pruebas lo ideal es guardar un registro, por ejemplo en Excel, del modelo probado y los valores obtenidos

## Referencias
* [https://www.confident-ai.com/blog/llm-evaluation-metrics-everything-you-need-for-llm-evaluation] GEval, faithfulness
* [https://docs.parea.ai/blog/eval-metrics-for-llm-apps-in-prod] Podríamos usar métricas similares a las de resumen
* [https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard]
  
