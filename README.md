# Energy usage prediction and anomaly detection
0. 전력 사용량 데이터세트 생성<br>
1. 공간단위 에너지 사용량 예측<br>
2. AutoEncoder 복원 에러 기반 상치 탐지<br>

## MakeDataset References
“전남대학교 바로고치미” 
https://sisul.jnu.ac.kr/sisul/13422/subview.do.
“공공데이터포털-한국전력거래소 광주시 일별 시간대별 전력거래량”
https://www.data.go.kr/data/15104326/fileData.do.
“기상자료개방포털-광주시 시간대별 온도, 습도 데이터”
https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36.
“국가통계포털-산업별(표준산업코드 중분류) 월별 시간대별 전력소비 계수” 
https://kosis.kr/index/index.do

## EnergyPredict References
ConvLSTM
Shi, Xingjian, et al. "Convolutional LSTM network: A machine learning approach for precipitation nowcasting." Advances in neural information processing systems 28 (2015).
PredRNNv2
Wang, Yunbo, et al. "Predrnn: A recurrent neural network for spatiotemporal predictive learning." IEEE Transactions on Pattern Analysis and Machine Intelligence 45.2 (2022): 2208-2225.
PhyDNet
Guen, Vincent Le, and Nicolas Thome. "Disentangling physical dynamics from unknown factors for unsupervised video prediction." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2020.
SimVP
Gao, Zhangyang, et al. "Simvp: Simpler yet better video prediction." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022.
CBAM
Woo, Sanghyun, et al. "Cbam: Convolutional block attention module." Proceedings of the European conference on computer vision (ECCV). 2018.

## AnomalyDetection References
LSTM autoencoder
Srivastava, Nitish, Elman Mansimov, and Ruslan Salakhudinov. "Unsupervised learning of video representations using lstms." International conference on machine learning. PMLR, 2015.
GRU
Cho, Kyunghyun, et al. "Learning phrase representations using RNN encoder-decoder for statistical machine translation." arXiv preprint arXiv:1406.1078 (2014).
TCN
Bai, Shaojie, J. Zico Kolter, and Vladlen Koltun. "An empirical evaluation of generic convolutional and recurrent networks for sequence modeling." arXiv preprint arXiv:1803.01271 (2018).