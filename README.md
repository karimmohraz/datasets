# datasets
ML datasets

## CNN Daily News
shuffled tfrecords files
```
total_num_examples=311971,
    splits={
        'test': 11490,
        'train': 287113,
        'validation': 13368,
    }
```
``` tfds.load('cnn_dailymail', split='test', shuffle_files=True, with_info=True, download=True, data_dir='~/Downloads/cnn/') ```
