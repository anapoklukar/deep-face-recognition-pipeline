# Deep Face Recognition Pipeline  

**Author:** Ana Poklukar  
**Date:** December 2024  

---

This project was developed for the **Image-Based Biometry** course at the University of Ljubljana. It builds upon the [face recognition pipeline](https://github.com/anapoklukar/face-recognition-pipeline) from Assignment 3 by integrating deep learning approaches for improved performance. The pipeline includes face detection, feature extraction, and recognition evaluation, with comparisons to traditional methods.  

The repository includes a Jupyter notebook with the full implementation and a detailed PDF report. Key components include:  

- **Face Detection:** Implemented using YOLO, RetinaFace, and InsightFace, with accuracy evaluated using Intersection over Union (IoU). Performance is compared to the traditional Viola-Jones algorithm.  
- **Feature Extraction:** Utilized DeepFace and FaceNet to generate facial embeddings, replacing traditional methods like LBP, HOG, and Dense SIFT.  
- **Recognition Evaluation:** Recognition performance assessed through Cumulative Match Characteristic (CMC) curves, both for standalone feature extractors and the full deep-learning-based pipeline. Comparisons are made with traditional methods from Assignment 3.  
