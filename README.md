# Policy Generator Notebook

This repository contains a Jupyter Notebook that demonstrates the methodology for generating IDS-compliant policies as described in our conference paper. The notebook is organized into several sections:

- **Introduction & Setup**: Overview and required imports, including secure configuration for API keys.
- **Data Preprocessing**: Loading, cleaning, and preparing the dataset for policy generation.
- **Model & Policy Generation**: Implementation of the policy generation process via API requests with IDS ontology guidelines.
- **Results & Analysis**: Evaluation and visualization of generated policies.
- **Conclusion**: Summary and potential future work.

## Features

- **IDS-Compliant Policies**: Generates policies that adhere to the International Data Spaces (IDS) ontology.
- **Secure and Reproducible**: Sensitive information like API keys is securely handled via environment variables.
- **End-to-End Workflow**: From data loading and preprocessing to policy generation and analysis.
- **Easy Integration**: Designed for academic and professional use in research and conference presentations.

## Prerequisites

- **Python 3.7+**
- **Jupyter Notebook** or **JupyterLab**

### Required Python Libraries

- `numpy`
- `pandas`
- `matplotlib`
- `requests`
- `json`
- `re`

You can install these dependencies using pip:

```
pip install numpy pandas matplotlib requests
```

### Setup

1. Environment Variables:
Set your API keys securely. For example, in your terminal:
```
export AZURE_API_KEY=your_api_key_here
```

2.	Data Files:
Ensure your dataset is available at data/policy_data.csv or update the path in the notebook accordingly.

Running the Notebook
1. Launch Jupyter Notebook or JupyterLab.
2. Open the notebook file (main.ipynb).
3. Run the notebook cells sequentially to execute the workflow:
  3.1. Setup & Imports
  3.2. Data Preprocessing
  3.3. Model & Policy Generation
  3.4. Results & Analysis
  3.5. Conclusion


### Contributing

Contributions are welcome. Please adhere to the coding style and documentation guidelines when making improvements.

### License

This project is licensed under the MIT License. See the LICENSE file for details.

### Acknowledgements

This project is part of a conference paper effort and has been developed with contributions from multiple researchers. Special thanks to all contributors and reviewers for their valuable feedback.
