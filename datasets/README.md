# Datasets 
Our data was sourced from four offerings of a computer systems course at a public North American institution. The data was divided into two distinct datasets: one for the two winter term offerings in 2021 (referred to as ``dataset_2021``) and the other for the two winter term offerings in 2022 (referred to as the ``dataset_2022``). This division aligns with the instructor’s practice of reusing questions within the same academic year, enabling the application of collaborative filtering by ensuring students from both terms have scores for a common subset of questions

Each of our two datasets consisted of the following three fields: 
* **User ID**: A unique identifier for each student enrolled in the course for that particular year.
* **Question ID**: A unique identifier for each question used in the course for that particular year.
* **Score**: The final score a student received on a specific question, normalized to fall within the range [0,1].