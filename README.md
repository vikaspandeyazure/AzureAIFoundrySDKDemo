This repository is a replica of the steps mentioned in https://learn.microsoft.com/en-us/azure/ai-foundry/tutorials/copilot-sdk-create-resources?tabs=windows


# AzureAIFoundrySDKDemo

This repository contains a demo project for the Azure AI Foundry SDK. The project demonstrates how to create and manage AI resources using the SDK.

## Project Overview

The Azure AI Foundry SDK Demo project is designed to help users understand how to use the Azure AI Foundry SDK to create and manage AI resources. The project includes several scripts and notebooks that guide users through the process of setting up and using the SDK.

## Getting Started

To get started with this project, follow the steps below:

### Prerequisites

1. **Azure Subscription**: You need an Azure subscription to create and manage resources.
2. **Python Environment**: Ensure you have Python installed on your machine. It's recommended to use a virtual environment.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vikaspandeyazure/AzureAIFoundrySDKDemo.git
    cd AzureAIFoundrySDKDemo
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

### Project Setup

Follow the steps outlined in the [Azure AI Foundry SDK Tutorial](https://learn.microsoft.coms/copilot-sdk-create-resources?tabs=windows to set up your project:

1. **Step 1: Create an Azure AI Foundry Resource**:
    - Navigate to the Azure portal and create an Azure AI Foundry resource.
    - Note down the resource details such as the resource name, subscription ID, and resource group.

2. **Step 2: Configure the SDK**:
    - Update the `config.py` file with your Azure AI Foundry resource details.
    - Ensure that your environment variables are set up correctly.

3. **Step 3: Run the Demo Scripts**:
    - Use the provided Jupyter notebook `RAGChatDemo.ipynb` to interact with the AI Foundry SDK.
    - Run the scripts such as `create_search_index.py`, `get_product_documents.py`, and `evaluate.py` to see the SDK in action.

## Usage

The project includes several scripts and a Jupyter notebook to demonstrate the capabilities of the Azure AI Foundry SDK. Here are some key files:

- `RAGChatDemo.ipynb`: A Jupyter notebook to interact with the AI Foundry SDK.
- `create_search_index.py`: Script to create a search index.
- `get_product_documents.py`: Script to retrieve product documents.
- `evaluate.py`: Script to evaluate the AI model.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

Special thanks to the Azure AI Foundry team for their support and guidance.

## Contact

For any questions or issues, please open an issue in the repository or contact the repository owner.
