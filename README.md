# REPOST-DL
캡스톤디자인 - Data/DL

## Install

```bash
git clone https://github.com/jeongseok5/REPOST-DL
cd REPOST-DL
pip install -r requirements.txt
```

## Example

```
python inference.py 
    -m BSRGANx2                # model
    -dir dir/for/inference     # directory for inference
    --disable_cuda             # Disable CUDA
```

You can change the ```-m``` to BSRGAN w/ scale factor==4. 
