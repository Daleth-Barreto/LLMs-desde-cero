# Construye un modelo de lenguaje grande (desde cero)

*(Nota: Esta es una traducción al español técnico realizada por **Hernández Barreto Alan Daleth**. Todos los créditos de la obra original, incluyendo el código, el libro, los videos y los materiales didácticos, pertenecen exclusivamente a su autor original,* ***Sebastian Raschka*** *).*

Este repositorio contiene el código para desarrollar, preentrenar y aplicar *fine-tuning* a un LLM tipo GPT y es el repositorio oficial de código del libro [Build a Large Language Model (From Scratch)](https://www.google.com/search?q=https://amzn.to/4fqvn0D).

En *[Build a Large Language Model (From Scratch)](https://www.google.com/search?q=http://mng.bz/orYv)*, aprenderás y entenderás cómo funcionan los *Large Language Models* (LLMs) desde adentro hacia afuera, programándolos desde cero, paso a paso. En este libro, el autor te guiará a través de la creación de tu propio LLM, explicando cada etapa con texto claro, diagramas y ejemplos.

El método descrito en este libro para entrenar y desarrollar tu propio modelo —pequeño pero funcional con fines educativos— refleja el enfoque utilizado en la creación de modelos fundacionales a gran escala, como los que respaldan a ChatGPT. Además, este libro incluye código para cargar los pesos de modelos preentrenados de mayor tamaño para realizar *fine-tuning*.

* Enlace al [repositorio de código fuente oficial](https://www.google.com/search?q=https://github.com/rasbt/LLMs-from-scratch)
* [Enlace al libro en Manning (sitio web de la editorial)](https://www.google.com/search?q=http://mng.bz/orYv)
* [Enlace a la página del libro en Amazon.com](https://www.google.com/search?q=https://www.amazon.com/gp/product/1633437167)
* ISBN 9781633437166

Para descargar una copia de este repositorio, haz clic en el botón de [Download ZIP](https://www.google.com/search?q=https://github.com/rasbt/LLMs-from-scratch/archive/refs/heads/main.zip) o ejecuta el siguiente comando en tu terminal:

```bash
git clone --depth 1 https://github.com/rasbt/LLMs-from-scratch.git

```

(Si descargaste el paquete de código desde el sitio web de Manning, por favor considera visitar el repositorio oficial en GitHub en [https://github.com/rasbt/LLMs-from-scratch](https://www.google.com/search?q=https://github.com/rasbt/LLMs-from-scratch) para obtener las últimas actualizaciones).

# Tabla de Contenidos

Ten en cuenta que este archivo `README.md` es un archivo Markdown (`.md`). Si has descargado este paquete de código desde el sitio web de Manning y lo estás visualizando en tu computadora local, te recomiendo usar un editor o visor de Markdown para una visualización adecuada. Si aún no has instalado un editor de Markdown, [Ghostwriter](https://www.google.com/search?q=https://ghostwriter.kde.org) es una buena opción gratuita.

Alternativamente, puedes ver este y otros archivos en GitHub en [https://github.com/rasbt/LLMs-from-scratch](https://www.google.com/search?q=https://github.com/rasbt/LLMs-from-scratch) desde tu navegador, el cual renderiza Markdown automáticamente.

> **Consejo:**
> Si buscas orientación sobre la instalación de Python, paquetes de Python y cómo configurar tu entorno de código, te sugiero leer el archivo [README.md](https://www.google.com/search?q=setup/README.md) ubicado en el directorio [setup](https://www.google.com/search?q=setup).

* [Guía de Solución de Problemas](https://www.google.com/search?q=./troubleshooting.md)

| Título del Capítulo | Código Principal (para Acceso Rápido) | Todo el Código + Suplementario |
| --- | --- | --- |
| [Recomendaciones de configuración](https://www.google.com/search?q=setup) [Cómo leer mejor este libro](https://www.google.com/search?q=https://sebastianraschka.com/blog/2025/reading-books.html) | - | - |
| Cap 1: Entendiendo los *Large Language Models* | Sin código | - |
| Cap 2: Trabajando con datos de texto | - [ch02.ipynb](https://www.google.com/search?q=ch02/01_main-chapter-code/ch02.ipynb)- [dataloader.ipynb](https://www.google.com/search?q=ch02/01_main-chapter-code/dataloader.ipynb) (resumen)- [exercise-solutions.ipynb](https://www.google.com/search?q=ch02/01_main-chapter-code/exercise-solutions.ipynb) | [./ch02](https://www.google.com/search?q=./ch02) |
| Cap 3: Programando mecanismos de atención | - [ch03.ipynb](https://www.google.com/search?q=ch03/01_main-chapter-code/ch03.ipynb)- [multihead-attention.ipynb](https://www.google.com/search?q=ch03/01_main-chapter-code/multihead-attention.ipynb) (resumen) - [exercise-solutions.ipynb](https://www.google.com/search?q=ch03/01_main-chapter-code/exercise-solutions.ipynb) | [./ch03](https://www.google.com/search?q=./ch03) |
| Cap 4: Implementando un modelo GPT desde cero | - [ch04.ipynb](https://www.google.com/search?q=ch04/01_main-chapter-code/ch04.ipynb)- [gpt.py](https://www.google.com/search?q=ch04/01_main-chapter-code/gpt.py) (resumen)- [exercise-solutions.ipynb](https://www.google.com/search?q=ch04/01_main-chapter-code/exercise-solutions.ipynb) | [./ch04](https://www.google.com/search?q=./ch04) |
| Cap 5: Preentrenamiento con datos no etiquetados | - [ch05.ipynb](https://www.google.com/search?q=ch05/01_main-chapter-code/ch05.ipynb)- [gpt_train.py](https://www.google.com/search?q=ch05/01_main-chapter-code/gpt_train.py) (resumen) - [gpt_generate.py](https://www.google.com/search?q=ch05/01_main-chapter-code/gpt_generate.py) (resumen) - [exercise-solutions.ipynb](https://www.google.com/search?q=ch05/01_main-chapter-code/exercise-solutions.ipynb) | [./ch05](https://www.google.com/search?q=./ch05) |
| Cap 6: *Fine-tuning* para clasificación de texto | - [ch06.ipynb](https://www.google.com/search?q=ch06/01_main-chapter-code/ch06.ipynb) - [gpt_class_finetune.py](https://www.google.com/search?q=ch06/01_main-chapter-code/gpt_class_finetune.py) - [exercise-solutions.ipynb](https://www.google.com/search?q=ch06/01_main-chapter-code/exercise-solutions.ipynb) | [./ch06](https://www.google.com/search?q=./ch06) |
| Cap 7: *Fine-tuning* para seguir instrucciones | - [ch07.ipynb](https://www.google.com/search?q=ch07/01_main-chapter-code/ch07.ipynb)- [gpt_instruction_finetuning.py](https://www.google.com/search?q=ch07/01_main-chapter-code/gpt_instruction_finetuning.py) (resumen)- [ollama_evaluate.py](https://www.google.com/search?q=ch07/01_main-chapter-code/ollama_evaluate.py) (resumen)- [exercise-solutions.ipynb](https://www.google.com/search?q=ch07/01_main-chapter-code/exercise-solutions.ipynb) | [./ch07](https://www.google.com/search?q=./ch07) |
| Apéndice A: Introducción a PyTorch | - [code-part1.ipynb](https://www.google.com/search?q=appendix-A/01_main-chapter-code/code-part1.ipynb)- [code-part2.ipynb](https://www.google.com/search?q=appendix-A/01_main-chapter-code/code-part2.ipynb)- [DDP-script.py](https://www.google.com/search?q=appendix-A/01_main-chapter-code/DDP-script.py)- [exercise-solutions.ipynb](https://www.google.com/search?q=appendix-A/01_main-chapter-code/exercise-solutions.ipynb) | [./appendix-A](https://www.google.com/search?q=./appendix-A) |
| Apéndice B: Referencias y Lecturas Adicionales | Sin código | [./appendix-B](https://www.google.com/search?q=./appendix-B) |
| Apéndice C: Soluciones a los Ejercicios | - [lista de soluciones de ejercicios](https://www.google.com/search?q=appendix-C) | [./appendix-C](https://www.google.com/search?q=./appendix-C) |
| Apéndice D: Añadiendo funcionalidades al *training loop* | - [appendix-D.ipynb](https://www.google.com/search?q=appendix-D/01_main-chapter-code/appendix-D.ipynb) | [./appendix-D](https://www.google.com/search?q=./appendix-D) |
| Apéndice E: *Fine-tuning* eficiente en parámetros con LoRA | - [appendix-E.ipynb](https://www.google.com/search?q=appendix-E/01_main-chapter-code/appendix-E.ipynb) | [./appendix-E](https://www.google.com/search?q=./appendix-E) |

El modelo mental a continuación resume los contenidos cubiertos en este libro.

## Requisitos Previos

El requisito previo más importante es una base sólida en programación con Python.
Con este conocimiento, estarás bien preparado para explorar el fascinante mundo de los LLMs
y comprender los conceptos y ejemplos de código presentados en este libro.

Si tienes algo de experiencia con redes neuronales profundas, puede que encuentres ciertos conceptos más familiares, ya que los LLMs están construidos sobre estas arquitecturas.

Este libro utiliza PyTorch para implementar el código desde cero sin usar ninguna librería externa de LLMs. Aunque la destreza en PyTorch no es un requisito previo, la familiaridad con sus conceptos básicos es ciertamente útil. Si eres nuevo en PyTorch, el Apéndice A proporciona una introducción concisa a la librería. Alternativamente, mi libro, [PyTorch in One Hour: From Tensors to Training Neural Networks on Multiple GPUs](https://www.google.com/search?q=https://sebastianraschka.com/teaching/pytorch-1h/), puede resultarte útil para aprender lo esencial.

## Requisitos de Hardware

El código de los capítulos principales de este libro está diseñado para ejecutarse en *laptops* convencionales dentro de un marco de tiempo razonable y no requiere de hardware especializado. Este enfoque garantiza que una amplia audiencia pueda interactuar con el material. Además, el código utiliza automáticamente GPUs si están disponibles. (Por favor, consulta el documento de [setup](https://www.google.com/search?q=https://github.com/rasbt/LLMs-from-scratch/blob/main/setup/README.md) para recomendaciones adicionales).

## Curso en Video

[Un curso en video complementario de 17 horas y 15 minutos](https://www.google.com/search?q=https://www.manning.com/livevideo/master-and-build-large-language-models) donde el autor, Sebastian Raschka, programa a través de cada capítulo del libro. El curso está organizado en capítulos y secciones que reflejan la estructura del libro, por lo que puede usarse como una alternativa independiente al libro o como un recurso complementario para programar a la par.

## Libro Complementario / Secuela

*[Build A Reasoning Model (From Scratch)](https://www.google.com/search?q=https://mng.bz/lZ5B)*, aunque es un libro independiente, puede considerarse como una secuela de *Build A Large Language Model (From Scratch)*.

Comienza con un modelo preentrenado e implementa diferentes enfoques de razonamiento, incluyendo escalado en tiempo de inferencia (*inference-time scaling*), aprendizaje por refuerzo (*reinforcement learning*) y destilación (*distillation*), para mejorar las capacidades de razonamiento del modelo.

De manera similar a *Build A Large Language Model (From Scratch)*, *[Build A Reasoning Model (From Scratch)](https://www.google.com/search?q=https://mng.bz/lZ5B)* adopta un enfoque práctico implementando estos métodos desde cero.

* Enlace de Amazon (Por definirse)
* [Enlace a Manning](https://www.google.com/search?q=https://mng.bz/lZ5B)
* [Repositorio en GitHub](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch)

## Ejercicios

Cada capítulo del libro incluye varios ejercicios. Las soluciones están resumidas en el Apéndice C, y los *notebooks* de código correspondientes están disponibles en las carpetas principales de los capítulos de este repositorio (por ejemplo, [./ch02/01_main-chapter-code/exercise-solutions.ipynb](https://www.google.com/search?q=./ch02/01_main-chapter-code/exercise-solutions.ipynb)).

Además de los ejercicios de código, puedes descargar un PDF gratuito de 170 páginas titulado [Test Yourself On Build a Large Language Model (From Scratch)](https://www.google.com/search?q=https://www.manning.com/books/test-yourself-on-build-a-large-language-model-from-scratch) desde el sitio web de Manning. Contiene aproximadamente 30 preguntas de cuestionario y soluciones por capítulo para ayudarte a evaluar tu comprensión.

## Material Adicional

Varias carpetas contienen materiales opcionales como un *bonus* para los lectores interesados:

* **Configuración (*Setup*)**
* [Consejos de configuración de Python](https://www.google.com/search?q=setup/01_optional-python-setup-preferences)
* [Instalación de paquetes y bibliotecas de Python usados en este libro](https://www.google.com/search?q=setup/02_installing-python-libraries)
* [Guía de configuración del entorno con Docker](https://www.google.com/search?q=setup/03_optional-docker-environment)


* **Capítulo 2: Trabajando con datos de texto**
* [*Tokenizer* Byte Pair Encoding (BPE) desde cero](https://www.google.com/search?q=ch02/05_bpe-from-scratch/bpe-from-scratch-simple.ipynb)
* [Comparando varias implementaciones de Byte Pair Encoding (BPE)](https://www.google.com/search?q=ch02/02_bonus_bytepair-encoder)
* [Entendiendo la diferencia entre *Embedding Layers* y *Linear Layers](https://www.google.com/search?q=ch02/03_bonus_embedding-vs-matmul)*
* [Intuición del *Dataloader* con números simples](https://www.google.com/search?q=ch02/04_bonus_dataloader-intuition)


* **Capítulo 3: Programando mecanismos de atención**
* [Comparando implementaciones eficientes de *Multi-Head Attention](https://www.google.com/search?q=ch03/02_bonus_efficient-multihead-attention/mha-implementations.ipynb)*
* [Entendiendo los *Buffers* de PyTorch](https://www.google.com/search?q=ch03/03_understanding-buffers/understanding-buffers.ipynb)


* **Capítulo 4: Implementando un modelo GPT desde cero**
* [Análisis de FLOPs](https://www.google.com/search?q=ch04/02_performance-analysis/flops-analysis.ipynb)
* *[KV Cache](https://www.google.com/search?q=ch04/03_kv-cache)*
* [Alternativas de *Attention](https://www.google.com/search?q=ch04/%23attention-alternatives)*
* *[Grouped-Query Attention](https://www.google.com/search?q=ch04/04_gqa)*
* *[Multi-Head Latent Attention](https://www.google.com/search?q=ch04/05_mla)*
* *[Sliding Window Attention](https://www.google.com/search?q=ch04/06_swa)*
* *[Gated DeltaNet](https://www.google.com/search?q=ch04/08_deltanet)*
* *[DeepSeek Sparse Attention (DSA)](https://www.google.com/search?q=ch04/09_dsa)*
* *[Cross-Layer KV Sharing](https://www.google.com/search?q=ch04/10_kv-sharing)*


* [*Mixture-of-Experts* (MoE)](https://www.google.com/search?q=ch04/07_moe)


* **Capítulo 5: Preentrenamiento con datos no etiquetados**
* [Métodos alternativos de carga de pesos](https://www.google.com/search?q=ch05/02_alternative_weight_loading/)
* [Preentrenamiento de GPT en el *dataset* del Proyecto Gutenberg](https://www.google.com/search?q=ch05/03_bonus_pretraining_on_gutenberg)
* [Añadiendo funcionalidades al *training loop](https://www.google.com/search?q=ch05/04_learning_rate_schedulers)*
* [Optimizando hiperparámetros para el preentrenamiento](https://www.google.com/search?q=ch05/05_bonus_hparam_tuning)
* [Construyendo una Interfaz de Usuario para interactuar con el LLM preentrenado](https://www.google.com/search?q=ch05/06_user_interface)
* [Convirtiendo GPT a Llama](https://www.google.com/search?q=ch05/07_gpt_to_llama)
* [Carga de pesos del modelo eficiente en memoria](https://www.google.com/search?q=ch05/08_memory_efficient_weight_loading/memory-efficient-state-dict.ipynb)
* [Extendiendo el *Tokenizer* BPE de Tiktoken con nuevos *tokens](https://www.google.com/search?q=ch05/09_extending-tokenizers/extend-tiktoken.ipynb)*
* [Consejos de rendimiento en PyTorch para un entrenamiento de LLM más rápido](https://www.google.com/search?q=ch05/10_llm-training-speed)
* [Arquitecturas de LLMs](https://www.google.com/search?q=ch05/%23llm-architectures-from-scratch)
* [Llama 3.2 desde cero](https://www.google.com/search?q=ch05/07_gpt_to_llama/standalone-llama32.ipynb)
* [Qwen3 *Dense* y *Mixture-of-Experts* (MoE) desde cero](https://www.google.com/search?q=ch05/11_qwen3/)
* [Gemma 3 desde cero](https://www.google.com/search?q=ch05/12_gemma3/)
* [Olmo 3 desde cero](https://www.google.com/search?q=ch05/13_olmo3/)
* [Tiny Aya desde cero](https://www.google.com/search?q=ch05/15_tiny-aya/)
* [Qwen3.5 desde cero](https://www.google.com/search?q=ch05/16_qwen3.5/)
* [Gemma 4 E2B y E4B desde cero](https://www.google.com/search?q=ch05/17_gemma4/)


* [Capítulo 5 con otros LLMs como reemplazo directo (ej., Llama 3, Qwen 3)](https://www.google.com/search?q=ch05/14_ch05_with_other_llms/)


* **Capítulo 6: *Fine-tuning* para clasificación**
* [Experimentos adicionales haciendo *fine-tuning* a diferentes capas y usando modelos más grandes](https://www.google.com/search?q=ch06/02_bonus_additional-experiments)
* [*Fine-tuning* de diferentes modelos en el *dataset* de 50k reseñas de películas de IMDb](https://www.google.com/search?q=ch06/03_bonus_imdb-classification)
* [Construyendo una Interfaz de Usuario para interactuar con el clasificador de Spam basado en GPT](https://www.google.com/search?q=ch06/04_user_interface)


* **Capítulo 7: *Fine-tuning* para seguir instrucciones**
* [Utilidades de *Datasets* para encontrar cuasi-duplicados y crear entradas en voz pasiva](https://www.google.com/search?q=ch07/02_dataset-utilities)
* [Evaluando respuestas de instrucciones usando la API de OpenAI y Ollama](https://www.google.com/search?q=ch07/03_model-evaluation)
* [Generando un *dataset* para *Instruction Finetuning](https://www.google.com/search?q=ch07/05_dataset-generation/llama3-ollama.ipynb)*
* [Mejorando un *dataset* para *Instruction Finetuning](https://www.google.com/search?q=ch07/05_dataset-generation/reflection-gpt4.ipynb)*
* [Generando un *Preference Dataset* con Llama 3.1 70B y Ollama](https://www.google.com/search?q=ch07/04_preference-tuning-with-dpo/create-preference-data-ollama.ipynb)
* [Direct Preference Optimization (DPO) para el alineamiento del LLM](https://www.google.com/search?q=ch07/04_preference-tuning-with-dpo/dpo-from-scratch.ipynb)
* [Construyendo una Interfaz de Usuario para interactuar con el modelo GPT de instrucciones](https://www.google.com/search?q=ch07/06_user_interface)



Más material extra del repositorio [Reasoning From Scratch](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch):

* **Conceptos básicos de Qwen3 (Desde cero)**
* [Recorrido por el código fuente de Qwen3](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/blob/main/chC/01_main-chapter-code/chC_main.ipynb)
* [Qwen3 Optimizado](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/tree/main/ch02/03_optimized-LLM)


* **Evaluación**
* [Evaluación basada en verificadores (MATH-500)](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/tree/main/ch03)
* [Evaluación de Opción Múltiple (MMLU)](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/blob/main/chF/02_mmlu)
* [Evaluación en *Leaderboards* de LLMs](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/blob/main/chF/03_leaderboards)
* [Evaluación con LLM como juez (*LLM-as-a-Judge*)](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/blob/main/chF/04_llm-judge)


* **Escalado en Inferencia (*Inference Scaling*)**
* [Auto-consistencia (*Self-Consistency*)](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/blob/main/ch04/01_main-chapter-code/ch04_main.ipynb)
* [Auto-refinamiento (*Self-Refinement*)](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/blob/main/ch05/01_main-chapter-code/ch05_main.ipynb)


* **Aprendizaje por Refuerzo / *Reinforcement Learning* (RL)**
* [RLVR con GRPO desde cero](https://www.google.com/search?q=https://github.com/rasbt/reasoning-from-scratch/blob/main/ch06/01_main-chapter-code/ch06_main.ipynb)



## Preguntas, Comentarios y Contribuciones a este Repositorio

Cualquier tipo de retroalimentación es bienvenida, idealmente a través del [Manning Forum](https://www.google.com/search?q=https://livebook.manning.com/forum%3Fproduct%3Draschka%26page%3D1) o [GitHub Discussions](https://www.google.com/search?q=https://github.com/rasbt/LLMs-from-scratch/discussions). Igualmente, si tienes alguna pregunta o simplemente quieres rebotar ideas con otros, no dudes en publicarlas en el foro también.

Ten en cuenta que, dado que este repositorio contiene el código correspondiente a un libro impreso, actualmente el autor no puede aceptar contribuciones que extiendan el contenido del código de los capítulos principales, ya que introduciría desviaciones respecto al libro físico. Mantenerlo consistente ayuda a asegurar una experiencia fluida para todos.

## Citación

Si encuentras útil este libro o código para tu investigación, por favor considera citarlo.

Citación estilo Chicago:

> Raschka, Sebastian. *Build A Large Language Model (From Scratch)*. Manning, 2024. ISBN: 978-1633437166.

Entrada BibTeX:

```bibtex
@book{build-llms-from-scratch-book,
  author       = {Sebastian Raschka},
  title        = {Build A Large Language Model (From Scratch)},
  publisher    = {Manning},
  year         = {2024},
  isbn         = {978-1633437166},
  url          = {https://www.manning.com/books/build-a-large-language-model-from-scratch},
  github       = {https://github.com/rasbt/LLMs-from-scratch}
}

```
