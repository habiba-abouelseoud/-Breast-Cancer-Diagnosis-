# Breast Cancer Diagnosis with Decision Trees

Step-by-Step Explanation:
Root Node:

Attribute: Tumor Size
Decision: If tumor size is small, move to the left child; if large, move to the right child.
Left Child Node (Tumor Size = Small):

Attribute: Tumor Shape
Decision: If tumor shape is irregular, classify as malignant; if regular, move to the next attribute.
Right Child Node (Tumor Size = Large):

Attribute: Age of the Patient
Decision: If the patient is older than 50, classify as malignant; if younger, classify as benign.
Leaf Nodes:

Final nodes represent the diagnosis:
Malignant: Tumor is irregular and either large or the patient is older than 50.
Benign: Tumor is regular and small, and the patient is younger than 50.
