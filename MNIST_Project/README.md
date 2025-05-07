# 📝 Supervised Learning Assignment Checklist – MNIST CNN (Spring 2025)

## 👥 Team Members
- Member 1: Ammar Mohamed   (20220216)
- Member 2: Ahmed Abdelaziz (20220025)
- Member 3: Marwan Osama    (20220324)
- Member 4: Rana Helal      (20220131)

---


## 📆 Day 1 – May 7: Setup & Baseline Models
- [✅] Set up shared Google Colab notebook
- [✅] Load MNIST dataset (shape 28x28)
- [✅] Shuffle dataset
- [✅] Implement basic ANN
- [✅] Implement SVM
- [✅] Document accuracy, layers, params, train/test time for both

---

## 📆 Day 2 – May 8: Base CNN + Epoch Tuning
- [ ] Implement CNN with 3 layers (include Conv2D + MaxPooling2D)
- [ ] Use ReLU, SGD, no dropout
- [ ] Test different epoch values (10–25)
- [ ] Log results: accuracy, params, time, layers
- [ ] Choose best epoch count

---

## 📆 Day 3 – May 9: Learning Rate Testing
- [ ] Fix best epoch from May 8
- [ ] Test learning rates (e.g., 0.01, 0.001, 0.0001)
- [ ] Document impact on performance
- [ ] Select optimal LR

---

## 📆 Day 4 – May 10: Model Architecture Variation
- [ ] Test models with different Conv/FC layers (3 Conv max, 4 FC max)
- [ ] Aim for high accuracy with fewer params
- [ ] Document 4+ different configs
- [ ] Capture full Segment B data

---

## 📆 Day 5 – May 11: Batch Sizes & Activations
- [ ] Try 2 new batch sizes (e.g., 128, 192)
- [ ] Test 3 new activations (include sigmoid)
- [ ] Compare performance metrics
- [ ] Finalize best batch size and activation

---

## 📆 Day 6 – May 12: Optimizers + Dropout
- [ ] Test 2 new optimizers (e.g., Adam, RMSProp)
- [ ] Add dropout layers in 2 positions
- [ ] Try 2 rates (e.g., 0.25, 0.5)
- [ ] Analyze regularization effect

---

## 📆 Day 7 – May 13: Final Model & Report Writing
- [ ] Choose best overall model
- [ ] Document why it's best (final analysis)
- [ ] Start report (Word format first)
- [ ] Add graphs, stats, insights
- [ ] Ensure all members can run the notebook independently

---

## 📆 Day 8 – May 14: Final Checks & Submission
- [ ] Final proofreading of report
- [ ] Convert Word report to PDF
- [ ] Save notebook as id1_id2_id3_id4_id5.ipynb
- [ ] Save report as id1_id2_id3_id4_id5.pdf
- [ ] Submit files as required

---

## 📌 Notes
- [ ] All models include Segment B stats
- [ ] All observations per Segment C noted
- [ ] Follow constraints (dropout < 85%, batch size ≤ 250, FC ≤ 512, kernel ≤ 5x5)
- [ ] Use Google Colab with GPU enabled
