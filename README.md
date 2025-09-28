Q5: Evaluation Metrics from a Multi-Class Confusion Matrix

Program uses a confusion matrix showing system predictions vs. actual labels for Cat, Dog, and Rabbit.

For each class, it calculates:

True Positives (TP): correct predictions.

False Positives (FP): predicted class incorrectly.

False Negatives (FN): missed correct class.

From these, it computes:

Precision: of all predicted instances of a class, how many are correct?

Recall: of all actual instances of a class, how many were found?

Results are summarized in two ways:

Macro Average: simple average across all classes (equal weight to each class).

Micro Average: combine totals first, then calculate (larger classes have more weight).

Prints precision and recall per class, along with macro and micro averages.

Q8: Bigram Language Model Implementation

Program trains a bigram model using three short sentences (“I love NLP”, “I love deep learning”, “deep learning is fun”).

Counts:

Unigrams: how often each word appears.

Bigrams: how often each consecutive word pair appears.

Calculates probabilities:

Example: if the sequence is “I love”, what is the chance the next word is “NLP” or “deep”?

Defines a function to compute sentence probability by multiplying all bigram probabilities.

Tests two sentences:

“I love NLP” → probability = 1/3.

“I love deep learning” → probability = 1/6.

Prints counts, probabilities, and results.

Concludes that the model prefers “I love NLP”, since that sequence appears more strongly in training data.