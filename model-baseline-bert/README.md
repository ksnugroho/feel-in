Hyperparameter:
- NUM_OF_EPOCHS = 4
- BATCH_SIZE = 32
- LEARNING_RATE (AdamW) = 2e-5, β1 \beta _{1}

| pre-trained name                       | accuracy | val_accuracy | loss  | val_loss | runtime |
|----------------------------------------|----------|--------------|-------|----------|---------|
| indobenchmark/indobert-base-p1-uncased | 0.893    | 0.795        | 0.337 | 0.683    | 7m 56s  |
| indobenchmark/indobert-base-p2-uncased | 0.886    | 0.812        | 0.358 | 0.627    | 7m 22s  |
| indolem/indobert-base-uncased          | 0.730    | 0.837        | 0.890 | 0.540    | 6m 54s  |
| indolem/indobertweet-base-uncased      | 0.872    | 0.853        | 0.428 | 0.482    | 7m 2s   |

Training Report:

https://wandb.ai/indoemobert/baseline-bert/reports/Model-Baseline-Report-BERT-Fine-Tuning--VmlldzoyMzIzOTYx?accessToken=4vgoktwfk4rxwcd9akq4whiohgjl1bhzr7wwbi1hvu8xa0zamohh2x5f10ocr107
