

# Post OCR Correction Using Glyph Embedding

## Overview
This project focuses on post Optical Character Recognition (OCR) correction using glyph embedding techniques.

## Project Structure
- **notebooks/**: Contains Jupyter notebooks for experiments and analysis.
- **data/**: Directory for storing datasets.
- **models/**: Directory for saving trained models.
- **scripts/**: Helper scripts for preprocessing and evaluation.
  **🚀 Exciting Breakthrough in OCR Technology! 🚀**  

I recently came across the groundbreaking book *"Enhancing OCR Performance through Post-OCR Models: Adopting Glyph Embedding for Improved Correction"* by Yung-Hsin Chen and Yuli Zhou, and I couldn’t wait to share its insights with you all!  

This research dives deep into the limitations of traditional OCR (Optical Character Recognition) models and introduces a novel approach to overcome them. By leveraging **post-OCR correction models** and incorporating **glyph embedding techniques**, the authors demonstrate how visual characteristics of characters can be captured to significantly improve OCR accuracy.  

Here’s what makes this work stand out:  
- **Innovative Use of Glyph Embedding**: The authors utilize CharBERT and a unique embedding technique to enhance OCR outputs, enabling the model to correct individual words with remarkable precision.  
- **Robust Datasets**: The study employs the ICDAR 2013 and ICDAR 2023 datasets, which include diverse document images with printed and handwritten text, as well as challenging scenarios like degraded text and complex layouts.  
- **Superior Performance**: The results show that post-OCR correction, combined with glyph embedding, outperforms state-of-the-art methods, especially in handling intricate documents and low-quality images.  

This research is a game-changer for industries relying on OCR technology, from document processing to historical text preservation. It’s a must-read for anyone interested in AI, computer vision, or natural language processing!  

📖 **Learn more**: Check out the full paper on [arXiv](https://arxiv.org/abs/2308.15262) or explore the GitHub repository for implementation details.  

---

**🚀 Excited to Share My Latest Work on Post-OCR Correction Using Glyph Embeddings! 🔍✨**  

Inspired by this groundbreaking research, I recently trained multiple models for post-OCR correction, integrating **glyph embeddings**—a cutting-edge technique that enhances text recognition by incorporating visual character features. One of the top-performing models was:  

🔹 **Model 2**  
📌 **Encoder**: CNN for CharBERT + CNN for MyEmbedding (Glyph Embeddings)  
📌 **Decoder**: Transformer decoder (best performance)  

📊 **Results**:  
🔹 Train Loss: 1.8702 | Val Loss: 0.5987  
🔹 Train WER: 0.4040 | Val WER: 0.1762  
🔹 Train CER: 0.2916 | Val CER: 0.0986  
![image](https://github.com/user-attachments/assets/44667f16-a573-4c67-928f-2e7807088381)

These results highlight the power of glyph embeddings in significantly improving OCR correction accuracy!  

A huge thank you to **Yung-Hsin Chen** for her inspiring work, *"Enhancing OCR Performance through Post-OCR Models: Adopting Glyph Embedding for Improved Correction."* Your research played a pivotal role in shaping this project! 🙌  

📖 **Check out the mini-book and notebook on GitHub** for more details and implementation insights. Stay tuned for more updates as I continue to explore the potential of this approach! 🚀  

---

#OCR #AI #ComputerVision #Innovation #PostOCR #GlyphEmbedding #MachineLearning #TechTrends #DeepLearning

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/malekzitouni/Post_OCR-Correction-Using-Glyph-Embedding.git
   ```
2. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter notebooks in the `notebooks/` directory to explore the experiments.
2. Use the scripts in the `scripts/` directory for preprocessing and evaluation.

## Contributing
Feel free to submit issues or pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.
```

You can create this README file in your repository and commit it. To do this:
1. Create a new file named `README.md` in the root directory of your repository.
2. Copy and paste the above content into the `README.md` file.
3. Commit and push the changes to your repository.



Let’s discuss! How do you see glyph embeddings and post-OCR correction transforming industries like document processing, historical text preservation, or even AI-driven transcription services? Share your thoughts below! 👇  
