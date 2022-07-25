Crop Recommendation Using Interpretable and Explainable Machine Learning Models 

In this project, I employ machine learning models with the highest interpretability and explainability in order to create the underlying models for a potential recommendation engine that can be used my farmers and agriculturists to decide which crop to grow on their soil in order to maximise yield, based on the nutrient concentrations in the soil. I specifically selected tuned gradient boosted trees, decision trees, and kNN models in order to solve this classification model because of their simplicity - since their underlying intuition is relatively simple to explain (at least compared to the black box models that are the norm in applied machine learning), it would be easier to persuade farmers and agriculturists, who are often skeptical of technologically driven solutions that involve them altering their generational practices.

I used a dataset composed of 620 datasets collected from Indian farms. The datasets included characteristics about the nutrient concentration of the soils as explanation variables and the recommended crop as a response variable. The following inputs were used: 

* N (Nitrogen) - Measured in Kg/Ha
* P(Phosphorus) - Measured in Kg/Ha
* K(Potassium) - Measured in Kg/Ha
* ph - Scale used to specify the acidity or basicity of the soil. Range 0-14
* EC(Electrical Conductivity) - Measured in dS/m
* S(Sulphur) - Measured in percentage(%)
* Cu(Copper) - Measured in PPM(Parts Per Million)
* Fe(Iron) - Measured in ppm(Parts Per Million)
* Mn(Manganese) - Measured in ppm
* Zn(Zinc) - Measured in ppm
* B(Boron) - Measured in ppm

To predict the optimal crop to grow given the nutrient concentrations. It recommended one of the following crops: pomegranate, mango, grapes, mulberry, and ragi.


