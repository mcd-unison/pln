---
title: Conceptos y modelos de aprendizaje profundo
subtitle: Material del curso (Curso PLN/MCD/UNISON)
layout: page
hero_image: https://github.com/mcd-unison/pln/raw/main/docs/img/data-science-banner.jpg
hero_darken: true
show_sidebar: false
---

## Presentaciones usadas en el curso

- [Introducción a los modelos secuenciales y celdas LSTM](https://www.github.com/mcd-unison/pln/blob/main/slides/pln-capitulo-2.pptx)

- [*Name-entity Recognition* (NER) con LSTM](https://www.github.com/mcd-unison/pln/blob/main/slides/NER-LSTM.pdf)

- [Embeddings from Language Models (ELMo)](http://hanj.cs.illinois.edu/cs512/slides-students2020/Elmo.pdf)

- [Redes Siamesas y *One shoot learning*](https://www.github.com/mcd-unison/pln/blob/main/slides/NN-siamesas.pdf)

- [El mecanismo de atención y traductores con LSTM](https://www.github.com/mcd-unison/pln/blob/main/slides/atencion-slides.pdf)

- [El modelo de transformadores (muy fea mis presentación pero no me alcanzó pa más el seso)](https://www.github.com/mcd-unison/pln/blob/main/slides/transformers.pdf)

- [Transfer learning y modelos preentrenados](https://www.github.com/mcd-unison/pln/blob/main/slides/transfer.pdf)

- [Tareas con secuencias largas](https://www.github.com/mcd-unison/pln/blob/main/slides/secuencias-largas.pdf)

- [LagChain: Get your LLM application from prototype to production](https://www.langchain.com), su [documentación](https://python.langchain.com/docs/get_started) y si [repositorio de GitHub](https://github.com/langchain-ai/langchain)

## Explicaciones gráficas

- [The Unreasonable Effectiveness of Recurrent Neural Networks (Karpathy, 2015)](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

- [Recurrent Neural Networks cheatsheet (Amidi y Amidi, 2019)](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)

- [Using Triplet Loss and Siamese Neural Networks to Train Catalog Item Embeddings (Ramachandran, 2021)](https://doordash.engineering/2021/09/08/using-twin-neural-networks-to-train-catalog-item-embeddings/)

- [The Illustrated Transformer (Alammar, 2018)](http://jalammar.github.io/illustrated-transformer/)

- [BERT 101 🤗 State Of The Art NLP Model Explained (Muller, 2022)](https://huggingface.co/blog/bert-101)

- [A Visual Guide to Using BERT for the First Time (Alammar, 2019)](http://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/)

- [The Illustrated GPT-2 (Visualizing Transformer Language Models) (Alammar, 2019)](http://jalammar.github.io/illustrated-gpt2/)

- [How GPT3 Works - Visualizations and Animations (Alammar, 2020)](http://jalammar.github.io/how-gpt3-works-visualizations-animations/)

- [Recent Advances in Language Model Fine-tuning (Ruder, 2021)](https://www.ruder.io/recent-advances-lm-fine-tuning/) 

- [Understanding Locality Sensitive Hashing(LSH): A Powerful Technique for Similarity Search (Joshi, 2023)](https://medium.com/@sarthakjoshi_9398/understanding-locality-sensitive-hashing-lsh-a-powerful-technique-for-similarity-search-a95b090bdc4a)
  
- [LSH Algorithm and Implementation (E2LSH)](https://www.mit.edu/~andoni/LSH/)


- [Intro to Large Language Models (Karpathy, 2023, youtube)](https://youtu.be/zjkBMFhNj_g?si=al3CCBwB5hqQ5kPy)

## Artículos seminales

- [Long Short-Term Memory (Hochreiter y Schmidhuber, 1997)](https://deeplearning.cs.cmu.edu/F23/document/readings/LSTM.pdf)

- [Understanding LSTM -- a tutorial into Long Short-Term Memory Recurrent Neural Networks (Staudemeyer y Morris, 2019)](https://arxiv.org/abs/1909.09586)

- [Neural Machine Translation by Jointly Learning to Align and Translate (Bhadanau et al, 2014)](https://arxiv.org/abs/1409.0473)

- [Attention Is All You Need (Vaswani et al, 2017)](https://arxiv.org/abs/1706.03762)

- [Deep contextualized word representations (Peters et al, 2018)](https://arxiv.org/pdf/1802.05365)

- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (Devlin et al, 2018)](https://arxiv.org/abs/1810.04805)

- [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer (Raffel et al, 2019)](https://arxiv.org/abs/1910.10683)

- [Reformer: The Efficient Transformer (Kitaev et al, 2020)](https://arxiv.org/abs/2001.04451)

- [Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity (Fedus et al, 2022)](https://arxiv.org/pdf/2101.03961.pdf)


## Sitios y herramientas interesantes

- La de base si estás en tensorflow: [*Keras*](https://keras.io)

- Para NLP, está [*Keras NLP*](https://keras.io/keras_nlp/), la cual es una librería que funciona en forma nativa con Tensorflow, JAX y/o pyTorch. En general ayuda a establecer un flujo de trabajo tanto de entrenamiento como de puesta en producción de procesos de NLP. Muy pensada para el uso y ajuste fino de modelos preentrenados.

- Si estás haciendo PLN con modelos profundos, no es posible vivir sin conocer a fondo [Hugging Face](https://huggingface.co). Es una compañía que mantiene un entorno de desarrollo abierto, una colección de modelos preentrenados, y una librería (la librería de transformadores mñas importante al momento), así como facilidades para poner los modelos en producción.

- Para recursos específicos en español, *Hugging Face* mantiene una rama en los países que hablamos español, [Somos NLP](https://somosnlp.org). Muy recomendable. Incluye una bolsa de trabajo (muy centrada en España por el momento, pero que esperamos crezca).
 
- La [Sociedad Española para el Procesamiento del Lenguage Natural (SEPLN)](http://www.sepln.org) es una de las organizaciones científicas en el área de informñatica más antiguas de España, y mantiene una revista desde 1983. Información interesante, acceso gratuito a la revista, congresos, hackatones. Todo muy español, pero con muchos lazos en Latinoamñerica y en espacial con México.


## Filosofía, sociedad, implicaciones éticas y sociales

- [Language models and linguistic theories beyond words](https://www.nature.com/articles/s42256-023-00703-8)

- [GPTs are GPTs: An Early Look at the Labor Market Impact Potential of Large Language Models](https://arxiv.org/abs/2303.10130)

- [Yann LeCun and Andrew Ng: Why the 6-month AI Pause is a Bad Idea (Video)](https://www.youtube.com/live/BY9KV8uCtj4?si=ZmGJWo6ERkLwQdRg) 

- Consideraciones éticas del uso de LLM en medicina:
  - [Attention is not all you need: the complicated case of ethically using large language models in healthcare and medicine](https://www.sciencedirect.com/science/article/pii/S2352396423000774)
  - [Ethics of large language models in medicine and medical
research](https://www.thelancet.com/journals/landig/article/PIIS2589-7500(23)00083-3/fulltext)

- [Generative Conversational AI And Academic Integrity: A Mixed Method Investigation To Understand The Ethical Use of LLM Chatbots In Higher Education](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4548263)

- [Student Use Cases for AI: Start by Sharing These Guidelines with Your Class](https://hbsp.harvard.edu/inspiring-minds/student-use-cases-for-ai)