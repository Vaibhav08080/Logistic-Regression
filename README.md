🧠 Model Description
Logistic Regression is a binary classification algorithm that uses the logistic function to predict the probability of a binary outcome. The model optimizes the binary cross-entropy loss using Gradient Descent.

Mathematical Formulation
The hypothesis is given by:

ℎ
𝜃
(
𝑥
)
=
1
1
+
𝑒
−
𝜃
𝑇
𝑥
h 
θ
​
 (x)= 
1+e 
−θ 
T
 x
 
1
​
 
The cost function (Binary Cross-Entropy):

𝐽
(
𝜃
)
=
−
1
𝑚
∑
[
𝑦
⋅
log
⁡
(
ℎ
𝜃
(
𝑥
)
)
+
(
1
−
𝑦
)
⋅
log
⁡
(
1
−
ℎ
𝜃
(
𝑥
)
)
]
J(θ)=− 
m
1
​
 ∑[y⋅log(h 
θ
​
 (x))+(1−y)⋅log(1−h 
θ
​
 (x))]
Optimization
Gradient Descent is used to minimize the loss function:

𝜃
:
=
𝜃
−
𝛼
⋅
∂
𝐽
(
𝜃
)
∂
𝜃
θ:=θ−α⋅ 
∂θ
∂J(θ)
​
 
📝 Results
Achieved X% accuracy on the training data.

Visualized the decision boundary to understand model performance.

Compared results with scikit-learn implementation.

📊 Visualizations
Loss curve to track training progress.

Decision boundary visualization.
