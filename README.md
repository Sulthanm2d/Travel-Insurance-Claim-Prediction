# Travel-Insurance-Claim-Prediction
Capstone Modul 3
## **Context**
SingLife Travel Insurance is a company that specializes in providing travel insurance services. SingLife, based in Singapore, is a digital life insurance company known for its innovative approach to financial products.

The company operates in the insurance sector, offering various insurance products digitally. Travel insurance is one of the specific areas they focus on, providing coverage for individuals traveling for leisure or business.

## **Problem Statement**
Despite SingLife's commitment to delivering insurance services, it has encountered challenges in efficiently handling customer insurance claims. To address this issue, the company is seeking the expertise of a data scientist. The data scientist's role would involve analyzing and predicting whether a customer is likely to file an insurance claim. This predictive analysis aims to enhance the company's claim handling processes, ensuring more effective and timely responses to customer needs.

## **Goals**
Create a machine learning model that can be used by insurance companies to predict which customers will claim/not claim.

Machine learning models must be able to minimize losses to the smallest possible extent.

## **Metrics Evaluation**
- **FN**: The company estimates a loss of 800 SGD for cases where customers who actually make a claim (default) go undetected. This figure encompasses the loss from both the enrolled customers who file claims and the marketing costs incurred in acquiring new customers.

- **FP**: Meanwhile, the loss for situations where customers do not make a claim but are erroneously identified as claimants is 4000 SGD. This amount represents the average insurance coverage cost for these customers.

**We need to use fscore metrics with beta 1/5, this is because the precision value is 5x more important than the recall value**
