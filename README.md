# Neurons

This repository contains implementations of various neuron models, ranging from simple to complex, all built from first principles. The goal is to provide a resource for understanding the progressive complexity of computational neuroscience models.


## Repository Structure

The repository is organized into two main sections:

### 1. Point Neurons
Single-compartment models where the entire neuron is treated as a point in space.
- Integrate-and-Fire Model
- Leaky Integrate-and-Fire Model
- Exponential Integrate-and-Fire Model
- Adaptive Exponential Integrate-and-Fire Model
- Izhikevich Model
- Hodgkin-Huxley Model

### 2. Multi-Compartment Neurons
Models that divide neurons into multiple compartments to capture spatial complexity.
- Cable Theory Models
- Simplified Dendritic Models
- Full Morphological Models
- Detailed Biophysical Models with NEURON

## Contents

Each Jupyter notebook includes:
- **Description**: Theoretical background of the model
- **Mathematics**: Governing equations and numerical methods
- **Biophysical Relevance**: How the model relates to actual neuronal properties
- **Applications**: Real-world usage in computational neuroscience 
- **Implementation**: Clear, well-commented code
- **Visualization**: Dynamic plots and interactive components

## Prerequisites

- Basic understanding of neuroscience concepts
- Familiarity with differential equations
- Python programming experience

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/Neurons.git
cd Neurons
```

2. Create and activate the conda environment:
```bash
conda env create -f neurons_environment.yml
conda activate neurons_env
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Usage

1. Navigate to either the `point-neurons` or `multi-compartment-neurons` directory
2. Open the notebook of interest
3. Execute the cells sequentially to understand the progressive build-up of the model
4. Experiment with parameters to observe different neuronal behaviors

## Environment

The provided `neurons_environment.yml` file contains all necessary dependencies including:
- Python 3.9+
- NumPy
- Matplotlib
- NEURON simulator (for detailed compartmental models)

## References and Further Reading

- Gerstner, W., & Kistler, W. M. (2002). Spiking Neuron Models: Single Neurons, Populations, Plasticity.
- Dayan, P., & Abbott, L. F. (2001). Theoretical Neuroscience: Computational and Mathematical Modeling of Neural Systems.
- Carnevale, N. T., & Hines, M. L. (2006). The NEURON Book.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.