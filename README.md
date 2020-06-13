# DFC605-16
DFC605-16

제목 : 고려대학교 로고를 찾아라.<p>
목표 : 많은 로고들 중에 고려대학교의 로고를 CNN을 통하여 쉽게 찾을 수 있도록 함.<p>
중점학습 : MNIST같이 학습할 수 많은 데이터 이미지를 확보하지 않고(최소 5000개 이상) 적은수의 샘플을 통하여 이미지를 배치화 하여 샘플링데이터를 증가시키고 그것을 통하여 학습하고자 함.<p>

<img src = "data:image/png;base64,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"></img>
