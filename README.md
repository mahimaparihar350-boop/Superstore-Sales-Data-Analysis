{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "lRnVzV5lOA12"
      },
      "outputs": [],
      "source": [
        "kagglehub>=0.2.0\n",
        "pandas>=1.5.0\n",
        "matplotlib>=3.5.0\n",
        "seaborn>=0.11.0"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Superstore Sales Data Analytics Project\n",
        "\n",
        "## Project Overview\n",
        "This project performs an Exploratory Data Analysis (EDA) on retail sales transactions using the official Kaggle dataset downloaded via `kagglehub`. The objective is to analyze customer shipping preferences and product category demand to extract actionable operational insights.\n",
        "\n",
        "## Dataset Details\n",
        "* **Dataset Source**: Kaggle (`ismatkhan121/supermarket-sales-dataset` / Superstore Dataset)\n",
        "* **Data Retrieval**: Programmatically fetched via `kagglehub.dataset_download()`\n",
        "* **Key Attributes**: Order ID, Order Date, Ship Mode, Customer ID, Segment, Region, Category, Sub-Category, Product Name, Sales.\n",
        "\n",
        "## Technologies Used\n",
        "* **Language**: Python 3.10+\n",
        "* **Library Dependencies**: `kagglehub`, `pandas`, `matplotlib`, `seaborn`\n",
        "* **Environment**: Google Colab / Jupyter Notebook\n",
        "\n",
        "## Setup & Execution Instructions\n",
        "1. Install dependencies:\n",
        "   ```bash\n",
        "   pip install -r requirements.txt"
      ],
      "metadata": {
        "id": "-uMhqc_fWyML"
      },
      "execution_count": null,
      "outputs": []
    }
  ]
}
