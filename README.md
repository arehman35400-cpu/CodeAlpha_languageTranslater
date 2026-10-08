# 🌐 Language Translator

A simple interactive language translation tool built in a Jupyter Notebook using **ipywidgets** and **deep-translator**. Choose a source language, a target language, type your text, and get the translation instantly.

## 📌 Project Overview

The translator provides a small widget-based interface inside the notebook. It validates the input, calls the Google Translate service through `deep-translator`, and shows the result along with a status message.

## ✨ Features

* Interactive dropdown menus for source and target languages
* Text input area and one-click **Translate** button
* Read-only output box for the translated text
* Status messages for empty text, missing language selection, and errors
* Supports 10 languages

## 🈯 Supported Languages

| Language | Code |
|----------|------|
| English  | `en` |
| Spanish  | `es` |
| French   | `fr` |
| German   | `de` |
| Chinese (Simplified) | `zh-CN` |
| Japanese | `ja` |
| Urdu     | `ur` |
| Arabic   | `ar` |
| Russian  | `ru` |
| Italian  | `it` |

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* ipywidgets
* IPython
* deep-translator

## ⚙️ Installation

```bash
pip install ipywidgets deep-translator
```

If the widgets do not appear in Jupyter Notebook, enable the extension:

```bash
jupyter nbextension enable --py widgetsnbextension
```

## ▶️ How to Use

1. Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.
2. Run the code cell.
3. Select the **Source Language** and **Target Language**.
4. Type your text in the input box.
5. Click **Translate** to see the result.

## 💬 Example

```text
Source Language: English
Target Language: French
Input:  Hello, how are you?
Result: Bonjour comment allez-vous?
Status: Done!
```

## ⚠️ Notes

* An active internet connection is required, since translation is done online.
* Very long texts may be rejected by the translation service.

## 🔮 Future Improvements

* Add more languages
* Add automatic source-language detection
* Add text-to-speech for the translated text
* Add a copy-to-clipboard button
* Build a web version (Streamlit / Flask)

## 👨‍💻 Author

Abdul Rehman Waheed
