# Lesson 03 — The Machine-Learning Workflow

## Learning outcomes

Describe the stages of a basic ML project and explain why evaluation must use data not used to fit the model.

## The workflow

1. **Frame the problem:** define the user, prediction target, and success metric.
2. **Collect data:** ensure it is relevant, permitted, and representative.
3. **Inspect and prepare:** check missing values, duplicates, units, labels, and potential leakage.
4. **Split data:** keep separate training and evaluation data.
5. **Train a baseline:** begin with a simple, understandable method.
6. **Evaluate:** use metrics appropriate to the task and compare with a simple baseline.
7. **Inspect errors:** look at where the model fails and who may be affected.
8. **Deploy or demonstrate:** expose the model carefully if useful.
9. **Monitor and improve:** performance can change when real-world data changes.

## Example

A team wants to predict whether a transaction deserves fraud review. “Accuracy” alone may be misleading if fraud cases are rare. The team should consider precision, recall, review capacity, false positives, and the cost of missed fraud.

## Activity

Choose a small prediction problem. Write:
- Who will use the result?
- What is the target?
- What data might be needed?
- What is a simple baseline?
- What errors would be costly?
- How would you test the model on unseen examples?

## Check your understanding

1. Why should test data not be repeatedly used to choose model settings?
2. What is data leakage?
3. Why should a baseline be built before a complicated model?

## Next step

Continue to Python and data foundations in AI-02.
