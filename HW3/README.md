**算法公式（LaTeX**<br>
1.Epsilon-Greedy:<br>
![image](https://github.com/user-attachments/assets/a4232d15-ab5c-4bf2-adf2-d187dbc71339)
2.UCB (Upper Confidence Bound)<br>
UCB 演算法會在選擇 arm 時考慮兩個部分：當前的平均獎勵與置信區間（用來表示不確定性）。選擇讓「平均獎勵 + 不確定性」最大的 arm，自動平衡探索與利用。<br>
![image](https://github.com/user-attachments/assets/a66e6e6e-4de3-43f5-a1c4-7f6ebde40a2b)
3.Softmax<br>
Softmax 使用機率分布來選擇 arm，將高期望報酬的 arm 設定為較高的選擇機率，使用溫度參數控制探索程度（溫度高表示更隨機，溫度低表示更貪婪）。<br>
![image](https://github.com/user-attachments/assets/edbc6e61-8773-4bd7-9e3a-9299a68f6f50)
4.Thompson Sampling



