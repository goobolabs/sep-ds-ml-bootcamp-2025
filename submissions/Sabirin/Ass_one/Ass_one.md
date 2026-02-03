# Name: Sabirin Aboukar Hassan

## 1. What Is Machine Learning? (With a Real-Life Example)

### Definition (in simple words)

Machine Learning (ML) is a part of artificial intelligence (AI) that lets computers automatically learn from data and improve without having specific instructions from humans. In other words, instead of programming every rule, we give the computer lots of examples, and it figures out patterns itself.

### Real-life Example

Imagine a spam filter for your email. At first, you mark many emails as “spam” or “not spam.” The ML system looks at these examples and learns from them. Next time you get an email, even if it is different, the filter can guess if it is spam just because it learned from past examples.

---

## 2. Supervised Learning vs. Unsupervised Learning

### Supervised Learning

Supervised learning uses labeled data, which means the inputs come with known outputs. The model learns to predict outputs based on inputs.

**Example:**  
An email spam filter trained with labeled emails (spam or not spam) that predicts whether new emails are spam.

### Unsupervised Learning

Unsupervised learning uses unlabeled data, meaning only inputs are provided. The model finds patterns or groups in the data on its own.

**Example:**  
Grouping customers by shopping behavior without predefined labels.

### Simple Explanation

Supervised learning is like teaching a child by showing examples such as “This is a dog” and “This is a cat.” The child later recognizes animals.

Unsupervised learning is like giving a child different shapes and colors and letting them group similar ones without guidance.

---

## 3. What Causes Overfitting? How to Prevent It

### What Is Overfitting?

Overfitting happens when a model learns the training data too well, including noise or unimportant details, and performs poorly on new data. It is similar to memorizing answers instead of understanding concepts.

### Common Causes of Overfitting

A model may be too complex compared to the amount of data available. There may not be enough training data for the model to generalize. The dataset may also contain noise or incorrect information.

### How to Prevent Overfitting

Overfitting can be reduced by using more training data so the model sees more variation. Simplifying the model and reducing complexity can also help. Techniques such as early stopping, pruning, regularization, and cross-validation are commonly used.

---

## 4. Why Split Data into Training and Test Sets?

### Process

In machine learning, data is usually split into two parts. Training data is used to teach the model and usually represents about 70–80% of the dataset. Test data is kept separate and used to evaluate the model after training.

### Why This Is Important

If a model is trained and tested on the same data, it may only memorize examples. Using separate test data allows us to measure how well the model generalizes to new, unseen data. This ensures the model performs well in real-life situations.

---

## 5. Case Study: Machine Learning in Healthcare

### Selected Study

A real-world study showed that machine learning can analyze EEG data from b
