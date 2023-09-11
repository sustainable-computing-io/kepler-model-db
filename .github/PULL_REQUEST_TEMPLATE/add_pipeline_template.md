### What kepler-model-server version did you use?



### Training pipeline description (skip if using the defaults for the version you provided above)
- **Extractor:** 
- **Isolator:** 
- **Trainers:**
    - <!--list all-->
- **Workload information:**
    - <!--see example: https://github.com/sustainable-computing-io/kepler-model-db/blob/main/models/v0.6/README.md#workload-information -->

### Checklist
- [ ] has machine information in models/README.md and has link to CPU model if provided
- [ ] pipeline folder contains all of the following:
  - [ ] pipeline metadata (metadata.json)
  - [ ] train arguments (train_arguments.json)
  - [ ] model metadata summary files (xxx_model_metadata.csv)
  - [ ] visualized preprocess data in preprocessed_data
  - [ ] all models listed in model metadata summary files in the structure //
- [ ] has training information in models//README.md and matches the value in pipeline metadata
- [ ] has pipeline description if not equal to defaults for std_v
- [ ] has train arguments match pipeline description
- [ ] verified account matches publisher in pipeline metadata
