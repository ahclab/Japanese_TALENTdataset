# Japanese TALENT dataset

## Dataset Summary:　
This dataset contains recordings of eye movements and facial expressions while two participants engage in a collaborative problem-solving task online. It is a Japanese version of a TALENT dataset in French [Hamet Bagnou+ 2022]. 

Note: The use of the dataset is only permitted for research purposes.

## Data Details:
The pairs with the same number after A or B are those in which the collaborative problem-solving task was carried out. For example, pair 1 includes A01 and B01.

| Name     | Format     | Contents     |
|-----------|-----------|-----------|
| data/eye_movements | xlsx | Raw Tobii output data |
| data/facial_expressions | csv | Raw OpenFace output data |
| data/profile | csv | Participant information |
| data/time_stamp | csv, xlsx | Files of the start and end times of the experiment for Tobii output data and OpenFace output data. Files of speaking time in OpenFace output data |

## Data Recording Details: 
- Fifty healthy participants (age: 39.4 years old; 25 males, 25 females)
- We set up pairs of participants to work on a cooperative problem-solving task via an online communication tool
- This dataset includes behavioral signals of eye movements and facial expressions, scores from anxiety and alexithymia questionnaires and the Social Performance Rating Scale (SPRS)
- Our data collection was approved by the Research Ethics Committee of the Nara Institute of Science and Technology (Approval No. 2022-I-60)
- Data recording setup

<img src="https://github.com/ahclab/Japanese_TALENTdataset/blob/main/docs/setup.png" alt="[setup]" width="700">

- AOI for eye movement analysis
  - Self: Themselves
  - Other: Conversation partner
  - Outside: Other areas

  <img src="https://github.com/ahclab/Japanese_TALENTdataset/blob/main/docs/AOI.png" alt="[AOI]" width="300">

## Citation:
Please cite the following papers when you use the dataset.

```bibtex
@article{miyamoto2023eye,
 title={Eye Movements Related to Anxiety and Alexithymia During a Collaborative Problem-Solving Task},
 author = {Miyamoto, Kana and Tanaka, Hiroki and Nakamura, Satoshi},
 author={Hamet Bagnou, Jennifer and Prigent, Elise and Martin, Jean-Claude and Clavel, C{\'e}line},  journal={Frontiers in Psychology},
 year={2023},
 publisher={The Institute of Electronics, Information and Communication Engineers}
}

