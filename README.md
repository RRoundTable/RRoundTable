# Wontak, Ryu
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/RRoundTable/hit-counter)](https://hits.seeyoufarm.com)

## Machine Learning Engineer

### Professional Summary

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/wontak-ryu-bb26b4137/)](https://www.linkedin.com/in/wontak-ryu-bb26b4137/)
[![Tech Blog Badge](http://img.shields.io/badge/-Tech%20blog-black?style=flat-square&logo=github&link=https://rroundtable.github.io/blog/)](https://rroundtable.github.io/blog/)
[![Facebook Badge](https://img.shields.io/badge/facebook-1877f2?style=flat-square&logo=facebook&logoColor=white&link=https://www.facebook.com/profile.php?id=100024528850182)](https://www.facebook.com/profile.php?id=100024528850182)
[![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:ryu071511@gmail.com)](mailto:ryu071511@gmail.com)

- As a machine learning engineer, I worked on a series of tasks required for ML production, ranging from model training and reproduction, model optimization, serving, API optimization, and infrastructure setup.

- In addition to this, I have developed [Segmentation Similarthings](https://huggingface.co/spaces/Annotation-AI/segment-similarthings) using the Segment Anything Model (SAM) and Support Embeddings. SAM is a foundation model that has zero-shot performance. Segmentation Similarthings applies machine learning to find similar objects while adjusting the number of inferences. For example, if you want to find 10 similar objects in an image, you only need 10 inferences! This is a more efficient way to segment similar objects in an image compared to segmenting all objects in an image which requires 1,024 inferences per a single image.

### ML Problem Solver @ [AnnotationAI](https://www.annotation-ai.com/) [2022.07 ~ ]

AnnoWiz is a tool that helps to generate high-quality training data more efficiently based on semi-automatic data labeling technology. It automates the bounding box and polygon segmentation tasks with 70% to 99% accuracy depending on the class, reducing the time needed for AI training data processing by up to 90%. This is particularly useful for industries that require a lot of data preprocessing.

At Annotation-AI, I worked on the following projects:

- Worked on Triton Serving, an open-source software stack for AI inference workloads. This allowed for efficient deployment of deep learning models in production.
- Implemented TensorRT quantization to optimize throughput and memory usage of deep learning models.
- Developed Segmentation Similarthings, which applies machine learning to find similar objects while adjusting the number of inferences. This is a more efficient way to segment similar objects in an image compared to segmenting all objects in an image which requires 1,024 inferences per a single image.
- Wrote a [technical blog on gRPC load balancing](https://blog.annotation-ai.com/grpc-loadbalancing-in-k8s/), which explained how to implement load balancing in gRPC using Kubernetes and Traefik.
- Optimized Python FastAPI to improve its performance and efficiency.
- Conducted load testing and profiling to identify and fix performance issues in the system.
- Developed a Golang Echo API for more light and efficient API.
- Developed a logging system architecture in Kubernetes with Loki, Promtail, and Grafana. This allowed for efficient monitoring and troubleshooting of the system.

### MLOps Engineer @ [SpaceWalk](https://spacewalk.tech/) [2021.06 ~ 2022.06]

Spacewalk analyzes the characteristics of the environment that developers want to develop by combining various data such as land, transportation, surrounding prices, and building regulations. It derives development scenarios optimized for the given environment using design strategies acquired by artificial intelligence through deep reinforcement learning.

At SpaceWalk, I worked on the following projects:

- Accelerated the reinforcement batch inference speed through unlimited parallel processing using AWS and Kubernetes. This involved building a scalable and efficient infrastructure for reinforcement learning models.[[Blog Post](https://medium.com/spacewalk-blog/accelerating-reinforcement-batch-inference-speed-through-unlimited-parallel-processing-aws-k8s-b58debe0e095)]
- Built a workflow pipeline for AI services using Argo Workflows. This allowed for efficient and automated execution of machine learning workflows.
- Built ArgoCD for CI/CD, which is a continuous delivery tool that automates the deployment of applications to Kubernetes clusters.
- Built ArgoCD Vault for protecting secrets, which is a secure and scalable way to manage secrets in Kubernetes.
- Conducted a seminar on readable code and code review for machine learning engineers. This helped to improve the quality of code and collaboration among team members.
- Used Kubernetes in AWS to build a scalable and reliable infrastructure for machine learning workloads.

### Machine Learning Engineer @ [Makinarocks](https://www.makinarocks.ai/) [2020.02 ~ 2021.06]

Markinarocks is an AI startup that specializes in providing AI solutions and enterprise ML Ops platforms (Markinarocks Runway) for industries such as semiconductors, automobiles, manufacturing, and energy. It was selected as one of the "2023 Top 100 AI Companies" by CB Insights, a global market research firm. It is the only Korean company among the companies selected this year.

At Makinarocks, I worked on the following projects:

- Developed an anomaly detection service for robotics based on autoencoder. This involved training deep learning models to detect anomalies in sensor data from robots. [[News](https://www.irobotnews.com/news/articleView.html?idxno=23243)]
- Developed a residual autoencoder and resolved the noisy gradient problem with warm-up and proved it with mathematical expressions. This improved the performance and efficiency of deep learning models.[[Blog Post](https://makinarocks.github.io/Gradient-Accumulation/)]
- Developed a regression test pipeline for machine learning models. The pipeline automatically runs train and evaluate whenever a commit is pushed with GitHub self-hosted runner. The runner is running on the company's own GPU, which allows for efficient and scalable testing of machine learning models. [[Blog Post](https://makinarocks.github.io/Regresssion-Test/?fbclid=IwAR33ILGNd854Au3yO8qHgHHledB3Rn9hOUceDJy0BYEJLUfS8JtqqYVlk28)]


### Research Engineer Intern @ [VUNO](https://www.vuno.co/en) [2019.8 ~ 2019.11]

VUNO is a medical AI company that provides AI-based fundus image reading support solutions for medical professionals. Its core AI technology "Method for supporting fundus image reading for a subject and device using the same" has been patented in the United States. VUNO's technology considers the anatomical characteristics of the fundus to provide user convenience when reading fundus images using AI. It automatically finds the center of the macula and optic disc in fundus images and outputs diagnostic information in each segmented area based on those centers. This provides information on the fundus segmentations and allows for intuitive confirmation of the location-specific features of major findings.

At VUNO, I worked on the following projects:
- Developed a reliable classifier using Class Activation Map. This allowed me to explain how the model predicts the data, which is important for transparency and interpretability of the model.
- Dockerized production-ready ML models. This involved packaging the models and their dependencies into Docker containers, which made them portable and easy to deploy across different environments.


### AWARDS

- 3rd Prize in [EO Detection Contest 2020](https://dacon.io/competitions/official/235492/overview/)
- 1st Prize in [Open Innovation Hackerton 2019](https://www.youtube.com/watch?v=tDl6UmlbNBs&ab_channel=%EC%84%B1%EB%82%A8TV)
