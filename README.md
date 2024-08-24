# IPML NLP Project: Attention-GAN Based Text-to-Image Synthesis

This project implements an Attention-GAN (AttnGAN) model for text-to-image synthesis, which generates images from textual descriptions. The project uses a combination of neural networks and attention mechanisms to produce high-quality images based on the input text.

## Project Structure

- **LICENSE**: Contains the licensing information for the project.
- **README.md**: Overview of the project and instructions on how to use it.
- **requirements.txt**: Lists all the Python packages and their versions required to run the project.

### Directories:
- **code/**: Contains all the scripts for running the project, including model definitions, training scripts, and utility functions.
- **docs/**: Contains the project report, presentations, and any additional documentation.

## Requirements

This project requires the following Python libraries, which can be installed using the `requirements.txt` file:

- torch (PyTorch)
- torchvision
- numpy
- matplotlib
- pyyaml
- nltk

Additionally, an NVIDIA GPU is required for training and generating images. It is recommended to use Google Colab with a subscription for GPU access.

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required Python packages using:

```bash
pip install -r requirements.txt
```

## Usage

1. To generate images from text, run the following command in your terminal or Jupyter notebook:

```bash
python code/main.py --cfg code/cfg/eval_bird.yml --gpu 0
```

This will generate images based on the bird dataset. You can modify the configuration file to use other datasets.

2. Review the generated images and results in the `results/` directory.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
