# Neuromorph

Neuromorph is a project started by Sharbatanu CHATTERJEE to explore neuronal architectures of _Drosophila_ larvae using CATMAID's Python library.

## Getting Started

To get started with the project, clone the repository and create the conda environment:

```bash
git clone https://github.com/JovanicLab/neuromorph.git
cd neuromorph
conda env create -f environment.yml
conda activate neuromorph
```

Then launch JupyterLab or use Jupter notebooks on your IDE (like vscode).

## Adding an `api.txt` File

The project requires an `api.txt` file to store API keys or configuration details. Follow these steps to add the file:

1. Create a new file named `api.txt` in the root directory of the project.
2. Add your API keys or configuration details to the file, without spaces and quotes, as follows.
    ```
    api_token=YOUR_TOKEN
    http_user=YOUR_USERNAME
    http_password=YOUR_PASSWORD
    server=YOUR_SERVER
    ```
3. **Ensure the file is not included in version control by adding it to `.gitignore`.**

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).