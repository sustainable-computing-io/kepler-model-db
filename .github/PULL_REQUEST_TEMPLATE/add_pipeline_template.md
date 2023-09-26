*** The uploaded model must be trained and exported by the provided script in [model_training](https://github.com/sustainable-computing-io/kepler-model-server/tree/main/model_training). *** 

```
Notation: 

  [version]: kepler-model-server version (current: v0.6)
  [machine]: machine id defined when running `./script.sh export`
  [pipeline]: trained pipeline name (default: std_v0.6)
```
---

## Please confirm the following checklist for any applicable item.

- [ ] rename PR by the following format:

  ```
  models ([version] [machine] [pipeline])
  ```

### New training machine
- [ ] add machine information in `models/README.md` with a link to CPU model if provided (manual)
- [ ] has machine entry added in `models/[version]/README.md` (auto)
- [ ] add tag `new-machine` to the PR

### New pipeline
- [ ] has the pipeline information generated in `models/[version]/.doc` (auto)
- [ ] fill description in the generated page. (manual)
- [ ] add tag `new-pipeline` to the PR

### Existing training machine
- [ ] remove existing machine entry in `models/[version]/README.md` (manual)

### File checklist (auto)
- [ ] pipeline metadata (`metadata.json`)
- [ ] train arguments (`train_arguments.json`)
- [ ] model metadata summary files (`xxx_model_metadata.csv`)

### Common checklist
- [ ] has result page generated in  `models/[version]/[machine]/README.md` (auto)
- [ ] all links in result page is valid 
- [ ] verified account of PR committer matches publisher
- [ ] no change on other files except the above mentioned document and trained pipeline files in `models/[version]/[machine]`

---
## Please provide visualized results of error summary
generated error summary image folder: `models/[version]/[machine]/[pipeline]/error_summary`

### RAPL power 
#### AbsPower
<-- place `error_abs_*_rapl.png` -->

#### DynPower
<-- place `error_dyn_*_rapl.png` -->

### ACPI power
#### AbsPower
<-- place `error_abs_*_acpi.png` -->

#### DynPower
<-- place `error_dyn_*_acpi.png` -->


---

## Please provide visualized results of preprocessed data for `new-pipeline`
generated preprocessed data image folder: `models/[version]/[machine]/[pipeline]/preprocessed_data`

### RAPL power 
#### AbsPower
<-- place `preprocess_abs_*_rapl.png` -->

#### DynPower
<-- place `preprocess_dyn_*_rapl.png` -->

### ACPI power
#### AbsPower
<-- place `preprocess_abs_*_acpi.png` -->

#### DynPower
<-- place `preprocess_dyn_*_acpi.png` -->

---