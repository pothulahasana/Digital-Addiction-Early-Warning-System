# Digital Addiction Early Warning System
This repository is attached the following files:
  1. Data Set of digital_addiction_dirty_data (.csv)
  2. Data set of digital_addiction_clean_data (.csv)
  3. Data set of digital_addition_data (.ARFF)
  4. Project Documentation (.docx)
  5. Project Presentation (.pptx)
  6. Project Documentation (.pdf)
  6. Detailed Explanation in the form of Readme file for Implementation steps and the modules been in the Repo...

📘 Digital Addiction Early Warning System using WEKA
📌 Overview

This project focuses on analyzing digital addiction level of users and predicting their risk  using machine learning techniques. The system uses the WEKA tool to preprocess data, apply classification algorithms, and generate meaningful insights from digital addiction.

🎯 Objective
Analyze digital addiction data
Preprocess dataset using WEKA
Convert categorical data into machine-readable format
Build a classification model using J48 algorithm
Predict user Risk levels
📊 Dataset Description

The dataset contains attributes related to student engagement such as:

1. digital_addiction_risk_level : Safe,  At Risk, High Risk.-->Target Attribute
2. user_id: U1000 – U1118.
3. date: 01-01-2025  -   31-01-2025.
4. day_of_week:  Mon – Sun.
5. is_weekend: 1, 0.
6. total_screen_time_min: 0 - 1440
7. unlock_count: 0 - 1440
8. avg_session_time_min: 0 - 1440
9. longest_session_min: 0 - 1440
10. first_pickup_after_wakeup_min: 0 - 1440
11. night_usage_min: 0 - 600
12. social_media_time_min: 0 - 1440
13. education_app_time_min: 0 - 1440
14. entertainment_time_min:  0 - 1440
15.  short_video_time_min: 0 - 1440
16. passive_usage_ratio: 0 - 1
17. app_switch_count: 0 - 86400
18. notification_received: 0 - 86400
19. notification_opened: 0 - 86400
20. boredom_level: 1-5
21. stress_level: 1-5
22. loneliness_level: 1-5
23. mood_before_usage: 1-5
24. mood_after_usage: 1-5
25. urge_without_reason: 0, 1
26. peak_usage_hour: 0-23
27. usage_during_classes: 0, 1
28. usage_during_meals: 0, 1
29. late_night_streak_days: 0-7
30. weekend_usage_spike: 0, 1
31. phantom_check_events: 0-86400
32. auto_unlock_events: 0-86400
33. anxiety_without_phone: 0, 1
34. attempted_reduction: 0, 1
35. reduction_failed: 0, 1
36. sleep_disruption: 0, 1
37. productivity_impact: 1-5
38. physical_activity_min: 0-1440
39. offline_hobby_time_min: 0, 1
40. social_interaction_time_min: 0, 1
41. academic_pressure_level: 1-3
42. social_support_level:  1-3
43. device_count: 1-10
44. usage_intensity_score: 0-1
45. emotional_dependency_score: 0-1
46. control_failure_index: 0-1
⚙️ Technologies Used
WEKA (Data Mining Tool)
Java
CSV / ARFF File Formats
🔄 Methodology
1. Data Preprocessing
ReplaceMissingValues (handling missing data)
NominalToBinary (convert categorical to numeric)
Normalize (scale numeric values)
2. Classification
Algorithm used: J48 Decision Tree
Evaluation method: 10-fold cross-validation
3. Clustering
Algorithm used: K-Means (SimpleKMeans)
Groups students based on engagement patterns
📈 Results
Accuracy: 75%
Confusion Matrix generated
Decision Tree visualization created
Cluster patterns identified
🌳 Decision Tree Insight

The decision tree is built using the J48 associator using Weka.
📸 Screenshots

Include screenshots of:

Data preprocessing (WEKA Preprocess tab)
J48 classifier output
Decision tree visualization
Clustering results
🗂️ Project Structure
📁 Student-Engagement-Analysis
 ┣ 📄 dataset.csv
 ┣ 📄 dataset.arff
 ┣ 📄 report.pdf
 ┣ 📄 README.md
 ┗ 📁 screenshots/
🚀 Future Enhancements
Improve accuracy using advanced algorithms (Random Forest, SVM)
Use larger datasets
Develop a web-based interface
Integrate real-time data analysis
📝 Conclusion

This project demonstrates how machine learning can be used to analyze digital addiction and predict Risk level. It provides valuable insights that can help improve academic decision-making, user health and overall user well being.

🙏 Acknowledgment

We would like to thank our faculty and institution for their support in completing this project.

👨‍💻 Authors
Leela_Pavani_Suravarapu
Hasana_Pothula
Rokhiya_Begum
N_D_S_S_Madhavi
