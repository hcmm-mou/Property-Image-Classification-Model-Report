# Property Image Classification Model Report & Research

## Project Overview 
This project completed training notebook and evaluated the classification model to automate the classification of property images for Real Estate Agency X (case study). The agency processes approximately 50,000 new properties monthly, which required manual categorization and processing of photos into categories such as living room, bedroom, kitchen, bathroom, and exterior, a process that previously consumed ~**16,650 hours** of manual labour per month for workers. The primary purpose of this project is to understand ML lifecycle (development, evaluation, implementation, ect.) and research AI solutions to business problems.

### Business Objectives
- Improve employee satisfaction by reducing repetitive manual tasks
- Reduce operational costs and labor requirements
- Reallocate resources to higher-value activities for business growth

### Solution
- **Model**: InceptionV3 (transfer learning) with fine-tuning
- **Framework**: TensorFlow/Keras (implemented in Google Colab)
- **Evaluation Metric**: Accuracy (primary), with F1-Score consideration
- **Dataset**: Labeled property images across multiple categories

## Key Results
- **Validation Accuracy**: 68.4% after 10 epochs
- **Validation Loss**: 0.896 (45% reduction from initial)
* Moderate overfitting observed (train acc: 0.58, val acc: 0.68)
* Model training demonstrated consistent improvement and solid baseline performance for a real estate image classifier

### Prediction Results
![image alt](https://github.com/hcmm-mou/Property-Image-Classification-Model-Report/blob/2c99ec76f509252a83d9d09b5885c5a5db63f652/data%20and%20model%20training/model_prediction_test.png)

### Impact
The model significantly reduces manual workload while maintaining acceptable accuracy, enabling partial automation under human supervision. It successfully addresses core business pain points and lays the foundation for scalable ML solutions.



**Project Status**: Completed model prototype with proposal & evaluation report  
**Documentation**: [Project Proposal](https://github.com/hcmm-mou/Property-Image-Classification-Model-Report/blob/2c99ec76f509252a83d9d09b5885c5a5db63f652/project%20report/project_proposal.pdf) | [Model Evaluation Report](https://github.com/hcmm-mou/Property-Image-Classification-Model-Report/blob/2c99ec76f509252a83d9d09b5885c5a5db63f652/project%20report/model_evaluation_report.pdf)




