# Environment Setup 

- Follow the environment setup instructions on https://github.com/StanfordASL/Trajectron-plus-plus

- Add the current directorty to PYTHONPATH

# Data Preparation

Modify the "__main__" function in `process_data.py` such that `data_path` points to the nuscenes dataset, `output_path` points to the directory where the processed data pickle files are stored. Then run `python process_data.py`

# Training And Evaluation
Training and evaluation code are in the trajectron folder. Instructions are the same as https://github.com/StanfordASL/Trajectron-plus-plus
