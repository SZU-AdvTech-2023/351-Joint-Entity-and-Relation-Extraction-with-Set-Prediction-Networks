##  模型训练
### Requirement:
```
Python: 3.7   
PyTorch: >= 1.5.0 
Transformers: 2.6.0
```

###  model train
* 注意：需将命令行中的BERT_DIR替换为实际存储BERT的目录！！！

```shell
python -m main --bert_directory BERT_DIR --num_generated_triples 15 --na_rel_coef 1 --max_grad_norm 1 --max_epoch 100 --max_span_length 10
```

###  or

```shell
python -m main --bert_directory BERT_DIR --num_generated_triples 15 --max_grad_norm 2.5 --na_rel_coef 0.25 --max_epoch 100 --max_span_length 10
```

