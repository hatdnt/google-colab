# 🎨 Wan Image Generation - Google Colab

![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

Welcome to the **Wan Image Generation** repository! This collection of Google Colab notebooks leverages the power of the Wan model to provide high-quality **Text-to-Image** and **Image-to-Image** generation capabilities, wrapped in an easy-to-use Gradio interface.

## 🚀 Key Features

*   **State-of-the-Art Generation**: Utilizes the **Wan 2.2** model for superior image and latent generation.
*   **Dual Interface**: Control generation via user-friendly **Gradio Web UI** or **Telegram Bot**.
*   **Flexible Modes**: Dedicated notebooks for both creating images from scratch and transforming existing images.

---

## 📂 Notebooks

### 1. Text-to-Image (T2I)
Generate stunning images from detailed text descriptions.

| Feature | Notebook | Link |
| :--- | :--- | :--- |
| **Text-to-Image** | `Wan2_2_T2I_jupyter_gradio.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hatdnt/Google-Colab/blob/main/Image/Wan2_2_T2I_jupyter_gradio.ipynb) |

**How to use:**
1.  Click the "Open in Colab" badge.
2.  Run the cells to install dependencies and load the model.
3.  Enter your prompt in the Gradio interface and click "Generate".

### 2. Image-to-Image (I2I)
Transform existing images into new creations based on text prompts.

| Feature | Notebook | Link |
| :--- | :--- | :--- |
| **Image-to-Image** | `Img2Img_Wan2_2_T2I_jupyter_gradio.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hatdnt/Google-Colab/blob/main/Image/Img2Img_Wan2_2_T2I_jupyter_gradio.ipynb) |

**How to use:**
1.  Click the "Open in Colab" badge.
2.  Upload your reference image in the interface.
3.  Adjust parameters and provide a prompt to guide the transformation.

---

## ⚙️ Configuration (Required)

To use the Telegram Bot features, you MUST configure a Bot Token:

1.  **Get a Token**: Open Telegram and chat with **[@BotFather](https://t.me/BotFather)**. Send the command `/newbot` to create a bot and receive your `HTTP API TOKEN`.
2.  **Set Token in Colab**:
    *   Open the desired notebook.
    *   Locate the cell defining `BOT_TOKEN` (usually near the end).
    *   Replace `"YOUR_BOT_TOKEN_HERE"` with your actual token.
    *   *Example*: `BOT_TOKEN = "123456789:ABCdefGhIJKlmNoPQRstuVWxyz"`

---

## 🛠️ Usage Tips

*   **First Run**: The first execution will download the **Wan 2.2 Model** (approx. several GB) from Hugging Face. Please be patient.
*   **Runtime Type**: Ensure you are using a GPU runtime in Google Colab (Runtime > Change runtime type > **T4 GPU** or better).
*   **Google Drive**: Mount Google Drive to save your generated outputs permanently.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/hatdnt/google-colab/issues).

---

*Note: Please replace `hatdnt` in the Colab links above with your actual GitHub username to ensure the badges work correctly.*

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
