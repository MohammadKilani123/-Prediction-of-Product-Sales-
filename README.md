# -Prediction-of-Product-Sales-

# Establish more of supermarket Type one

## To enhance sales at item outlets, our primary focus should be on expanding establishments that emulate the layout and presentation style of Supermarket Type 1. Moreover, it's essential to thoroughly analyze the appearance and arrangement of products in Supermarket Type 1 and replicate these strategies across other supermarket types. The specific type of items being sold may not significantly impact total sales, as they align with consumer necessities. Ensuring that items are presented in a manner akin to Supermarket Type 1 will maximize visibility and increase the likelihood of sales growth.


**Author**: Mohammad Kilani

### Business problem:
Increase item outlet sales

### Data:
[Data](https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/)

## Methods
- I have employed fundamental techniques to manually observe, rectify, and address any inconsistencies.
- Subsequently, I proceeded to visualize the cleaned data to gain a deeper understanding and a broader perspective of the dataset.
- I have attempted various models using the existing features to construct a predictive model for our item outlet sales.
- My recommendation to develop an interface for other supermarket types resembling Supermarket Type One stems from the necessity to gather additional data on consumer behavior. This includes further exploration of the correlation between location, size, and item outlet sales. We are planning to conduct multiple visits to various establishments to gather additional features that could potentially influence item outlet sales but were not included in our existing dataset. These features may include employee uniforms, their demeanor, age, and experience, as well as our discount mechanisms and the presentation of each section. This comprehensive approach will allow us to refine our predictive model and enhance the effectiveness of our strategies.
- The current model tuning details can be found in my notebook. For further information about the model, please refer to the following paragraph


## Results


# Prediction-of-Product-Sales
##### The procedure undertaken to clean the data and ensure alignment with our desired format can be found in the documentation. We've named the dataframe 'df' for easy reference, encompassing every aspect of the data inspected throughout the process.

***following you can find graphs that explore the data we have been provided, i will be briefly addressing a couple of the graphs which will be seen in this read me next,  more analysis available within the repository***

![download (3)](https://github.com/eliekawasfr/Prediction-of-Product-Sales/assets/34871626/049e76d8-b672-4bec-a164-5124062c14e4)

#### comparing outlet type to item outlet sales

![download (4)](https://github.com/eliekawasfr/Prediction-of-Product-Sales/assets/34871626/567792e7-dba6-405c-b710-71ca56ac38ea)

> From our exploration of the previous graphs, we can infer that both Supermarket Type 3 and Supermarket Type 1 exhibit the highest sales. Additionally, it appears that the establishment year of the outlets has a negligible effect on item outlet sales.

## Model: Random Forest Prediction Model
- i would not recommend using this model yet! 'I just test the  **methods** 

 > Model Results for mathematicians

![image](https://github.com/eliekawasfr/Prediction-of-Product-Sales/assets/34871626/c3502dca-6807-4a2d-bebc-af732fbaad87)

##  The model we are presenting here is our premium model for predicting item outlet sales. It operates with an accuracy of 60.3%, which translates to a misprediction of approximately $728. While we can begin using this model, it's crucial to invest more time to ensure a more accurate model for estimating future item outlet sales. This involves exploring additional features and categories that could serve as better indicators, referred to as permutation importance features. Meanwhile, our next objective is to revamp our process to target at least an 80% accuracy in predictions to instill confidence in our future forecasts

---


- Overall, the tuned Random Forest Regressor Model emerges as the superior choice. It significantly outperforms the linear regression model, showcasing its effectiveness in predicting item outlet sales.

- ## Recommendations Limitations & Next Steps:

 
- My recommendation to develop an interface for other supermarket types resembling Supermarket Type One is based on the imperative to gather additional data about consumer behavior. It's essential to further investigate the relationship between location, size, and item outlet sales. To accomplish this, we are advancing by conducting several visits to different establishments to collect more features that may correlate with item outlet sales but were not initially included in our dataset. These additional features could encompass employee uniforms, their demeanor, age, and experience, as well as our discount mechanisms and the decoration/presentation of each section. This comprehensive approach will enable us to refine our understanding of consumer behavior and enhance the effectiveness of our strategies in creating interfaces for other supermarket types.



For any additional questions, please contact **mohammadkilani118@gmail.com**
