# Transformers
Este proyecto demuestra cómo utilizar la biblioteca transformers de Hugging Face para realizar inferencias. El modelo que se utiliza es [distilbert-base-uncased-finetuned-sst-2-english] (https://huggingface.co/distilbert/distilbert-base-uncased-finetuned-sst-2-english). Esta versión de DistilBERT está especialmente afinada en un conjunto de datos de análisis de sentimientos (Stanford Sentiment Treebank, versión 2), lo que la hace ideal para nuestras necesidades de clasificación de sentimientos en textos en inglés.

**Install the dependencies**

Create the virtual environment and install the dependencies:

```
python -m venv .venv
source .venv/bin/activate
.venv/bin/pip install -r requirements.txt
```
