# [NTIRE 2025 Challenge on Image Super-Resolution (x4)](https://cvlai.net/ntire/2025/) @ [CVPR 2025](https://cvpr.thecvf.com/)

## How to test the baseline model?

1. `git clone https://github.com/YanHuiGUO/Submission-for-NTIRE-2025-SR-x4-.git`
2. Select the model you would like to test from [`run.sh`](./run.sh)
    ```bash
    CUDA_VISIBLE_DEVICES=0 python test.py --test_dir DIV2K_test_LR_bicubic/X4 --save_dir NTIRE2025_ImageSR_x4/results --model_id 7
    ```
    - Be sure the change the directories `--data_dir` and `--save_dir`.
    - We provide one model (team07): team07_MicroSR. The code and pretrained model are provided.
    - The pretrained model can be downloaded with [link](https://drive.google.com/file/d/1onGAT8KDs56cODjF8AXgsFiD9YW9FS3x/view?usp=sharing) and please place it in the model_zoo folder.


## License and Acknowledgement
This repo is heavily built on the [SwinFIR code](https://github.com/Zdafeng/SwinFIR) and the [official template](https://github.com/zhengchen1999/NTIRE2025_ImageSR_x4). 

This code repository is release under [MIT License](LICENSE).

