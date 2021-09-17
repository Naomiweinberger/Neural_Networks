# **Image Classification with Convolutional Neural Networks**
![mendeleydata](https://user-images.githubusercontent.com/78061842/133839902-905f12ce-779e-4157-a92b-1431bd2a9bcf.png)
)

## **Author: Naomi Weinberger**
![](http://localhost:8889/view/Pictures/mendeleydata.png)
## **Overview**
Pneumonia is leading cause of death for children, particularly in developing countries. Because of their lack of resources, it is often hard to identify Pneumonia in a timely fashion. Using image classification can help identify those with Pneumonia at a faster rate, and help send resources to those that need them.


## **Data**
The data for this project was sourced by Mendeley Data. 5,232 children's chest X-rays were collected. 3,883 of these had Pneumonia (2,538 bacterial and 1,345 viral) and 1,349 were normal. 
![NORMAL-1049278-0001](https://user-images.githubusercontent.com/78061842/133839912-b8408ed2-15d3-45d3-9291-4794ba94ceda.jpeg)
![BACTERIA-1135262-0002](https://user-images.githubusercontent.com/78061842/133839888-a86a359b-74c1-4a05-a304-89d6c52a6f2b.jpeg)
![VIRUS-9968655-0001](https://user-images.githubusercontent.com/78061842/133839928-938a193f-3fc2-4d42-b26c-5c074d7474af.jpeg)



## **Methods**
This project used CNNS, pretrained networks and a Talos search to optimize results. The scans were divided into two groups: training data and testing data. 

## **Results**
The best preforming model has a loss of 0.0674, an accuracy of  0.9746, a validation loss of 0.1421 and a validation accuracy of 0.9551.

![](https://user-images.githubusercontent.com/78061842/133839918-5f519233-da87-40a9-9469-02c232020984.PNG)
Though other model utilized a talos search and pretrained a pretrained network, the best preforming model didn't use either of those. 


## **Conclusions**
The model has a validation accuracy of over 95%. 

## **Next Steps**
For next steps I would train the model to differentiate between viral and bacterial Pneumonia. I would also explore other pretrained networks and more parameters for the model. 

## **For More Information **
See the full analysis in the [Jupyter Notebook](https://github.com/Naomiweinberger/Neural_Networks) or review this [presentation](https://www.canva.com/design/DAEped8toOs/share/preview?token=L7tSCH8g7S_tsaPK5jnA5A&role=EDITOR&utm_content=DAEped8toOs&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton) 
For additional info, contact Naomi Weinberger at [Weinberger.naomi@gmail.com](Weinberger.naomi@gmail.com)