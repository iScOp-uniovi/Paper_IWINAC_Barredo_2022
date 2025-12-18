# Data Folder

## 📄 Description
This folder contains the datasets used in the experiments for the paper:

> **"Robust Makespan Optimization via Genetic Algorithms on the Scientific Workflow Scheduling Problem"**
>
> Presented at **IWINAC 2024**.
>
> Authors: Pablo Barredo, Jorge Puente
>
> DOI: [10.1007/978-3-031-06527-9_8](https://doi.org/10.1007/978-3-031-06527-9_8)
> 
> URI: [http://hdl.handle.net/10651/66050](http://hdl.handle.net/10651/66050)

Distributed scientific applications are commonly executed as a workflow of data interdependent tasks on a cluster of different machines. Over the last years, the infrastructure used for solving these problems has evolved from clusters of physical machines to virtual resources in a Cloud based on Quality of Service requirements and pay-per-use basis. In these settings, the total execution time of the workflow, i.e., the makespan, is one of the main objectives. The subsequent optimization problem of distributing the tasks on the available resources, called workflow scheduling problem, is often solved by means of metaheuristics. In this paper we propose an improved workflow model that considers disk times in communications costs. To solve the scheduling problem, we devise a genetic algorithm that produces robust schedules. The experimental study showed that the proposed model is able to predict the execution time of the workflow with more precision than the existing ones in a Cloud Infrastructure as a Services system.
---

## 📂 Folder Structure

- `workflows/` → Contains scientific workflow instances extracted from **WfCommons** ([version 1.4](https://github.com/wfcommons/WfInstances/tree/main/pegasus)).
- `hosts/` → Contains different **IaaS configurations** used during experimentation.

---

## 🔍 Workflow Instances
The **scientific workflow instances** in this repository originate from the **WfCommons** repository:

🔗 **WfCommons v1.4**: [https://github.com/wfcommons/WfInstances/tree/main/pegasus](https://github.com/wfcommons/WfInstances/tree/main/pegasus)

To ensure reproducibility, we use version **1.4** of these instances.

---

## 📧 Contact
For any questions or inquiries about these datasets, please contact:  
✉️ **[puente@uniovi.es](mailto:puente@uniovi.es)**
 
