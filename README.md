# InfluenceCL + ELI

```shell
pip3 install -r requirements.txt
```

## Quick Start

Train and evaluate models `utils/main.py`: 
```shell
python3 utils/main.py --model iceli --load_best_args --dataset seq-miniimg --buffer_size 500
```

implementation is based on [Mammoth](https://github.com/aimagelab/mammoth). We also refer to [bilevel_coresets](https://github.com/zalanborsos/bilevel_coresets) and [Example_Influence_CL](https://github.com/SSSunQing/Example_Influence_CL).
