# ChatterSculpt

ChatterSculpt is an AI-powered creative generation project exploring text-to-image synthesis, image-to-3D/object reconstruction, and evaluation of AI-generated visuals. **Tech Stack:** Python, PyTorch, Hugging Face Diffusers, Transformers, Accelerate, NumPy, SciPy, Pillow, scikit-image, Jupyter Notebook, and Google Colab.

## Features

- **Text-to-Image Generation** — Generate images from natural language descriptions using diffusion-based generative models.
- **Image-to-3D/Object Reconstruction** — Explore techniques for reconstructing 3D representations of objects from input images.
- **Image Generation Evaluation** — Experiment with metrics and approaches to evaluate the quality of AI-generated images.
- **Deep Learning Experiments** — Implement and explore AI models using Python and deep learning frameworks.

## Project Structure

```text
ChatterSculpt/
│
├── Text_to_Image.ipynb
├── Image_to_Object.ipynb
├── Text_to_Image_Metrics.ipynb
└── README.md
```

### Notebooks

| Notebook | Description |
|---|---|
| `Text_to_Image.ipynb` | Experiments with generating images from text prompts using generative AI models. |
| `Image_to_Object.ipynb` | Explores image-based object reconstruction and 3D representation techniques. |
| `Text_to_Image_Metrics.ipynb` | Experiments with evaluating and analyzing text-to-image generation results. |

## Tech Stack

- **Programming Language:** Python
- **Deep Learning:** PyTorch
- **Generative AI:** Diffusers
- **Machine Learning Models:** Hugging Face Transformers
- **Model Acceleration:** Accelerate
- **Numerical Computing:** NumPy, SciPy
- **Image Processing:** Pillow, scikit-image
- **Development Environment:** Jupyter Notebook / Google Colab
- **Model Hub:** Hugging Face

## Getting Started

### Prerequisites

- Python 3.9+
- Jupyter Notebook or Google Colab
- GPU recommended for deep learning and image generation workloads

### Installation

Clone the repository:

```bash
git clone https://github.com/Kavish718/ChatterSculpt.git
cd ChatterSculpt
```

Install the core dependencies:

```bash
pip install torch torchvision
pip install diffusers transformers accelerate
pip install numpy scipy pillow scikit-image ftfy
pip install jupyter
```

### Running the Project

1. Open the repository in Jupyter Notebook or Google Colab.
2. Select the notebook corresponding to the experiment you want to run.
3. Install any notebook-specific dependencies.
4. Run the cells sequentially.
5. Follow the notebook instructions to generate images, process inputs, or evaluate outputs.

> **Note:** Some experiments may require a GPU, pretrained model downloads, datasets, or additional configuration.

## Project Goals

ChatterSculpt explores how artificial intelligence can bridge language, images, and 3D representations.

The project aims to investigate:

- How natural language prompts can be transformed into visual content.
- How computer vision techniques can extract object representations from images.
- How generated images can be evaluated for quality and relevance.
- The practical applications of generative AI in creative workflows.

## Future Improvements

- Build an interactive web interface for image generation.
- Integrate text-to-image and image-to-3D workflows into a unified pipeline.
- Add prompt history and image download functionality.
- Improve image evaluation and comparison metrics.
- Optimize inference performance and GPU utilization.
- Deploy the project as a web application.

## Author

**Kavish**

GitHub: [@Kavish718](https://github.com/Kavish718)

## License

Add a license to the repository if you intend to make the project open-source for reuse and contributions.
