# Translation of texts with the Transformers (HuggingFace) library and Gradio webapp

In this repo, we use HuggingFace's transformers library to translate text.


**Libraries and installations**

The libraries that are used in this repo are reported in the "environment.yml" file.

To install the libraries, execute the following command in Anaconda Prompt:

conda env create -f environment.yml

After the libraries are installed, execute in Anaconda Prompt:

conda activate translation_conda_env

python -m ipykernel install --user --name=translation_conda_env

The latter command is used to install the environment as a kernel in Jupyter notebooks.

**Translation of texts with the Transformers library and Gradio webapp**

The code for the translation between languages, and the code for the Gradio app, are reported in the repo's jupyter notebook.
