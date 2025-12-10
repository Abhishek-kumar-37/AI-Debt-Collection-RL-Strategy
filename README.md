# RL-project-debt-collection
reinforcement learning for optimal debt collection strategy

Note that the trajectory_new.csv here is not the original file due to the limit of file size that is allowed to upload to github. It is a sample. 

# AI Debt Collection Strategy using Reinforcement Learning

This project demonstrates how Reinforcement Learning (RL) can be used to optimize debt 
collection strategy for financial institutions. An AI agent learns which action to take 
(reminder, call, settlement offer, wait, escalate etc.) to maximize repayment while 
reducing collection effort and cost. This approach aligns closely with modern fintech 
debt recovery systems such as **CredResolve**.

---

## 🚀 Project Features

- RL model for automated debt collection decision-making
- Learns best action sequence to improve recovery outcomes
- Supports **loan-level** & **installment-level** simulation
- Transfer Learning (TL) framework for scaling to new loan portfolios
- Uses sample dataset (`trajectory_new.csv`) for demonstration

---

## 🧠 Business Use Case

Banks, NBFCs, lending apps & fintech recovery platforms can use this model to:

- Predict borrower repayment behavior
- Prioritize delinquent accounts efficiently
- Reduce manual effort & recovery cost
- Increase overall debt recovery percentage
- Deploy AI-driven reminder/call/settlement strategies

---

## 📄 Dataset

The file `trajectory_new.csv` is a **sample version** of the original dataset due to heavy 
file size limitations. However, it fully demonstrates how trajectories are processed to 
create episodes for RL training.

---

## 🔧 How to Run

### Loan-level episode generation
```bash
python3 run_test.py


run the following code if you want to construct an episode at loan level
```
python3 run_test.py
```

run the following code if you want to construct an episode at installment level
```
python3 run_installment_test.py
```

run the following code if you want to obtain the translators for TL:
```
python3 translation.py
```

run the following code if you want to test the TL framework
```
python3 run_test_TL.py
```
