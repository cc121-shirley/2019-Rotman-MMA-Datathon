# 2019-Rotman-MMA-Datathon
1. Background:
Diabetes is one of the most prevalent serious diseases in North America. 
In 2008 (at the time of hospital’s planned opening), the US diabetes population was estimated at roughly 18 million. 
Long-term complications of diabetes include heart disease, stroke, kidney failure, limb amputations, and death. 
Poorly managed diabetes can lead to readmissions to the hospital.
A typical patient will be initially diagnosed with early-stage diabetes by their family doctor and prescribed a regimen of diet and exercise. 
If that fails to stop the progression of the disease, the patient will be prescribed Metformin – a very effective drug that will be sufficient for many patients. 
Since the hospital must carry both Metformin and Insulin, the focus of your analysis will be on the “other medications” group.
These medications fall into five different classes:
 Alpha-glucosidase inhibitors
 DPP-4 Inhibitors
 Glitazones
 Meglitinides
 Sulfonylureas
2. Readmission: 
It ndicates whether the patient was readmitted within 30 days of the last hospital admission (“<30”), 
more than 30 days after the last readmission on record (“>30”) or there were no records of previous admissions in the data (“No”). 
Note that readmissions within the last 30 days are tracked particularly closely and are often penalized by government oversight and insurance agencies; 
readmissions that occur more than 30 days since the previous admission are considered less serious.
3. Task
Your task is to analyze the data (using tools of your choice) and make a recommendation for 2 drugs, from different drug classes to be listed on the formulary. 
You may assume that the drugs all cost relatively the same. The primary consideration should be given to readmissions, a large driver of costs to the hospital. 
The director would like to list medications that lead to the lowest number of readmissions when controlling for the baseline illness 
In addition to the main recommendation, consultants should also present 2 alternative medications for consideration. 
The audience for the presentation includes the director of pharmacy, the head of endocrinology, and the CEO.
 The dataset consists of 101766 encounters and 17 kinds of drugs
 This is a supervised learning and the target variable is readmitted
 We aim at finding 2 drugs that decreasing the occurrence of readmission <30 effectively and 2 alternative drugs
 Please find details in datathon notebook2 final.ipynb  file
