# AI Data Visualization Agent

## Overview

The **AI Data Visualization Agent** is a Streamlit web application designed to assist users in analyzing their datasets using AI. By uploading a CSV file, users can query the AI for insights, generate Python code for data analysis, and visualize the results interactively. This application leverages Together AI and E2B APIs to provide a seamless experience for generating data visualizations and running Python code.

---

## Features

- **Upload and Preview Datasets**: Upload CSV files and preview their content directly in the app.
- **Query AI for Analysis**: Ask natural language questions about your dataset, and the app will generate Python code to analyze it.
- **Interactive Visualizations**: View generated plots and figures directly within the app.
- **Supports Multiple Models**: Select from a range of models, such as Meta-Llama or DeepSeek.
- **Secure API Integration**: Safely enter your Together AI and E2B API keys.

---

## Prerequisites

### Requirements
- Python 3.9+
- API keys for:
  - Together AI ([Get Here](https://api.together.ai/signin))
  - E2B ([Get Here](https://e2b.dev/docs/legacy/getting-started/api-key))

### Dependencies
Install the required libraries:

```bash
pip install streamlit pandas pillow together e2b_code_interpreter
```

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-name/ai-data-visualization-agent.git
   cd ai-data-visualization-agent
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. **Enter API Keys**:
   - Provide your Together AI and E2B API keys in the sidebar.

2. **Upload Dataset**:
   - Click the "Choose a CSV file" button and upload your dataset.

3. **Ask a Question**:
   - Use the text area to input your query about the dataset.

4. **Analyze**:
   - Click the "Analyze" button to receive insights and visualizations.

5. **View Results**:
   - Explore generated visualizations and outputs directly in the app.

---

## Example

### Input:
- **Dataset**: A CSV file containing sales data.
- **Query**: "Can you compare the average sales across different categories?"

### Output:
- **AI Response**: A summary of the analysis.
- **Generated Visualization**: A bar chart comparing average sales.

---

## Model Options

Choose from the following models:
- **Meta-Llama 3.1 405B**
- **DeepSeek V3**
- **Qwen 2.5 7B**
- **Meta-Llama 3.3 70B**

---

## Known Issues

- Ensure API keys are valid and correctly entered.
- Large datasets may slow down analysis.

---

## Contributing

We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit changes: `git commit -m 'Add feature name'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---

## License

This project is licensed under the GNU License. See the `LICENSE` file for details.

---

## Acknowledgments

- **Streamlit**: For providing an interactive Python-based web app framework.
- **Together AI**: For LLM services.
- **E2B**: For enabling sandboxed Python code execution.

---

## Contact

For questions or feedback, please contact Esat Arslan at esat.arslan.dev@gmail.com

