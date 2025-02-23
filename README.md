# BIAS-2015-data
Datasets used by BIAS-2015

DEPRECATED: This repository is deprecated, please access all BIAS-2015 data files and supplementary files through our AWS bucket here

s3://bias-2015

preprocessing_data - All datasets used and all intermediate files generated during preprocessing

preprocessing_data/bias_2015_required_files - The preprocessing files that are required to run BIAS-2015, the results from preprocessing

validation_data - All datasets used and generated during validation

## Cloning This Repository

This repository uses [Git Large File Storage (Git LFS)](https://git-lfs.github.com/) to manage large files. To ensure that you can properly download and work with the repository, please follow these steps:

1. **Install Git LFS**: If you haven't already, you'll need to install Git LFS. You can install it via Homebrew on macOS, or follow the installation instructions for your operating system [here](https://git-lfs.github.com/).

    ```bash
    # On macOS, use Homebrew
    brew install git-lfs
    ```

2. **Initialize Git LFS**: After installing Git LFS, you'll need to initialize it in your Git environment. This is a one-time setup step.

    ```bash
    git lfs install
    ```

3. **Clone the Repository**: Now you can clone the repository as usual. Git LFS will automatically handle the downloading of large files.

    ```bash
    git clone https://github.com/bitscopic/BIAS-2015-data
    ```

4. **Verify LFS Installation**: After cloning, you can verify that the large files were downloaded correctly by listing the tracked files:

    ```bash
    git lfs ls-files
    ```

By following these steps, you'll ensure that all large files are correctly downloaded and that the repository works as intended.

