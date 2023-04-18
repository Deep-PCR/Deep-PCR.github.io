# Deep Learning-based Point Cloud Representation


The scope of this project is the design, development, implementation, and assessment of a DL-based static Point Cloud (PC) compressed representation targeting both decoding and enhancement consumptions.

The DL-based PC representation solutions will simultaneously accommodate compression efficiency and effective PC processing using the same compressed domain stream.

This work was funded by the Fundação para a Ciência e Tecnologia (FCT, Portugal) through the research project PTDC/EEI-COM/1125/2021, entitled “Deep Learning-based Point Cloud Representation”.

<img src="https://user-images.githubusercontent.com/124708731/232837219-00b86721-7c8b-49af-a9d9-c5721a4455a5.gif" width=20% height=20%>



# About

Visual communications have a fundamental role in Human societies. In the digital era, this has led to the explosion of image and video-based applications and services, notably following the democratization of image and video acquisition, storage and streaming. However, conventional image and video-based experiences are far from the real-world immersion; this has motivated a rush for more realistic, immersive and interactive visual experiences, notably offering 6-DoF (Degrees-Of-Freedom) experiences where the user is free to exploit the six translational and rotational types of motion, possible in the real world.

The recent advances in visual data acquisition and consumption have led to the emergence of the so-called plenoptic visual models, where Point Clouds (PCs) are playing an increasingly important role. PCs are a 3D visual model where the visual scene is represented through a set of points and associated attributes, notably color (see Figure 1). To offer realistic and immersive experiences, PCs need to have millions, or even billions, of points, thus asking for efficient coding solutions.

![Figure_1](https://user-images.githubusercontent.com/124708731/232832937-53b8ec8a-cbdc-4bd7-87fd-3aa5b1c5a0ec.png)

Efficient and realistic immersive experiences are critical for emerging applications and services, notably virtual and augmented reality, personal communications and meetings, education and medical applications and virtual museum tours. This need has led the MPEG (Moving Picture Experts Group) standardization group to issued two PC coding standards; however, these standards are based on rather conventional technology, notably octree-based coding (G-PCC) and 2D image and video coding standards after 3D to 2D mapping (V-PCC).

Deep learning (DL)-based solutions are currently the state-of-the-art for multiple computer vision tasks, both high-level tasks and lower-level tasks, but also in the image coding domain, reaching competitive performance in a short time. 

The scope of this project is the design, development, implementation and assessment of a DL-based static PC compressed representation targeting both decoding and enhancement consumptions (see Figure 2). The proposed DL-based solutions will simultaneously accommodate efficient fidelity-to-original PC coding, with compression efficiency improvements over available solutions, and effective enhanced-from-original PC processing using the same compressed domain stream. 

![Figure_2](https://user-images.githubusercontent.com/124708731/232832884-b189fd97-0cbf-43f9-a192-5005ce8121ba.png)


# Team

### Leading Organisation: 

### Instituto de Telecomunicações (IT) - Lisbon, Portugal

IT is a private, not-for-profit organization of public interest, association of 6 Portuguese universities, 1 polytechnic, 1 telecom operator and 1 telecom equipment manufacturer, established in 1992 with a mission to create and share scientific knowledge in telecommunications at world level and to host and tutor graduateand post-graduate students. IT earned the statute of Associated Laboratory in 2001, which was renewed in January 2021 with maximum evaluation.

IT offers advanced laboratory facilities in most scientific areas to support applied research, which is carried out in the framework of national and international projects in cooperation with similar research institutions worldwide.

The Multimedia Signal Processing (MSP) Group at Instituto de Telecomunicações has the objective of developing technology in the areas of visual information analysis, modeling, processing, recognition, manipulation, representation, coding and description. The MSP Group has a strong background on these technologies. In recent years, the MSP Group has dedicated special attention to deep learning-based coding and recognition. These activities have especially considered new imaging sensor models, e.g. light fields and point clouds beyond conventional imaging.

The IT team members are with two higher education institutions, Instituto Superior Técnico and Politécnico de Leiria, which provide the academic environment to support the engaged MSc and PhD students. 

### Participating Institutions:

### École Polytechnique Fédérale de Lausanne - School of Engineering (EPFL) - Lausanne, Suisse

The School of Engineering of EPFL has the main missions to educate well-rounded engineering students in preparation for careers in research or industry; to advance and to lead in research discoveries in engineering; and to support and contribute to technology transfer; to innovate in engineering education; and to contribute engineering solutions to societal challenges.

The School is composed of 120 faculty members spread over 5 institutes, namely, Bioengineering, Electrical Engineering, Mechanical Engineering, Materials Science and Engineering and Microengineering. The School has been ranked #12 in QS world university ranking, Engineering & Technology 2018 and #14 THE World University Ranking, Engineering &Technology 2018. The School is responsible for 9 Doctoral Programs in Advanced Manufacturing, Biotechnology and Bioengineering, Electrical Engineering, Energy, Materials Science and Engineering, Mechanics, Microsystems and Microelectronics, Photonics, and Robotics, Control, and Intelligent Systems, involving 800 Doctoral students.

Multimedia Signal Processing Group (MMSPG) of the Institute of Electrical Engineering, headed by Prof. Touradj Ebrahimi will be involved in this project. MMSPG is active in three interconnected areas of signal processing, namely, visual information compression, media security and digital content understanding and interpretation.

### University of Technology, Sydney (UTS) - Sydney, Australia

UTS has consistently been among the top 150 performing universities world-wide in computer science and engineering with world-class facilities and strong industry connections.

Within the Faculty of Engineering and IT, the Perceptual Imaging Lab (PILab) has worked with Industry and Government since 2016 to develop technologies to improve on the quality and user experience of modern imagery, particularly in the areas of 3D scanning technologies, perception science applied to education and cultural heritage, perceptual imaging for virtual reality and augmented reality, computer vision for classification and detection problem in hyperspectral and satellite imagery, subjective quality testing and point cloud and light field technologies. During its four years, PILab has attracted over $700,000 AUD of funding in these fields with partners in the Australian and US governments, cultural heritage and AR/VR content production.

The PILab team have expertise in 3D scanning, color, psychophysics, subjective testing, image and signal processing, machine learning, human vision and perception, affective computing, machine learning and optics. PILab has been involved in international standardization activities, supplying its expertise in designing and performing subjective experiments and assuming a leading role in the development of standards for the coding of point cloud data by the ISO/IEC/JTC 1/SC29/WG1 (JPEG) standardization committee.

# Outputs

#### Software Prototypes:

-	Instituto de Telecomunicações Deep Learning-based Point Cloud Codec (IT-DL-PCC): https://github.com/aguarda/IT-DL-PCC  

This repository includes the source code and trained models of the codecs submitted to the Call for Proposals on JPEG Pleno Point Cloud Coding issued on January 2022:
•	IT-DL-PCC-G: Geometry-only codec
•	IT-DL-PCC-GC: Joint geometry + color codec

#### Papers submitted to International Journals: 

-	André F. R. Guarda, Manuel Ruivo, Luís Coelho, Abdelrahman Seleem, Nuno M. M. Rodrigues, Fernando Pereira, "Deep Learning-Based Point Cloud Coding and Super-Resolution: a Joint Geometry and Color Approach", IEEE Transactions on Multimedia - Special Issue on Point Cloud Processing and Understanding, October 2022.

#### Papers accepted in International Conferences:

-	M. Ruivo, A. Guarda, F. Pereira, “Double-Deep Learning-Based Point Cloud Geometry Coding with Adaptive Super-Resolution”, IEEE European Workshop on Visual Information Processing - EUVIP, Lisbon, Portugal, September, 2022.

-	A. Seleem, A. F. R. Guarda, N. M. M. Rodrigues and F. Pereira, "Impact of Conventional and Deep Learning-based Point Cloud Geometry Coding on Deep Learning-based Classification Performance," 2022 IEEE International Symposium on Multimedia (ISM), Italy, 2022, pp. 74-81, doi: 10.1109/ISM55400.2022.00016.

-	L. Coelho, A. Guarda, F. Pereira, “Deep Learning-based Point Cloud Joint Geometry and Color Coding: Designing a Perceptually-Driven Differentiable Training Distortion Metric”, IEEE International Conference on Multimedia Big Data BigMM, Naples, Italy, December, 2022.

-	M. Ruivo, A. Guarda, F. Pereira, “Learning-based Point Cloud Geometry Coding Rate Control,” Data Compression Conference (DCC), Snowbird, UT, USA, March 2023.

#### Tutorials, Keynotes and Panels at International Conferences:

-	F. Pereira, “Deep learning-based point cloud coding for immersive experiences”, tutorial at ACM International Conference on Multimedia (ACM Multimedia’2022), Lisbon, Portugal, October 2022.

-	F. Pereira, "Deep learning-based extended reality: making humans and machines speak the same visual language", keynote speech at IXR 2022: 1st Workshop on Interactive eXtended Reality, ACM International Conference on Multimedia, Lisbon, Portugal, October 2022.

-	Member of the Experts Panel on "Groundbreaking multimedia research directions", ACM International Conference on Multimedia (ACM Multimedia'2022), Lisbon, Portugal, October 2022.

#### IST MSc Thesis:

-	Luís Guilherme Berenguer Todo Bom, “Deep Learning Architectures for Point Cloud Geometry Coding,” MSc Thesis, concluded July 2022.

-	Manuel Maria de Ornelas Marques Ruivo, “Learning-Based Point Cloud Geometry Coding: Integrating Sampling Tools for Increased RD Performance,” MSc Thesis, concluded November 2022.

-	Luís Adriano Martins Pinto Coelho, “Learning-Based Point Cloud Geometry and Color Coding,” MSc Thesis, concluded November 2022.

#### Technical Reports/Contributions to International Standardization Groups:

-	André F. R. Guarda, Nuno M. M. Rodrigues, Manuel Ruivo, Luís Coelho, Abdelrahman Seleem, Fernando Pereira, “IT/IST/IPLeiria Response to the Call for Proposals on JPEG Pleno Point Cloud Coding”. Doc. M96005, 96th JPEG Meeting, Online, July 2022.

-	André F. R. Guarda, Nuno M. M. Rodrigues, Manuel Ruivo, Luís Coelho, Abdelrahman Seleem, Fernando Pereira, “IT/IST/IPLeiria Response to the Call for Proposals on JPEG Pleno Point Cloud Coding: Performance for Additional Test Point Clouds”. Doc. M96017, 96th JPEG Meeting, Online, July 2022. 

-	André F. R. Guarda, Nuno M. M. Rodrigues, Manuel Ruivo, Luís Coelho, Abdelrahman Seleem, Fernando Pereira, “IT/IST/IPLeiria Response to the Call for Proposals on JPEG Pleno Point Cloud Coding - presentation”. Doc. M96010, 96th JPEG Meeting, Online, July 2022. 

-	André F. R. Guarda, Nuno M. M. Rodrigues, Manuel Ruivo, Luís Coelho, Abdelrahman Seleem, Fernando Pereira, “JPEG Pleno Point Cloud Coding Verification Model Description”. Doc. M97094, 97th JPEG Meeting, Online, October 2022.

-	André F. R. Guarda, Nuno M. M. Rodrigues, Fernando Pereira, “Report on PCC Core Experiment 1.1: Performance of the Verification Model under Consideration”. Doc. M97088, 97th JPEG Meeting, Online, October 2022.

-	A. Guarda, S. Perry, “Verification Model Description for JPEG Pleno Learning-based Point Cloud Coding v1.0,” Doc. N100367, 97th JPEG Meeting, Online, October 2022.

-	A. Guarda, S. Perry, “PCQ-WD ISO/IEC 21794-6,” Doc. N100368, 97th JPEG Meeting, Online, October 2022.


