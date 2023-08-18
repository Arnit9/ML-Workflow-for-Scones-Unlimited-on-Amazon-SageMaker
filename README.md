# ML Workflow for Scones Unlimited on Amazon SageMaker 🥐🚚

Welcome to the ML Workflow for Scones Unlimited project! As a Machine Learning Engineer at Scones Unlimited, you'll be embarking on a journey to build an image classification model that can distinguish between bicycles and motorcycles. This model will have a multitude of applications, from optimizing delivery routes to identifying defects in products. With the power of AWS SageMaker, Lambda functions, and Step Functions, you'll create an end-to-end ML workflow that's scalable, efficient, and dependable. 🛠️📷

## Project Overview 📋

In this project, you will design and implement a scalable image classification model using Amazon SageMaker. Your goal is to create a workflow that can distinguish between bicycles and motorcycles, thus aiding Scones Unlimited in assigning delivery professionals to appropriate orders. The project unfolds in several key steps:

### Step 1: Data Staging 📂

- Set up a SageMaker Studio workspace.
- Prepare and load the data into SageMaker.
- Ensure the data is preprocessed and ready for machine learning.

### Step 2: Model Training and Deployment 🚀

- Train a machine learning model on SageMaker.
- Deploy the trained model as an API endpoint.
- Construct an API endpoint that's linked to the deployed model.

### Step 3: Lambdas and Step Function Workflow ⚙️

- Develop three Lambda functions to orchestrate the workflow:
  1. Retrieve image data as an event.
  2. Perform image classification.
  3. Filter out low-confidence inferences.
- Create a Step Function to weave the Lambdas into a seamless workflow.

### Step 4: Testing and Evaluation 🧪

- Rigorously test and evaluate the performance of your ML workflow.
- Ensure the classification model achieves a test accuracy above **94%**.

### Step 5: Optional Challenge 🏆

- Take on an optional challenge to further enhance your project's capabilities.

### Step 6: Cleanup Cloud Resources ♻️

- Wrap up the project by cleaning up unnecessary cloud resources.

## Skills Applied 🧠

Throughout this project, I've applied the following skills:

- Utilize SageMaker Studio for a productive ML environment.
- Train and deploy ML models on SageMaker.
- Create and manage AWS Lambda functions.
- Design and implement Step Functions to compose Lambda workflows.
- Monitor and evaluate model performance using SageMaker Model Monitor.
- Visualize and interpret Model Monitor data.

Feel free to connect for any inquiries or insights. Happy building and scone-classifying! 🥐🤖
