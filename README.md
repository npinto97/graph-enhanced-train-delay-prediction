# *Predicting Train Delays Using Machine Learning and Knowledge Graphs*  

### **Project Description**  
This project aims to develop a **train delay prediction model** using a combination of **Machine Learning, Deep Learning, and Knowledge Graphs**. Train delays are influenced by various factors, including **historical delays, weather conditions, network congestion, and operational constraints**. Capturing these complex dependencies requires a structured, multi-step approach.  

The project follows an **experimental methodology**, where each step builds upon the previous one to progressively improve predictive accuracy. The main challenges addressed are:  

1. **Temporal Dependency of Delays** – A train’s delay at a given station is influenced by previous delays along the route. **Recurrent Neural Networks (LSTM, GRU)** will be used to model these sequential dependencies.  

2. **Non-Linear Relationships Between Variables** – External factors (e.g., weather, time of day) interact with operational constraints in complex ways. **Ensemble models (Random Forest, XGBoost, SVR)** will be employed to capture these interactions.  

3. **Propagation of Delays Across the Railway Network** – Delays do not only propagate sequentially but also affect interconnected routes. A **Knowledge Graph** will be built to represent stations as nodes and train routes as edges, enriching the predictive model with structural insights.  

4. **Uncertainty in Predictions** – Given the stochastic nature of delays, **Bayesian Regression and Hidden Markov Models** will be used to quantify uncertainty, providing a confidence interval for each prediction.  

The project will progress through multiple phases, starting with **baseline regression models**, followed by the integration of **temporal modeling, graph-based representation, and probabilistic methods**. The ultimate goal is to **evaluate which combination of techniques yields the most accurate and reliable delay predictions**.  

This approach is not just about testing different methods but also about demonstrating **a broad understanding of Machine Learning techniques**, covering various topics studied during the course.  