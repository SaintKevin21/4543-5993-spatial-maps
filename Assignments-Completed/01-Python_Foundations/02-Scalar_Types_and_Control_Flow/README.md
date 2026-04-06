
[KevinKangethe__01_Scalar_Types.ipynb](https://github.com/user-attachments/files/26494205/KevinKangethe__01_Scalar_Types.ipynb)
{
  "cells": [
    {
      "cell_type": "markdown",
      "id": "c224876d",
      "metadata": {
        "id": "c224876d"
      },
      "source": [
        "# 📘 01 - Scalar Types\n",
        "\n",
        "Review and practice working with Python's basic scalar data types."
      ]
    },
    {
      "cell_type": "markdown",
      "id": "39c1942a",
      "metadata": {
        "id": "39c1942a"
      },
      "source": [
        "## ✅ Learning Goals\n",
        "- Recognize scalar types (`int`, `float`, `str`, `bool`)\n",
        "- Use the `type()` function to identify types\n",
        "- Use variables and assignment"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "id": "0cf15b63",
      "metadata": {
        "id": "0cf15b63"
      },
      "outputs": [],
      "source": [
        "# 🔧 Define some variables\n",
        "num = 42\n",
        "pi = 3.14159\n",
        "name = 'Python'\n",
        "is_cool = True"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "id": "7c8e8452",
      "metadata": {
        "id": "7c8e8452"
      },
      "outputs": [],
      "source": [
        "# 🔍 Check their types\n",
        "print(type(num))\n",
        "print(type(pi))\n",
        "print(type(name))\n",
        "print(type(is_cool))"
      ]
    },
    {
      "cell_type": "markdown",
      "id": "2c345a8b",
      "metadata": {
        "id": "2c345a8b"
      },
      "source": [
        "### ✏️ Your Turn\n",
        "Create your own variables of each type and print them."
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "id": "038b4f44",
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "038b4f44",
        "outputId": "8e67a184-747f-4030-f2e9-906c706e85b9"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "21\n",
            "98.6\n",
            "Dallas\n",
            "True\n"
          ]
        }
      ],
      "source": [
        "# Your code here\n",
        "age = 21\n",
        "temperature = 98.6\n",
        "city = \"Dallas\"\n",
        "is_student = True\n",
        "\n",
        "print(age)\n",
        "print(temperature)\n",
        "print(city)\n",
        "print(is_student)"
      ]
    },
    {
      "cell_type": "markdown",
      "id": "f02be606",
      "metadata": {
        "id": "f02be606"
      },
      "source": [
        "## ⚖️ Comparison Practice\n",
        "Use comparison operators to check values."
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "id": "9bf84dc7",
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "9bf84dc7",
        "outputId": "98ec3b8d-faa8-4142-cda4-fa0c0398ed5c"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "True\n",
            "False\n",
            "True\n"
          ]
        }
      ],
      "source": [
        "x = 10\n",
        "y = 5\n",
        "print(x > y)\n",
        "print(x == y)\n",
        "print(x != y)"
      ]
    },
    {
      "cell_type": "markdown",
      "id": "789b6f3d",
      "metadata": {
        "id": "789b6f3d"
      },
      "source": [
        "## 🧠 Quick Check\n",
        "What will the following print?\n",
        "```python\n",
        "print(3.0 == 3)\n",
        "```"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "\n",
        "\n",
        "True\n"
      ],
      "metadata": {
        "id": "QYb2WBh1-NTe"
      },
      "id": "QYb2WBh1-NTe"
    }
  ],
  "metadata": {
    "colab": {
      "provenance": []
    },
    "language_info": {
      "name": "python"
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    }
  },
  "nbformat": 4,
  "nbformat_minor": 5
}
