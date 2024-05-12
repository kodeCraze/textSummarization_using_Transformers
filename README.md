# TextSummarization_using_Transformers
![image](https://github.com/kodeCraze/textSummarization_using_Transformers/assets/146913161/8b8e1a12-2484-4e2e-b41b-88cf1bf326c7)
# 📝 Text Summarization with DistilBART
This project demonstrates text summarization using the DistilBART model from Hugging Face Transformers, integrated with Gradio for a user-friendly interface.

## 🚀 Overview

The application allows users to input text and obtain a concise summary using the DistilBART-CNN-12-6 model. The summarization model is fine-tuned and accessible through the Hugging Face Transformers library.

## 💻 Usage

To run the text summarization interface locally, follow these steps:

1. Install the required dependencies using `pip`:
    ```bash
    pip install -r requirements.txt
    ```

2. Launch the Gradio interface:
    ```bash
    python app.py
    ```

3. Access the interface in your web browser at `http://localhost:7860`.

## 📋 Requirements

Ensure you have the following libraries installed (specified in `requirements.txt`):

- `transformers>=4.36.2`
- `diffusers>=0.25.0`
- `ctransformers[cuda]>=0.2.24`
- `Pillow>=9.3.0`
- `gradio`
- `streamlit>=1.29.0`
- `accelerate>=0.25.0`
- `pypdf`
- `peft>=0.6.0`

## 🏁 Getting Started

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. Navigate to the project directory:
    ```bash
    cd your-repo
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    python app.py
    ```
Deployed @  URL : https://huggingface.co/spaces/I-Am-SnowFlake/text-summarizer101
## 🙌 Acknowledgments

- This project uses the DistilBART-CNN-12-6 model from Hugging Face Transformers.
- Gradio is utilized for creating the interactive text summarization interface.

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).
