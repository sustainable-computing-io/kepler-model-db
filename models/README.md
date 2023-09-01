# Power Models

Power models are stored with the following file structure.

```yaml
└── <version>
    ├── README.md
    └── nx12
        ├── preprocessed_data
        │   ├── *_data.csv # raw preprocess data (optional)
        │   └── preprocess_*.png # visualized preprocess data   
        └── <pipeline_name>
            ├── *_model_metadata.csv # summary of trained model 
            ├── metadata.json # pipeline metadata
            ├── <energy_source>/<output_type>/<feature_group>/* # model files
            └── train_arguments.json
```

- standard pipeline named by `std_<version>`
- preprocessed data are optional to upload

## Train server information

Machine ID|CPU Architecture|CPU model (optional)|#sockets (optional)|OS|Kernel version
---|---|---|---|---|---
