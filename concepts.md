## Learning Rate
Is a hyperparameter that determines the sizes of the steps taken during the optimization process to minimize the loss function. A smaller learning rate may lead to slower convergence, while a larger learning rate may cause the model to overshoot the optimal solution. It controls how much the models's weights are updated in response to the computed error at each iteration of training.

- Low learning rates - slow convergence, may get stuck in local minima.
- High learning rates - fast convergence, may overshoot the optimal solution.
- Optimal learning rates - balance between convergence speed and stability.

### Techniques to Adjust Learning Rate
1) Fixed Learning Rate - A constant learning rate throughout the training process.
2) Learning Rate Scheduling - Adjusting the learning rate based on a predefined schedule, such as reducing it after a certain number of epochs or when the validation loss plateaus.
3) Adaptive Learning Rate Methods - Algorithms that adjust the learning rate dynamically based on the training process, such as AdaGrad, RMSprop, and Adam.
4) Cyclical Learning Rates - Varying the learning rate between a minimum and maximum value in a cyclical manner, which can help escape local minima and improve convergence.



Loss Function - A mathematical function that measures the difference between the predicted output of the model and the actual target values. The goal of training a model is to minimize this loss function.

Convergence - The process of the model's parameters stabilizing as it learns from the training data, indicating that the model is approaching an optimal solution. 