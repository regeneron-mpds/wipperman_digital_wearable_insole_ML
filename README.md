# Digital wearable insole-based identification of knee arthropathies and gait signatures using machine learning 
<b>Background</b>: Gait is impaired in musculoskeletal conditions, such as knee arthropathy. Gait analysis is used in clinical practice inform diagnosis and to monitor disease progression or intervention response. However, clinical gait analysis relies on subjective visual observation of walking, as objective gait analysis has not been possible within clinical settings due to the expensive equipment, large-scale facilities, and highly trained staff required. Relatively low-cost wearable digital insoles may offer a solution to these challenges. 
<br><br><b>Methods</b>: In this work, we demonstrate how a digital insole measuring osteoarthritis-specific gait signatures yields similar results to the clinical gait-lab standard. To achieve this, we constructed a machine learning model, trained on force plate data collected in participants with knee arthropathy and controls. 
<br><br><b>Results</b>: This model was highly predictive of force plate data from a validation set (area under the receiver operating characteristics curve (auROC) = 0.86; area under the precision-recall curve (auPR) = 0.90) and of a separate, independent digital insole dataset containing control and knee osteoarthritis subjects (auROC = 0.83; auPR = 0.86). After showing that digital insole derived gait characteristics are comparable to traditional gait measurements, we next show that a single stride of raw sensor time series data could be accurately assigned to each subject, highlighting that individuals using digital insoles can be identified by their gait characteristics. 
<br><br><b>Conclusion</b>: This work provides a framework for a promising alternative to traditional clinical gait analysis methods, adds to the growing body of knowledge regarding wearable technology analytical pipelines, and supports clinical development of at-home gait assessments, with the potential to improve the ease, frequency, and depth of patient monitoring.

# Scripts used to generate manuscript results
We have provided notebooks and data necessary to replicate the XGBoost model training and predictions using vGRF and digital insole summary parameters that are presented in paper figures 2 and 4.

# Citation
<a href="https://elifesciences.org/articles/86132"> Wipperman, Lin, Gayvert al. "Digital wearable insole-based identification of knee arthropathies and gait signatures using machine learning". Elife. 2024 Apr 30:13:e86132. doi: 10.7554/eLife.86132 </a>

# License
License can be found in the file LICENSE.
