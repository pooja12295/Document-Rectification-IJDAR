## Inference 
1. Put the pretrained model in `$ROOT/model_pretrained/`.
2. Put the distorted images in `$ROOT/distorted/`.
3. The rectified images are saved in `$ROOT/rectified_output/` by default.
    ```
    python inference.py

    python inference.py --ill_rec True
    ```
