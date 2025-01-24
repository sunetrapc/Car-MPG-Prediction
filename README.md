# Car-MPG-Prediction
Imagine you’re in a car showroom, and you want to buy a car. But here’s the catch: you don’t just care about the car’s design, price, or color. What really matters to you is how much fuel the car will consume and how far it can go on a single gallon of gas. This measure is called the miles per gallon (MPG).

Now, you’re trying to find a way to predict the MPG of different cars based on their features, like the number of cylinders, weight, and horsepower. You want a tool that can do this prediction for you. Well, this is where our MPG Prediction Model comes into play!

## How I Built It
I’ve created a tool (called a machine learning model) that looks at data from past cars and predicts how many miles per gallon a car will get. But how do I created such a tool? Let me explain:

### Step 1: 
Getting the Data We used a dataset of cars (known as the "Auto MPG dataset") which contains information about the cars' features and their MPG values. Some of the key features include:

Number of cylinders: How many cylinders the car's engine has.
Horsepower: The power the engine produces.
Weight: How heavy the car is.
Each car in the dataset also has an MPG value, which is the number we want to predict.

### Step 2:
Cleaning the Data Just like cleaning up your messy desk, we cleaned up the dataset. Some of the information was missing, so we filled in those gaps to make sure our model wouldn’t be confused.

### Step 3:
Building the Model Think of the model like a brain. We trained the brain (the model) to understand the relationship between the car’s features (like weight, cylinders, and horsepower) and its MPG value. We used a deep learning model for this, which is a fancy way of saying we built a "smart" tool that can learn and make decisions on its own.

In this case, we taught it to learn from past cars, just like how you might learn to predict how much fuel your car will consume after driving a few times.

### Step 4: 
Testing the Model Once our model had learned from the data, we tested it. We gave it new data it hadn't seen before, and asked it to predict the MPG. It did a pretty good job!

Predicted MPG for a car: The model predicted that a car with certain features would have an MPG of, for example, 25 miles per gallon.
We then checked how close this prediction was to the actual value, and it turned out to be very accurate!
