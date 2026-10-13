# 기초 문법 정리

딥러닝 코드를 읽기 위한 기초 문법을 주제별로 정리한 노트북 · 현재 7개 공개

| 정리 | 내용 |
| :-- | :-- |
| [01_Python 문법](01_Python%20문법/Python%20문법_전체%20정리.ipynb) | 기초 문법 22문제를 7개 대단원 · 20개 섹션으로 재구성 (변수 · 리스트 · 딕셔너리 · 함수 · 문자열 · 파일 · JSON), 폴더 속 이미지로 학습용 목록을 만드는 종합 실습 |
| [02_Python 클래스](02_Python%20클래스/Python%20클래스_전체%20정리.ipynb) | 클래스 수업 노트북 4개를 4개 대단원 · 12개 섹션으로 재구성 (클래스 · self · 특수 메서드 · 상속 · super), PyTorch `Dataset` · `nn.Module`을 직접 만드는 종합 실습 |
| [03_NumPy](03_NumPy/NumPy_전체%20정리.ipynb) | 강의자료를 뼈대로 연습문제 27문제를 7개 대단원 · 24개 섹션으로 재구성 (배열 · 모양 · 인덱싱 · 조건 · 계산 · 정렬과 축 · broadcasting), 신메뉴 수익 분석 종합 실습, 9장 딥러닝 데이터로 연결 (정규화 · HWC → CHW · 배치 · seed · 시계열 윈도우) |
| [04_Pandas](04_Pandas/Pandas_전체%20정리.ipynb) | 수업 노트북 3개의 빈칸 48칸을 풀어 7개 대단원 · 23개 섹션으로 재구성 (표 살펴보기 · 선택 · 조건 · 계산과 정렬 · 결측 · 날짜 · 중복 정리 · groupby · merge), 처음 보는 판매 데이터 종합 실습, 9장 딥러닝 데이터로 연결 (라벨 → 번호 map · astype · concat · 날짜 index · resample · rolling · shift · to_numpy) · 실행에 쓴 수업 CSV(`data/`)는 올리지 않음, 결과는 저장된 출력으로 확인 |
| [05_머신러닝 -1](05_머신러닝/머신러닝-1_데이터분할·교차검증%28완성본%29.ipynb) | 머신러닝 intro + model_selection 노트북(빈칸 32칸을 직접 풀어 실행으로 검증)을 5개 대단원 · 15개 섹션으로 재구성 (fit · predict · score · 학습 데이터 채점 착시 · train_test_split · stratify · KFold vs StratifiedKFold · cross_val_score vs cross_validate · 모델 비교 mean ± std · 과적합 · GridSearchCV vs RandomizedSearchCV · 최종 test 1회 · train · val · test 3분할), 펭귄 품종 분류를 분할부터 최종 test까지 처음부터 끝까지 하는 종합 실습 |
| [06_딥러닝기초 · PyTorch -1](06_딥러닝기초·PyTorch/딥러닝기초-1_텐서·경사하강%28완성본%29.ipynb) | 개론 PDF(퍼셉트론 · 손실 · 경사) + Day01 강의 + Day01 연습문제 P01 ~ P15를 7개 대단원 · 21개 섹션으로 재구성 (텐서 · shape · dtype · device · view/reshape · squeeze · cat/stack · broadcasting 함정 · 행렬 곱 · MSE · autograd · 경사하강 · 학습률), 직접 만든 선형 회귀를 경사하강으로 학습하고 학습률 3가지(느림 · 적절 · 발산)를 비교하는 종합 실습 · GPU가 없어도 실행 |
| [12_세그멘테이션 -1](12_세그멘테이션/세그멘테이션-1_픽셀분류·U-Net%28완성본%29.ipynb) | 코드잇 Segmentation PDF(Semantic · FCN · U-Net) + 위클리 9(분할 부분)를 4개 대단원 · 10개 섹션으로 재구성 (분류 vs 탐지 vs 의미 · 인스턴스 분할 · 출력 (N, C, H, W) · long 마스크 vs one-hot · 픽셀 CE · ignore_index · nearest vs bilinear vs ConvTranspose2d vs Upsample+Conv · FCN 1×1 합성곱 · U-Net 모양 추적 손계산 · skip 연결 cat vs 더하기 · 픽셀 정확도 vs mIoU vs Dice 손계산 · CE vs Dice 손실), skip만 다른 U-Net 2개를 같은 조건으로 학습해 mIoU · Dice · 경계 정확도를 비교하는 종합 실습 · 수업 실행 코드가 없어 코드는 모두 보강, 데이터는 노트북 안에서 그린 도형(내려받기 없음) · GPU가 없어도 실행 |

**섹션 구성** · 🎯 질문 → 💡 쉬운 설명 → 실행 흐름 → 먼저 예측 → 코드 → 예측 정답 · 결과 해설 → 차이 · 언제 쓰나 → ⚠️ 주의 → ✅ 한 줄 정리

**마무리** · 백지 복습 → 면접 30초 답변 → 전체 코드 → 전체 최종 요약표
