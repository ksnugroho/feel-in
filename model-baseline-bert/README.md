# Result 

## Hyperparameter
- NUM_OF_EPOCHS = 4
- BATCH_SIZE = 32
- LEARNING_RATE (AdamW) = 2e-5, $\beta_{1}$ = 0.8,  $\beta_{2}$ = 0.9, $L2$ = 0.0001

## Summary
| pre-trained model                       | accuracy | val_accuracy | loss  | val_loss | runtime |
|----------------------------------------|----------|--------------|-------|----------|---------|
| indobenchmark/indobert-base-p1-uncased | 0.893    | 0.795        | 0.337 | 0.683    | 7m 56s  |
| indobenchmark/indobert-base-p2-uncased | 0.886    | 0.812        | 0.358 | 0.627    | 7m 22s  |
| indolem/indobert-base-uncased          | 0.730    | 0.837        | 0.890 | 0.540    | 6m 54s  |
| indolem/indobertweet-base-uncased      | 0.872    | 0.853        | 0.428 | 0.482    | 7m 2s   |
| bert-based-uncased                     | 0.778    | 0.784        | 0.772 | 0.707    | 5m 50s  |
| malay-bert-cased                       | 0.872    | 0.812        | 0.407 | 0.626    | 6m 54s  |

## References
<a id="1">[1]</a> 
J. Devlin, M.-W. Chang, K. Lee, and K. Toutanova, “BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding,” arXiv.org, 2018, doi: [10.48550/arXiv.1810.04805](https://arxiv.org/abs/1810.04805).<br>
<a id="2">[2]</a>
F. Koto, A. Rahimi, J. H. Lau, and T. Baldwin, “IndoLEM and IndoBERT: A Benchmark Dataset and Pre-trained Language Model for Indonesian NLP,” arXiv.org, 2020, doi: 10.48550/arXiv.2011.00677.
‌
## Best Model Metric
![alt text](https://raw.githubusercontent.com/ksnugroho/feel-in/main/assets/best-baseline-model-bert-metric.jpg)

## Training Report
https://wandb.ai/indoemobert/baseline-bert/reports/Model-Baseline-Report-BERT-Fine-Tuning--VmlldzoyMzIzOTYx?accessToken=4vgoktwfk4rxwcd9akq4whiohgjl1bhzr7wwbi1hvu8xa0zamohh2x5f10ocr107
