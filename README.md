# ComfyUI-Step1X-Edit

ComfyUI Custom Node for [Step1X-Edit](https://github.com/stepfun-ai/Step1X-Edit/). Noted this node may consume large VRAMs!

## Installation

1. Navigate to your ComfyUI's custom_nodes directory:
```bash
cd ComfyUI/custom_nodes
```

2. Clone this repository:
```bash
git clone https://github.com/Quank123WIP/ComfyUI-Step1X-Edit
```

3. Install requirements:
```bash
cd ComfyUI-Step1X-Edit
pip install -r requirements.txt
```

### Or Install via ComfyUI Manager

## Usage

Download the safetensors weight of the pretrained model from [here](https://huggingface.co/stepfun-ai/Step1X-Edit), and then place them in `models/Step1x-Edit` (both the vae and model itself).

Download the vision encoder(Qwen/Qwen2.5-VL-7B-Instruct) weight from [here], and place the whole folder inside `models/MLLM`.

## Citation

```bibtex
@article{liu2025step1x-edit,
      title={Step1X-Edit: A Practical Framework for General Image Editing}, 
      author={Shiyu Liu and Yucheng Han and Peng Xing and Fukun Yin and Rui Wang and Wei Cheng and Jiaqi Liao and Yingming Wang and Honghao Fu and Chunrui Han and Guopeng Li and Yuang Peng and Quan Sun and Jingwei Wu and Yan Cai and Zheng Ge and Ranchen Ming and Lei Xia and Xianfang Zeng and Yibo Zhu and Binxing Jiao and Xiangyu Zhang and Gang Yu and Daxin Jiang},
      journal={arXiv preprint arXiv:2504.17761},
      year={2025}
}
```

## Disclaimer

The results produced by this image editing model are entirely determined by user input and actions. The development team and this open-source project are not responsible for any outcomes or consequences arising from its use.

## License

MIT License