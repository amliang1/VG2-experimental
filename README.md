# Original Repository & Credits

- I want to give full credits to the entire team of DeepSeek!
- Please refer to the original repository: [DeepSeek-VL2](https://github.com/deepseek-ai/DeepSeek-VL2)

# Modified Version

This modified version allows you to run DeepSeek-VL2 on Google Colab for free.

## Getting Started

Follow these steps to get started with the modified version on Google Colab:

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/).
2. **Clone the Repository**: Use the following command to clone the repository in a Colab notebook:
  ```python
  !git clone https://github.com/shobhitag11/DeepSeek-VL2-Run-On-Google-Colab.git
  ```
3. **Install colab-xterm**: This allows running terminal commands inside Google colab.
```sh
!pip install colab-xterm
```
4. **Create a new cell**: Run the following commands.
```sh
%load_ext colabxterm
```
```sh
%xterm
```
5. **Navigate to the Directory**: Now, inside terminal, move to the working directory to the cloned repository:
  ```python
  %cd DeepSeek-VL2-Run-On-Google-Colab
  ```
6. **Install Dependencies**: Install the required dependencies:
  ```python
  pip install -r requirements.txt
  ```
7. **Run the Application**: Execute the main script to start the application:
  ```python
  python web_demo.py
  ```

## Additional Resources

- **Documentation**: Refer to the [Medium Article](https://iamshobhitagarwal.medium.com/deepseek-vl2-the-tiny-ai-model-thats-changing-visual-understanding-forever-b64966ff68a9) for detailed information.
- **Issues**: Report any issues or bugs [here](https://github.com/deepseek-ai/DeepSeek-VL2/issues).


Happy coding!
