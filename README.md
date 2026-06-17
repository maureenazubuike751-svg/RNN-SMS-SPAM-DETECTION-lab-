# RNN-SMS-SPAM-DETECTION-lab-
Rnn sms spam detection 
# RNN SMS Spam Detection

## Dataset
Mock SMS dataset with 5000 messages (50% ham, 50% spam)

## Model
- Embedding layer (32 dimensions)
- Two LSTM layers with Dropout (0.2)
- Dense layer (16 units, ReLU)
- Sigmoid output

## Results
- Accuracy: ~98%
- Precision: ~98%
- Recall: ~98%

## Deployment
- 95% confidence threshold
- API endpoint for classification
- User opt-in/out

## Trade-offs
- Precision prioritized over Recall
- False Positives minimized (avoid blocking important messages)
