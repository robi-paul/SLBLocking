# SLBLocking: Localization of Optical Side-Channel Leakage in Logic-Locked Integrated Circuits through Structure-based Learning


## Project details and instructions
### Requirements
These libraries are not necessarily the only versions that would work properly. They are, however, the versions used to obtain the recorded results included as a reference.
- Python = 3.7.9
- torch = 1.13.1
- dgl = 1.1.2
- matplotlib = 3.5.3
- networkx = 2.6.3
- numpy = 1.21.6
- pandas = 1.3.5
- openpyxl = 3.1.2
- joblib = 1.2.0

### Datasets
data_total_xor4k - training dataset utilized to train the best models.
- `CLAP_set` -> benchmark circuits set [1] with features and ground truth files for resolution 2, 4 in folder `CLAP_set/g2_gt`, `CLAP_set/g4_gt` respectively.
- `SAT_set` -> benchmark circuits set [1] with features and ground truth files for resolution 2, 4 in folder `SAT_set/g2_gt`, `SAT_set/g4_gt` respectively.
- `Unseen_set` -> circuits set with unseen topologies, features and ground truth files for resolution 2 included in folder `test_comprehensive/g2_gt`.
- `test_comprehensive` -> A comprehensive test set combining all the sets above, features and ground truth files for resolution 2 included in folder `test_comprehensive/g2_gt`.

