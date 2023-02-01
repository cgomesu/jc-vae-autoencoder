# jc-vae-autoencoder

Notebooks that illustrate how to implement an AE and PCA using PyTorch and Scikit-Learn.

# how-to

1. Install `git`, `python3` `pip`, and `venv`:

    ```sh
    sudo apt update
    sudo apt install git python3 python3-pip
    pip3 install --upgrade pip
    pip3 install virtualenv
    ```

1. Clone this repo:

    ```sh
    git clone https://github.com/cgomesu/jc-vae-autoencoder.git
    cd jc-vae-autoencoder/
    ```

1. Create a virtual environment if none exists and activate it:

    ```sh
    python3 -m venv .venv/
    source .venv/bin/activate
    ```

1. Install required packages:

    ```sh
    pip3 install -r requirements.txt
    ```

1. Start jupyter:

    ```sh
    jupyter-lab
    ```

1. Open the `pca.pynb` and `ae.pynb` notebooks and follow the instructions there.

1. When you are done, shutdown `jupyter-lab` (ctrl+c) and deactive the virtual environment:

    ```sh
    deactivate
    ```

1. (Optional.) If you're completely done, you can now delete the virtual environment to save storage space:

    ```sh
    rm -rf .venv/
    ```
