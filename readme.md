The Thrive by Five Index (2021) found that less than half of children attending an early learning programme (such as a preschool or creche) in South Africa start school with the right early learning foundation. There are many factors that influence whether a child Thrives by Five, such as access to a quality early learning programme, as well as poverty, gender, malnutrition, and emotional well-being. Children without a good foundation struggle to keep up at school and have a major learning disadvantage.

The Index used the Early Learning Outcomes Measure (ELOM) to assess children, and categorises their development as either “on track”, “falling behind” or “falling far behind”.

This model uses machine learning techniques to identify which early learning programme factors contribute to better learning outcomes in children, by predicting a child’s ELOM score.

This will allow DataDrive2030 to design better interventions that make optimal use of limited resources to ensure South Africa’s children are thriving.

```python
Approach
```
1. one_for_all: used one model to train and predict all children
2. one_for_one: replaced predictions for child missing key features
3. ensemble: blend and give weights to different model predictions
4. sensitivity: 
    (a) first: make predictions with provided feature value
    (b) new: replace current feature with median value by child_age_group