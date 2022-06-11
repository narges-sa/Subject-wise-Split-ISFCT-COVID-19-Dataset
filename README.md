# DataSet
A range of characteristic lung features are already kwon for COVID-19, including Ground-Glass Opacity (F1), Peripheral (F2), Central (F3), Peribronchovascular (F4),  Consolidation (F5), Reverse Halo (F6), Crazy paving (F7), and Atelectasis (F8) (8 subclasses) [1]. These radiological patterns are significant for determining the severity of COVID-19 [7], however in previous AI-based studies, such detailed features are all merged in existence or absence of COVID-19. To address this issue, in ISFCT Dataset, 8 characteristic lung features and existence of in right (R) or left (L) lung is marked for each CT slice. figure 1 and Table 2 demonstrate summary and samples of the features. In binary classificiation where only health and COVID-19 is considered, the COVID-19 label is assigned according to presence of F1-R or F1-L, as it is prevalent in other published works.

![image](https://user-images.githubusercontent.com/66547627/173172437-cd4fc674-957f-4f0a-9007-081c5da87b47.png)
Figure 1: Samples of 8 characteristic lung features and one healthy case.

The ISFCT Dataset contains data from 178 subjects diagnosed with COVID-19 (43399 CT slices) and 156 healthy controls (39767 CT slices). All CT slices have the equal size of 768×768 and each subject has (on average) 260 CT slices. The distribution of scans labeled with each of the eight characteristic lung features is presented in figure 2. This dataset, also, has demographic details including gender and age.

Table 1. The explanation of eight characteristic lung features.
![image](https://user-images.githubusercontent.com/66547627/173172766-ce3bafe6-1f01-47ac-be7f-8cf101ca9ded.png)


![image](https://user-images.githubusercontent.com/66547627/173172510-0059aa00-4073-4f63-864c-7ef94f325e84.png)

Figure 2: Distribution of CT slices in each sub classes (8 characteristic lung features).

The Dataset can be observed in: [Link](https://drive.google.com/drive/folders/1wAO8Dof44lmcNieWtCpU-LTEiqxpyuAA?usp=sharing) 

# References
1.	Misztal, K., et al., The importance of standardisation–COVID-19 CT & Radiograph Image Data Stock for deep learning purpose. Computers in Biology and Medicine, 2020. 127: p. 104092.
2.	Gunderman, R.B., Essential radiology. Clinical presentation, pathophysiology, imaging. 2. 2006.
3.	Koo, H.J., et al., Radiographic and CT features of viral pneumonia. Radiographics, 2018. 38(3): p. 719-739.
4.	Hacking, “Lobar consolidation. 2021.
5.	Rossi, S.E., et al., “Crazy-paving” pattern at thin-section CT of the lungs: radiologic-pathologic overview. Radiographics, 2003. 23(6): p. 1509-1519.
6.	Chiarenza, A., et al., Chest imaging using signs, symbols, and naturalistic images: a practical guide for radiologists and non-radiologists. Insights into imaging, 2019. 10(1): p. 1-20.
7.	Zhang, K., et al., Clinically applicable AI system for accurate diagnosis, quantitative measurements, and prognosis of COVID-19 pneumonia using computed tomography. Cell, 2020. 181(6): p. 1423-1433. e11.

# Usage Right:

This work is done by  Shiva ParsaRad** , Narges Saeedizadeh**, Shamim Shafieyoon ,Ghazaleh Jamalipour Soufi, Amir Yousefi, Samira Soleimany, Farzaneh Hekmatnia , Andrew Parviz Zarei, Hengameh Nazari, Pegah Torabi , Ali Hekmatnia, Hossein Rabbani, Rahele Kafieh*

If you find this work useful, you can refer our work as:

@article{ title={Biased Deep Learning methods in Detection of COVID-19 using CT images: a challenge mounted by Subject-wise-Split ISFCT Dataset},

author={ Shiva ParsaRad** , Narges Saeedizadeh**, Shamim Shafieyoon ,Ghazaleh Jamalipour Soufi, Amir Yousefi, Samira Soleimany, Farzaneh Hekmatnia , Andrew Parviz Zarei, Hengameh Nazari, Pegah Torabi , Ali Hekmatnia, Hossein Rabbani, Rahele Kafieh*},

*Corresponding author Rahele Kafieh (rkafieh@gmail.com)

**Shiva ParsaRad and Narges Saeedizadeh have the same contribution.

journal={},

year={2022} }
