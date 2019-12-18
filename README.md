# DQN-improvement
各式DQN衍生的演算法。    
此為強化式機器學習練習，參考https://github.com/GAOYANGAU/DRLPytorch 與 https://github.com/rlcode/per。

# DDPG(Deep Deterministic Policy Gradient)
參考https://github.com/GAOYANGAU/DRLPytorch    
DDPG算法是model free, off-policy的，且使用了深度神經網絡。    

- DQN只能解決離散且維度不高的action spaces的問題。是value based方法，只有一個值函數網絡。
- DDPG可以解決連續動作空間問題。是actor-critic方法，即既有值函數網絡(critic)，又有策略網絡(actor)。
