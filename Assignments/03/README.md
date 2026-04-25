## **deep learning for perception - assignment 03**
### _individual epoch outputs_

#### **epoch 1**
<img width="266" height="266" alt="epoch_01" src="https://github.com/user-attachments/assets/5055507b-80ba-4dcb-b775-5fe2589c2aa3" />

#### **epoch 2**
<img width="266" height="266" alt="epoch_02" src="https://github.com/user-attachments/assets/a2cc7f97-c414-4b04-aacc-8610b2883024" />

#### **epoch 3**
<img width="266" height="266" alt="epoch_03" src="https://github.com/user-attachments/assets/5d4303a4-bfdf-4c59-87b3-3259d3cb0166" />

#### **epoch 4**
<img width="266" height="266" alt="epoch_04" src="https://github.com/user-attachments/assets/4975d4e0-0640-404d-94c3-a0e300949660" />

#### **epoch 5**
<img width="266" height="266" alt="epoch_05" src="https://github.com/user-attachments/assets/19f68e90-8d99-415e-b7a7-8b6b4751ec35" />

#### **epoch 6**
<img width="266" height="266" alt="epoch_06" src="https://github.com/user-attachments/assets/4f9d9b79-3446-4abf-943f-e9d68cd51772" />

#### **epoch 7**
<img width="266" height="266" alt="epoch_07" src="https://github.com/user-attachments/assets/d2767f7d-d869-4fb6-a7d0-092c0c3917d4" />

#### **epoch 8**
<img width="266" height="266" alt="epoch_08" src="https://github.com/user-attachments/assets/7838613c-e021-47d9-aeaa-50372f7eb998" />

#### **epoch 9**
<img width="266" height="266" alt="epoch_09" src="https://github.com/user-attachments/assets/6d7a9a79-97b6-42f6-afa6-082fbf413d72" />

#### **epoch 10**
<img width="266" height="266" alt="epoch_10" src="https://github.com/user-attachments/assets/a065521a-afc9-48df-b2e8-14577e3744a8" />

#### **epoch 11**
<img width="266" height="266" alt="epoch_11" src="https://github.com/user-attachments/assets/f5f44f5f-5864-4026-8a82-57debf3482bc" />

#### **epoch 12**
<img width="266" height="266" alt="epoch_12" src="https://github.com/user-attachments/assets/cc50f5ca-4e7e-451f-98b9-935cef62de6f" />

#### **epoch 13**
<img width="266" height="266" alt="epoch_13" src="https://github.com/user-attachments/assets/b9a6f13d-87fc-4d8d-87c3-384c9c0b4b2e" />

#### **epoch 14**
<img width="266" height="266" alt="epoch_14" src="https://github.com/user-attachments/assets/ea2ece49-335e-4c31-bf09-be80d8555c62" />

#### **epoch 15**
<img width="266" height="266" alt="epoch_15" src="https://github.com/user-attachments/assets/8cf2d4aa-843a-4a74-9569-d2e427e40396" />

#### **epoch 16**
<img width="266" height="266" alt="epoch_16" src="https://github.com/user-attachments/assets/88cee072-fa2a-4e92-9be5-ba5ee45a58ee" />

#### **epoch 17**
<img width="266" height="266" alt="epoch_17" src="https://github.com/user-attachments/assets/a4e73a01-ec84-4d18-b1fb-bcc2320dd5c5" />

#### **epoch 18**
<img width="266" height="266" alt="epoch_18" src="https://github.com/user-attachments/assets/c47bb9ee-b6e5-4eae-971e-f991cb644b07" />

#### **epoch 19**
<img width="266" height="266" alt="epoch_19" src="https://github.com/user-attachments/assets/347a4363-050d-4403-a95a-fd9310fa8eda" />

#### **epoch 20**
<img width="266" height="266" alt="epoch_20" src="https://github.com/user-attachments/assets/eb8c395f-a380-4db3-b11d-d75d617b53ca" />

#### **epoch 21**
<img width="266" height="266" alt="epoch_21" src="https://github.com/user-attachments/assets/da820e00-62df-4991-84ab-54ad26657945" />

#### **epoch 22**
<img width="266" height="266" alt="epoch_22" src="https://github.com/user-attachments/assets/7ed79224-a01c-4322-895e-910707284c01" />

#### **epoch 23**
<img width="266" height="266" alt="epoch_23" src="https://github.com/user-attachments/assets/41e19bcd-e8e4-4b63-83de-1184f03a54ed" />

#### **epoch 24**
<img width="266" height="266" alt="epoch_24" src="https://github.com/user-attachments/assets/7e23993c-d809-4d16-921a-ed0b0e83ea57" />

#### **epoch 25**
training produced clear, recognizable digits from epoch 1 onwards, with quality improving steadily up to epoch 24. however, at epoch 25 the generator collapsed and began producing noise. this is apparently a known GAN failure mode where the discriminator loss dropped extremely low (like around ~0.003) while the generator loss spiked to around ~7.6, meaning the discriminator became too strong and the generator could no longer receive useful gradients to learn from. best results were observed at epoch 24, which is used as the final output.
<img width="266" height="266" alt="epoch_25" src="https://github.com/user-attachments/assets/661f6bac-7c90-4674-8773-01aacbeff6e9" />

#### **best final generated**
<img width="2100" height="2100" alt="final_generated" src="https://github.com/user-attachments/assets/4d2a623a-f3ce-481b-8c3c-35f9086561d5" />

#### **training loss**
<img width="1200" height="750" alt="training_loss" src="https://github.com/user-attachments/assets/5a16045d-0140-44cc-9bb1-fbfecbf5ec7d" />

