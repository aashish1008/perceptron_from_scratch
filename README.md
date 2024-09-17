# Perceptron from Scratch

The Perceptron is an algorithm for supervised learning of binary classifiers. It can be seen as a single unit of an ANN and also known as the Prototype for Neural Nets.
- **Single Layer Perceptron:** Can learn only linearly separable patterns
- **Multilayer Perceptron:** Can learn more complex patterns

  ![image](https://github.com/user-attachments/assets/83538203-d017-4aba-9bc1-9d5430938fa2)

  
## Linear Model:
![image](https://github.com/user-attachments/assets/719ef2eb-7891-4baa-8600-a042d9a88c00)

## Activation Function : Step Function
![image](https://github.com/user-attachments/assets/c1c80233-3299-49ce-9c42-b643df125cc7)
![image](https://github.com/user-attachments/assets/72a419c6-2583-4a72-b319-a6af075ea179)

## Perceptron Update Rule

![image](https://github.com/user-attachments/assets/3f5fbe04-b133-4854-a5d6-7532e3aefb1a)


## Algorithm to implement the perceptron
### Training (Learn Weights):
- Initialize weights
- For each sample:
  1. Calculate the predicted output:

     {y_predicted} = g(f(x)) = g(w^T x + b)

  2. Apply the update rule:
 
     
     Delta w =  learning_rate * (y_i - {y_predicted}_i) * x_i

     Delta b = learning_rate * (y_i - {y_predicted}_i)
 

### Prediction:
- Calculate the predicted output:
  {y_predicted} = g(f(x)) = g(w^T x + b)


