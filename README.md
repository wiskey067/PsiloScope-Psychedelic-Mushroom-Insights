🌿 PsiloScope – Visual and Predictive Analytics of Psychedelic Mushroom Compounds

PsiloScope is an end-to-end data analytics and machine learning project designed to investigate the chemical and physical characteristics of psychedelic mushrooms—specifically those containing psilocybin, a naturally occurring psychoactive compound. What began as a data visualization initiative evolved into a multi-phase analysis involving exploratory data insights, interactive visual dashboards, and classification models to predict mushroom species based on their chemical profiles.

This project bridges the gap between visual storytelling and predictive modeling, uncovering hidden patterns and correlations that could support future research in psychopharmacology, bioinformatics, and fungal taxonomy.



🎯 Project Objectives
	•	Analyze psilocybin concentration across mushroom species using real-world biochemical data
	•	Visualize compound behavior using texture-energy metrics to surface correlations and outliers
	•	Build predictive models to classify mushrooms based on chemical and structural attributes
	•	Combine insights from both Tableau dashboards and Python-based ML models to deliver a holistic view of psychedelic mushroom dynamics



🔍 Background

Psilocybin mushrooms have gained significant attention in recent years due to their potential for therapeutic applications in treating depression, PTSD, and anxiety. Despite their biochemical complexity, few data-driven studies visually or statistically examine how psilocybin concentration varies across mushroom species, or how physical texture and energy profiles might relate to compound expression.

PsiloScope aims to fill this gap by combining interactive visualization tools with supervised machine learning to create a research-friendly resource for exploration and hypothesis testing.



📊 Dashboard Overview – The Visual Lens

The Tableau dashboard presents a multi-layered visual narrative of psilocybin data. It allows users to interactively explore:
	•	🧬 Compound Concentrations: Pie charts and bar plots showing psilocibina (psilocybin) distribution across species
	•	🔄 Texture-Energy Dynamics: Scatter plots and trend lines exploring how physical texture may correlate with chemical behavior
	•	🔍 Comparative Analysis: Filters and controls enabling species-level comparisons for research insight

🔗 Live Tableau Dashboard
👉 View PsiloScope on Tableau Public



🤖 Machine Learning – The Predictive Engine

Beyond visualization, PsiloScope dives into predictive modeling using supervised learning to classify mushroom species. The process includes:
	•	🧹 Data Cleaning & Preprocessing
Handled using pandas, numpy, and sklearn to manage duplicates, encode categorical values, and scale features.
	•	⚙️ Modeling Algorithms Used
	•	Logistic Regression
	•	K-Nearest Neighbors
	•	Decision Trees & Random Forest
	•	Support Vector Machines
	•	XGBoost, LightGBM, and CatBoost
	•	📈 Model Evaluation
Each model is evaluated using accuracy, precision, confusion matrices, and classification reports to determine performance.
	•	📤 Output
The models effectively predict mushroom species based on a variety of biochemical inputs, which can be further tuned or deployed in a classification pipeline.



🧪 Data Insights
• Texture-based energy metrics show meaningful correlations with compound concentrations
• Certain species exhibit unique patterns in psilocybin expression, potentially linked to their biological taxonomy
• Classification models achieved strong performance, suggesting that biochemical properties can be reliable indicators of mushroom type



🛠 Tools & Technologies Used

Category	Tools/Libraries
Data Analysis	Python, Pandas, NumPy
Visualization	Tableau Public, Seaborn, Matplotlib
Machine Learning	Scikit-learn, XGBoost, LightGBM, CatBoost
Jupyter Notebook	For prototyping and modeling
Git & GitHub	Version control and project collaboration

📄 Research Paper – Academic Extension of PsiloScope

To formalize the findings of PsiloScope, I authored a peer-review-style research paper titled:

“A Comparative Analysis of Hyperparameter-Tuned Machine Learning Models for Toxicity Prediction in Amanita Mushrooms Using Visual Features”

The paper was developed using the IEEE LaTeX template on Overleaf, and follows a structured format comprising:
	•	Abstract and Introduction — establishing the motivation and research gap in psilocybin classification
	•	Related Work — summarizing key studies in psychopharmacology and fungal compound analysis
	•	Methodology — detailing preprocessing steps, modeling pipelines, and SHAP-based model explainability
	•	Experimental Results — comparing classifiers (XGBoost, SVM, Random Forest, etc.) on metrics like accuracy, F1-score 
	•	Visualization Integration — embedding Tableau insights to support visual correlation hypotheses
	•	Conclusion and Future Work — outlining limitations and directions for expanding chemical feature datasets

All graphs, charts, and performance metrics were generated in Jupyter Notebook, exported as high-resolution figures, and cited within the manuscript. This allowed for a clean and reproducible workflow from raw dataset to published analysis.

The research paper highlights PsiloScope as more than a project—it is a scalable, interdisciplinary toolkit combining AI, visualization, and psychopharmacology into an accessible, academically rigorous format.

👤 Author

Arijit Bhattacharjee
Data Analyst | Aspiring ML Engineer | Visualization Enthusiast
Email - ab9777816@gmail.com 

