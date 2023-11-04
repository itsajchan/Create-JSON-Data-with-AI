# 📀 Create JSON Objects with AI

This repository provides a comprehensive Jupyter notebook demonstrating the journey from JSON object generation to image synthesis. In this notebook, you'll get hands-on with:

1. **Generating JSON Data**: Using the OpenAI Chat Completion API, you can generate data in the form of JSON objects defined by you. This notebook creates hotel objects.
2. **Storing in Weaviate Vector Database**: Once the data is generated, it's stored in a Weaviate vector database for advanced search and analysis.
3. **Generative Search and Retrieval Augmented Generation (RAG)**: Dive deep into generative searches, leveraging RAG to provide contextual and enhanced results from the vector database.
4. **Image Synthesis with Diffusion Model**: Extracting the relevant details from the JSON objects, we'll paint a visual story by generating images using a state-of-the-art diffusion model.
5. **Migrating to Weaviate Cloud Services**: Finally, ensure that your data is safe and accessible in the cloud by transferring it from the local Embedded Weaviate instance to the more scalable Weaviate Cloud Services.

## ✅ Getting Started

### 🛠️ Prerequisites

- Python 3.x
- Jupyter Notebook (Recommended: Use Jupyter Lab for a better experience)
- OpenAI account 
- Replicate account - Not needed to start
- A Weaviate Cloud Services account (for data migration) - Not needed to start

### 👩‍💻 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/itsajchan/Create-JSON-Data-with-AI.git
   cd create-json-data-with-ai
   ```

2. **Install Required Libraries**

   Using pip:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

Navigate to the directory where you cloned the repo, and you should find the notebook ready to be run.

## 🚀 Usage

Go through each cell in the Jupyter notebook, ensuring that you follow the instructions and comments provided. This ensures a smooth and educative experience.

## 💖 Open Source Contribution

Your contributions are always welcome! Feel free to contribute ideas, feedback, or create issues and bug reports if you find any! Visit our [Weaviate Community Forum](https://forum.weaviate.io/) if you need any help!


## 🪪 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🙏 Acknowledgments

- Thanks to OpenAI for the Chat Completion API, which powers data generation and vectorization.
- Weaviate for their incredible vector database and cloud services, enabling advanced search capabilities and cloud storage.
- All researchers and developers behind the diffusion model that aids in image synthesis.
- The incredible team at Weaviate for making all of this possible.

---

We hope you enjoy this notebook from data generation to visualization and storage. Your feedback and contributions are always appreciated!