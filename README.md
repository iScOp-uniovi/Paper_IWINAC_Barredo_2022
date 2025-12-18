## 📄 Description
This repository contains supplementary material for the paper:

> **"Robust Makespan Optimization via Genetic Algorithms on the Scientific Workflow Scheduling Problem"**
>  
> Published in **Lecture Notes in Computer Science (LNCS), vol. 13259 (IWINAC 2022)**
>
>  Authors: Pablo Barredo, Jorge Puente
>
>DOI: [10.1007/978-3-031-06527-9_8](https://doi.org/10.1007/978-3-031-06527-9_8)
>
> URI: [http://hdl.handle.net/10651/66050](http://hdl.handle.net/10651/66050)

Distributed scientific applications are commonly executed as a workflow of data interdependent tasks on a cluster of different machines. Over the last years, the infrastructure used for solving these problems has evolved from clusters of physical machines to virtual resources in a Cloud based on Quality of Service requirements and pay-per-use basis. In these settings, the total execution time of the workflow, i.e., the makespan, is one of the main objectives. The subsequent optimization problem of distributing the tasks on the available resources, called workflow scheduling problem, is often solved by means of metaheuristics. In this paper we propose an improved workflow model that considers disk times in communications costs. To solve the scheduling problem, we devise a genetic algorithm that produces robust schedules. The experimental study showed that the proposed model is able to predict the execution time of the workflow with more precision than the existing ones in a Cloud Infrastructure as a Services system.

---

## 📂 Repository Content

- `data/` → Dataset used in the experiments and the scripts and configuration files needed to repeat them.
- `code/` → Implementation of the proposed algorithm.
- `results/` → Outcomes obtained after running the algorithm.
- `README.md` → This file containing repository information.

---

## 📊 Datasets and Code

The datasets and code provided in this repository aim to facilitate the reproducibility of the experiments presented in the paper. Please refer to the instructions in each subdirectory for proper usage.

---

## 📥 Using the Material

To access and utilize the supplementary material, clone this repository and navigate to the appropriate directories:

```bash
git clone https://github.com/iScOp-uniovi/Paper_IWINAC_Barredo_2022
cd Paper_IWINAC_Barredo_2022
```


Follow the guidelines in each subdirectory to run the code and analyze the data.

---

## 🔍 Cite this Work

If you use this material in your research, please cite our paper as follows:

```
@inproceedings{Barredo2022,
  author    = {Barredo, Pablo and Puente, Jorge},
  title     = {Robust Makespan Optimization via Genetic Algorithms on the Scientific Workflow Scheduling Problem},
  booktitle = {Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics)},
  year      = {2022},
  volume    = {13259 LNCS},
  pages     = {77--87},
  publisher = {Springer, Cham},
  doi       = {10.1007/978-3-031-06527-9_8},
  url       = {https://link.springer.com/chapter/10.1007/978-3-031-06527-9_8}
}
```

---
## ⚖️ License

This repository is distributed under a dual-license scheme:

- All **datasets, results and documentation** (`data/`, `results/`, `README.md`) are licensed under the  
  **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

- All **source code** contained in the `code/` directory is licensed under the  
  **MIT License**.
---

---

## 📧 Contact
For any questions or inquiries about this work, please contact:  
✉️ **[puente@uniovi.es](mailto:puente@uniovi.es)**


