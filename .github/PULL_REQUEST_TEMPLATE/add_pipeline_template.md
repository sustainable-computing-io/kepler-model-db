*** The uploaded model must be trained and exported by [model training instruction in kepler-model-server](https://github.com/sustainable-computing-io/kepler-model-server/tree/main/model_training). *** 

```
Notation: 

  [version]: kepler-model-server version (current: v0.7)
  [pipeline]: trained pipeline name (default: std_v0.7)
```
---

## Please confirm the following checklist for any applicable item.

- [ ] rename PR by the following format:

  ```
  models ([version] [pipeline])
  ```

### New pipeline
- [ ] has the pipeline information generated in `models/[version]/.doc` (auto)
- [ ] fill description in the generated page. (manual)
- [ ] add tag `new-pipeline` to the PR

### Existing pipeline 
- [ ] remove pipeline entry in `models/[version]/README.md` (manual)
      
### File checklist (auto)
- [ ] pipeline metadata (`metadata.json`)
- [ ] node type index (`node_type_index.json`)
- [ ] model metadata summary files (`xxx_model_metadata.csv`)

### Common checklist
- [ ] has result page generated in  `models/[version]/[pipeline]/error_report` (auto)
- [ ] verified account of PR committer matches publisher
- [ ] no change on other files except the above mentioned document and trained pipeline files in `models/[version]/[pipeline]`

---
## Please provide visualized results of error summary

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

