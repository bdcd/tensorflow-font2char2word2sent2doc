# tensorflow-font2char2word2sent2doc

[![PyPI version](https://badge.fury.io/py/tensorflow-font2char2word2sent2doc.svg)](https://badge.fury.io/py/tensorflow-font2char2word2sent2doc)
[![Python versions](https://img.shields.io/pypi/pyversions/tensorflow-font2char2word2sent2doc.svg)](setup.py)
[![wercker status](https://app.wercker.com/status/1d697a9a04d1e9166dfa9705ff10bbe5/s/master "wercker status")](https://app.wercker.com/project/byKey/1d697a9a04d1e9166dfa9705ff10bbe5)
[![License](https://img.shields.io/badge/license-unlicense-lightgray.svg)](https://unlicense.org)

TensorFlow implementation of [Hierarchical Attention Networks for Document Classification](https://www.google.co.jp/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwiNxqa286zRAhUMqY8KHZYlCWEQFggjMAA&url=https%3A%2F%2Fwww.cs.cmu.edu%2F~diyiy%2Fdocs%2Fnaacl16.pdf&usg=AFQjCNFokKFJ1g7WQSDYkYEM82XwhGiDGw&sig2=iHJc5O86dNQrexisfSA7mw) with some extension.

# 소스 + 모듈 다운로드

## 맥 사용자 
homebrew 설치
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
python 3.6.x 설치
```bash
brew install python3
```
## 윈도우 사용자

파이썬3 버전 다운로드 & 설치 
https://www.python.org/ 


#

소스 + 파이썬 모듈 다운로드
```bash
git clone https://github.com/bdcd/tensorflow-font2char2word2sent2doc.git
cd tensorflow-font2char2word2sent2doc/
cd /usr/local/Cellar/python3/3.6.2/bin/
pip3 install --user --upgrade tensorflow
pip3 install --user --upgrade char2image
pip3 install --user --upgrade tensorflow-qnd
pip3 install --user --upgrade tensorflow-qndex
```

# pycharm IDE
pycharm - preference - project - project interpreter - python 3.6.2 선택 

# 실행

```bash
/Library/Frameworks/Python.framework/Versions/3.6/bin/python3.6 /Users/hkjang/project/tensorflow-font2char2word2sent2doc/examples/char2word2sent2doc/main.py
usage: main.py [-h] [--regularization_scale REGULARIZATION_SCALE]
               [--word_embedding_size WORD_EMBEDDING_SIZE]
               [--sentence_embedding_size SENTENCE_EMBEDDING_SIZE]
               [--document_embedding_size DOCUMENT_EMBEDDING_SIZE]
               [--context_vector_size CONTEXT_VECTOR_SIZE]
               [--char_embedding_size CHAR_EMBEDDING_SIZE] --num_classes
               NUM_CLASSES [--num_labels NUM_LABELS]
               [--hidden_layer_sizes HIDDEN_LAYER_SIZES]
               [--dropout_keep_prob DROPOUT_KEEP_PROB]
               [--word_length WORD_LENGTH]
               [--save_word_array_file SAVE_WORD_ARRAY_FILE] --char_file CHARS
               --word_file WORDS [--document_length DOCUMENT_LENGTH]
               [--sentence_length SENTENCE_LENGTH] [--output_dir OUTPUT_DIR]
               [--train_steps TRAIN_STEPS] [--eval_steps EVAL_STEPS]
               [--min_eval_frequency MIN_EVAL_FREQUENCY]
               [--num_cores NUM_CORES] [--log_device_placement]
               [--save_summary_steps SAVE_SUMMARY_STEPS]
               [--save_checkpoints_steps SAVE_CHECKPOINTS_STEPS]
               [--keep_checkpoint_max KEEP_CHECKPOINT_MAX]
               [--batch_size BATCH_SIZE]
               [--batch_queue_capacity BATCH_QUEUE_CAPACITY]
               [--num_batch_threads NUM_BATCH_THREADS] --train_file TRAIN_FILE
               [--filename_queue_capacity FILENAME_QUEUE_CAPACITY] --eval_file
               EVAL_FILE
main.py: error: the following arguments are required: --num_classes, --char_file, --word_file, --train_file, --eval_file

```


## License

[The Unlicense](https://unlicense.org)
