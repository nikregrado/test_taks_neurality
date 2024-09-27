# Neureality Test Task for ML Engineer Position

All code is stored in a Colab notebook, which is also posted in this repository. You can access the notebook via this link: [Colab Notebook](https://colab.research.google.com/drive/1In7U2QfeN5idq_fh5zDGUaalnfOjr_dD?usp=sharing)

The code is based on the latest available versions of PyTorch and torchvision in the Colab environment.

## Steps to Recreate the Experiment

To recreate the experiment, you must perform the following steps:

1. **Clone this repository.**
2. **Upload the repository to your Google Drive folder named `neureality_test_task`.**
3. **Upload the Colab notebook to the same folder.**
4. **Run the notebook.**

## Contents

- **Output Images:**
  - In the folders `output_images_*`, you can find the results of the inference on CPU and GPU.

- **Performance Logs:**
  - In the files `performance_log_*`, you can find detailed logs of each step, starting from data loading and ending with data saving, including all major layers' time computation.

## Model Choice Justification

The model chosen was **Faster R-CNN** because:

1. **Availability in PyTorch:**
   - It is available in PyTorch in a pre-trained way without the need for additional packages.

2. **Ease of Weight Loading:**
   - Weights can be easily downloaded via PyTorch.

3. **Complex Architecture:**
   - It is not a fully sequential network, making it better to demonstrate profiling than models like YOLO or SSD.


## Notes

1. **Colab Support**
    - The code is designed to run in the Google Colab environment with GPU support.

2.  **Check the Runtime**
    - Ensure that your Colab runtime is set to use the GPU by selecting Runtime > Change runtime type > GPU.

