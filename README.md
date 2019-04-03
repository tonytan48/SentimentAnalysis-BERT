# SentimentAnalysis-BERT
This repo is developed from: https://github.com/huggingface/pytorch-pretrained-BERT

Benchmark Model could be run with the following code:
```shell
export GLUE_DIR=/SST-2
export TASK_NAME=SST-2

python run_classifier.py \
  --task_name $TASK_NAME \
  --do_train \
  --do_eval \
  --do_lower_case \
  --data_dir $GLUE_DIR/$TASK_NAME \
  --bert_model bert-base-uncased \
  --max_seq_length 128 \
  --train_batch_size 32 \
  --learning_rate 2e-5 \
  --num_train_epochs 3.0 \
  --output_dir /tmp/$TASK_NAME/
```
