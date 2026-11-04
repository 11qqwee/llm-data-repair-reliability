# Beyond Self-Correction: Reliability Control for Large Language Model-Based Data Repair

This repository contains the frozen core artefacts for the Neurocomputing submission: "Beyond Self-Correction: Reliability Control for Large Language Model-Based Data Repair".

To ensure full transparency and reproducibility, we publicly release the exact prompts, verification gate configuration, and evaluation metric policies used in our frozen pipeline.

## Repository Structure

- `code/prompts/`: The exact system and revision prompts used for the zero-shot and FG-SC attempts.
- `code/verification/`: The deterministic, parameter-free YAML configuration of the ground-truth-free verification gate.
- `code/evaluation/`: The formal definitions of the evaluation metrics (CRA, CPR, CDR) and the failure policy.

## Original Datasets

The derived benchmark cases are built upon three public lineages. The original source datasets are not redistributed here but are available at:

- **WikiTableQuestions**: [https://github.com/ppasupat/WikiTableQuestions](https://github.com/ppasupat/WikiTableQuestions)
- **Raha**: [https://github.com/BigData-Research/Raha](https://github.com/BigData-Research/Raha)
- **HoloClean**: [https://github.com/HoloClean/holoclean](https://github.com/HoloClean/holoclean)

## Citation

If you use these prompts or the gate configuration in your research, please cite our paper:@article{wang2026beyond,\
&#x20; title={Beyond Self-Correction: Reliability Control for Large Language Model-Based Data Repair},\
&#x20; author={Wang, Yi},\
&#x20; journal={Neurocomputing},\
&#x20; year={2026}\
}
