
# Machine-Learning-on-Real-Time-Data-with-Streaming-Dataset
• Built a lightweight online ML model that predicts NIFTY-50 price movements from daily streaming data, allowing
real-time adaptation to new market information.
• Used Python stack (pandas, numpy, matplotlib, scikit-learn) with online Stochastic Gradient Descent (SGD) and an
optional block-SGD variant; features: open/high/low/close, volume, turnover, and temporal features
(day/month).
• Computationally efficient for real-time use - achieved test MSE ≈ 0.08 (20% test split); block-based updates reduce
variance and improve stability while keeping CPU/memory requirements low.
