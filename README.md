## Contact

<div id="badges">
  <a href="https://www.linkedin.com/in/omar-montenegro-macia">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="mailto:omarmontenegromacia@gmail.com">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"/>
  </a>
</div>

## About myself

Computer Engineering graduate with a Master's in High-Performance Computing (HPC). Specialized in designing and optimizing AI solutions. Experienced in Python architecture design, inference pipeline optimization, Docker deployment, and AWS-based performance analysis and scalability.

I also have hands-on experience in Robotics. SLAM, GPS localization, intelligent algorithms and related technologies are of my interest!

- 🔭 I’m currently investigating on ways to implement a multi-modal RAG system on [JETRAG](https://github.com/Omimacgithub/JETRAG).
- 🌱 I’m currently learning about Machine Learning applied to solve Natural Language Processing tasks.

## Experience

**HPC Research Intern – CITIC (Centro de Investigación en TIC) | 02/2025 – 08/2025** (External Internship)

I worked as CITIC research Intern on the High-Performance Computing field. Despite having my own office seat, my site was on robotics lab, where I managed Summit_XL mobile robot for software development. My main contributions were the following:

- Optimized image pre and post-processing pipelines, as well as computer vision models inference within a multi-camera detection and recognition system, reducing inference latency by up to six times using a GPU.

- Integrated a Machine Learning algorithm that identifies new individuals based on the system's data distribution and includes them, thereby expanding the knowledge base without needing to retrain the models.

- Scaled the system, initially operating with 2 cameras, to work with up to 10 cameras simultaneously in real-time.

- Developed a face-tracking algorithm that efficiently recollects frame sequences for each individual. It was tested on videos sampled from two Kinect cameras installed on a mobile robot, with both people and the robot in motion, causing multiple visual occlusions involving objects and other people.

- Deployed the system using Docker, creating separate containers for the application (with NVIDIA GPU support) and a Redis database. The deployment was managed through a docker-compose.yml configuration.

- Researched and implemented a method for biometric template protection that prevents an attacker from reconstructing the original face image from model features, thereby fulfilling the requirements of the General Data Protection Regulation (GDPR).

**eCommerce Developer - Orienteed, S.L.U | 09/2023 – 12/2023** (External Internship)

My main contributions were the following:

- Improved the user experience by fixing product loading errors through React code review of a B2B application.

- Provided detailed product information by integrating data via REST and GraphQL APIs.

- Collaborated with multidisciplinary teams (development and QA) following Agile methodologies (Scrum).

## Education

**Master's Degree in High-Performance Computing (Final Grade: 8.7/10) - UDC · USC · CESGA | 09/2024 – 02/2026**

- Master's Thesis (Grade: 9.5/10): Machine Learning-Based Facial Recognition on High-Performance Embedded Architectures ([publication](https://www.linkedin.com/posts/omar-montenegro-mac%C3%ADa-02650a27b_memoria-tfm-activity-7433140966062075904-8XP7/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEQ9r54B4yRM2L_mEAazKPyOvSZfRE6yLkc)).

**Bachelor's Degree in Computer Engineering (Final Grade: 8.0/10) - UDC | 09/2020 – 07/2024**

- Bachelor's Thesis (Grade: 8.8/10): Tool for Creating and Monitoring ROS (Robot Operating System) Missions for Precisely Localizable Mobile Robots ([repository](https://github.com/Omimacgithub/summit_xl_rosmc), [publication](https://ruc.udc.es/entities/publication/862bed3e-c7c4-4a71-95fc-fb7eae639d4d)).

## Projects

### Hackathon projects

**HackUDC 2025 - Clothing Search and 3D Visualization Web Application ([repository](https://github.com/DisguisedPigeon/HackUDC2025))**

- Implemented requests to external APIs to retrieve garment data and display it on the website using detailed and organized cards.

**HackUDC 2024 - Electricity Bill Analysis Application using Pandas ([repository](https://github.com/DisguisedPigeon/HackUDC2024))**

- Processed users' CSV electricity bills to generate yearly consumption visualizations, providing relevant insights such as the months with the highest energy expenditure.

### AI-powered applications

**JETRAG - Local RAG assitant targeting NVIDIA Jetson embedded systems ([repository](https://github.com/Omimacgithub/JETRAG)) | 03/2026 – Present**

- Defined architecture and design details on an AGENTS.md file for OpenCode to build the application.

- Developed in FastAPI + SvelteKit a conversational assistant based on Retrieval-Augmented Generation (RAG) with the Gemma4 model. The architecture has been optimized for execution on embedded hardware (NVIDIA Jetson).

- Designed a CI/CD pipeline to automate app testing and deployment in Docker with a single command.

**JA3 - Job Application Accelerator Agent ([repository](https://github.com/Omimacgithub/JA3)) | 09/2026 – Present**

- Designed an AI agent n8n workflow that automatically analyzes your profile, generates a new CV and motivation letter suited for the job offer and store each into a file.

### Cloud & Infrastructure (AWS)

**Hadoop cluster deployment and maintenance lab on AWS ([repository](https://github.com/Omimacgithub/AWSHadoopLab/tree/main)) | 11/2024**

- Worked with large files on HDFS and used backup tools, fsck, and EC, achieving data protection.

**Scalability analysis of AWS infrastructure using the NPB benchmark ([repository](https://github.com/Omimacgithub/CFD-kernel-scalability-analysis-AWS)) | 12/2024**

- Analyzed the influence of instance affinity on performance for communication-intensive workloads.

- Analyzed the performance and scalability of different instances to determine the best cost-efficiency balance based on the workload.

### High-Performance Computing (HPC)

**Sparse Matrix-Vector product optimization  ([repository](https://github.com/Omimacgithub/spmv/)) | 12/2024**

- Analyzed performance using several sparse matrix storage formats (COO, CSR and CSC).
- Implemented and modified code to enable compiler autovectorization to achieve minimum latency on sparse Matrix-Vector product.

**BERT Fine-Tuning Performance Analysis on Finisterrae III using NVIDIA A100 GPUs. ([repository](https://github.com/Omimacgithub/HPCT_Lab-AI)) | 10/2024**

- Analyzed the performance differences between a parallel training strategy (multiple GPUs) and a sequential one with a single GPU.

### Robotics

**SUMMIT_XL_ROSMC - GUI tool for performing missions on Robotnik Summit-XL mobile robot ([repository](https://github.com/Omimacgithub/summit_xl_rosmc)) | 02/2024 - 07/2024**

- GUI tool integrated on the mobile robot Summit\_XL to ease its control for the end user.

## Courses

### IT Automation

**Google IT Automation with Python ([certificate](https://coursera.org/share/afc23e23747fced2a1359ba521254ca6)) | 06/2026 - 09/2026**

Google course oriented to IT professionals. I highlight the following learned skills:

- Deep understanding of basic and extended **regular expressions**, which is crucial for searching information on huge data.

- Creation of Python scripts that manipulate and process big data files (e.g. csv and re modules).

- Strong foundation on Git and GitHub for developing on collaborative environments and best practices (e.g. use of git rebase command to merge changes into a single commit, ready for merge on the production branch via pull request).

- Use of unittest and pytest modules to create and execute tests on Python.

This course **is not properly updated** to the last trends on the industry. In fact, it teaches **Puppet**, a software management tool that stopped receiving updates 2 years ago. Otherwise, **it is useful** for IT professionals that want to deep dive into file manipulation with Python and Git/GitHub for team software development.

## Languages and tools
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/fastapi/fastapi-original-wordmark.svg" title="FastAPI" alt="FastAPI logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" title="Linux" alt="Linux logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original-wordmark.svg" title="Docker" alt="Docker logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" title="amazonwebservices" alt="amazonwebservices logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/opencv/opencv-original-wordmark.svg" title="OpenCV" alt="OpenCV logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pytorch/pytorch-original-wordmark.svg" title="Pytorch" alt="Pytorch logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original-wordmark.svg" title="Pandas" alt="Pandas logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="Numpy" alt="Numpy logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/matplotlib/matplotlib-original-wordmark.svg" title="Matplotlib" alt="Matplotlib logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/slurm/slurm-original-wordmark.svg" title="Slurm" alt="Slurm logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/scipy/scipy-original-wordmark.svg" title="Scipy" alt="Scipy logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/c/c-original.svg" title="C" alt="C logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/ros/ros-original-wordmark.svg" title="ROS" alt="ROS logo" width="80" height="80"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/ros2/ros2-original-wordmark.svg" title="ROS2" alt="ROS2 logo" width="80" height="80"/>&nbsp;
</div>
