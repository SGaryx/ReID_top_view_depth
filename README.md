# Person Re-identification Project from Top-View Camera using TVPR2 Dataset

## Project Description

This project aims to develop a person re-identification system from a top-view camera using depth files from the TVPR2 dataset. The goal is to leverage this data to create a robust model capable of recognizing individuals in different video sequences.

## Notebooks

### 1. Process_Database.ipynb

The \`Process_Database.ipynb\` notebook is dedicated to cleaning the data from the TVPR2 dataset. It includes necessary steps for preprocessing images, handling annotations, and ensuring the quality of data used for model training.

### 2. Process_Sequence_Normalization.ipynb

In the \`Process_Sequence_Normalization.ipynb\` notebook, you'll find processes for normalizing sequences. This includes normalizing depth values and other transformations needed to prepare data before introducing it to the model.

### 3. Graph_Creation_Process.ipynb

The \`Graph_Creation_Process.ipynb\` notebook is specially designed for creating graphs from each image. These graphs are used to train a Graph Convolutional Network (GCN) to enhance re-identification performance.

## How to Use this Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/project-name.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks in the specified order above.

## Contributing

If you want to contribute to the improvement of this project, please follow these steps:

1. Fork the project.
2. Create a branch for your feature (\`git checkout -b feature/add-new-feature\`).
3. Commit your changes (\`git commit -m 'Add a new feature'\`).
4. Push the branch (\`git push origin feature/add-new-feature\`).
5. Open a Pull Request.

## Authors

- [Simon GARY]([link_to_your_github_profile](https://github.com/SGaryx)) - Lead Developer
- [Ombeline MOINEAU]([link_to_your_github_profile](https://github.com/ombelinemoineau)) - Lead Developer

## License

This project is licensed under the [MIT License](LICENSE).
