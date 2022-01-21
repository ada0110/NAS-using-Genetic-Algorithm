# Neural Architecture Search using Genetic Algorithm
In this project we have used Genetic Algorithm to do Neural Architecture Search(NAS) for finding the best performing Convolution Neural Network(CNN) architecture on the [fashion-mnist](https://www.kaggle.com/zalando-research/fashionmnist) dataset.

Our objective was to find a model that gives highest accuracy while using least number of parameters. Thus we used the `fitness_score = accuracy/log(numberof parameters)`.

We used the following genetic algorihtm startegy to achive this:
![image](https://user-images.githubusercontent.com/64487038/150488639-7febabbe-ea13-49c3-b24e-c13b1551ad05.png)

Following is the scatter plot of various models, their accuracy and fitness scores.
![image](https://user-images.githubusercontent.com/64487038/150488986-92331379-ad5e-4430-a64f-727b9828ab02.png)

Please check the attached report for more details.
