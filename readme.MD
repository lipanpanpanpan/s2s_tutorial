**This is a playground for sequence to sequence learning with Pytorch.**
**Still in progress...**
For bytecup code, please checkout to branch "byte_cup_min", which is a project for abstractive summarisation.

Quick start:
The default dataset is a self-copy toy dataset. For other default configs, see s2s_tutorial/s2s_config.py

```
cd s2s_tutorial
python run_train_val.py
python run_test.py
```

You can add your experiments by modifying s2s_tutorial/exp_config.py. For the english-french translation task, which is exp1, just run the code below. 

```
cd s2s_tutorial
python run_train_val.py --e exp1
python run_test.py --e exp1
```
