---
layout: single
title: "Research"
permalink: /research/
author_profile: true
classes: wide
---

## 📄 KCI 등재 논문 · 제1저자

**Grad-CAM++ 기반 보조 히트맵 입력을 활용한 경량 얼굴 인식 모델의 강건성 향상**

![KCI 논문](/assets/images/paper1.png)

경상국립대학교 IDEA Lab 학부연구생으로 수행한 연구입니다.

**연구 배경**
경량 얼굴 인식 모델은 조명 변화 및 가림 환경에서 성능 한계가 있었습니다. 모델 구조를 바꾸지 않고도 성능을 향상시킬 수 있는 방법을 연구했습니다.

**핵심 기여**
- 기존 RGB 입력에 Grad-CAM++ 기반 Heatmap을 4번째 채널로 결합하는 보조 입력 구조를 **독자적으로 설계**
- MobileNetV3, ShuffleNetV2, EfficientNetB0 등 경량 모델에 적용
- Zero, Random, Shuffle Ablation Study를 통해 성능 향상이 단순 채널 수 증가가 아닌 Heatmap 신호 자체의 기여임을 공학적으로 입증

**성과**

| 지표 | 결과 |
|------|------|
| F1-score 향상 | **최대 11.2%p** |
| 수렴 속도 | **Epoch 3 이내** |
| AUC (ShuffleNetV2) | **0.8372** |

[📄 논문 보기](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12563682){: .btn .btn--primary}

---

## 📄 HCI Korea 2026 · 제1저자

**역할 기반 데이터셋과 RAG 결합 시스템프롬프트를 활용한 한국어 자기소개서 기반 면접 질문 생성**

![HCI 논문](/assets/images/paper2.png)

캡스톤 프로젝트 '면접의 정석'에서 개발한 면접 질문 생성 기능을 학술적으로 고도화한 연구입니다.

**연구 배경**
기존 면접 질문 생성 모델은 지원자의 직무, 기업 인재상, 페르소나를 반영하지 못해 일반적인 질문만 생성되는 한계가 있었습니다.

**핵심 기여**
- 직무·기업 인재상·지원자 페르소나를 반영한 Role Prompt 기반 데이터셋 약 **3,000건 직접 구축**
- Chain-of-Thought, Few-shot, Retrieval 등 **5가지 프롬프트 기법 비교 실험**
- Role Prompt가 METEOR 및 BERTScore 기준으로 가장 우수함을 검증
- BM25와 SBERT 임베딩을 결합한 **Hybrid RAG 설계**

**성과**

| 지표 | 결과 |
|------|------|
| KoBART 학습 손실 | **1.97 → 0.55** |
| BLEU | **기존 대비 약 2배 향상** |
| Coverage | **0.49 → 0.67** |
| Groundedness | **0.05 → 0.29** |
| Distinct-2 | **0.58 → 0.78** |

[📄 논문 보기](/assets/papers/hci2026.pdf){: .btn .btn--primary}

---

## 📄 KIIT Conference · 3저자

**Dog vs Not-Dog 이진 분류 기반 실종견 탐색 딥러닝 모델 비교 연구**

![KIIT 논문 1](/assets/images/paper3.png)

반려견 견종 분류 프로젝트 '추견 60분'을 함께 개발한 팀원으로서, 데이터셋 구축과 모바일 앱 개발에 기여한 연구입니다.

**연구 개요**
Dog vs Not-Dog 이진 분류를 위한 딥러닝 모델 성능을 비교하고, 실종견 탐색 애플리케이션에 적용하는 것을 목표로 했습니다. 총 25,124장의 이미지로 5-Fold 교차 검증을 수행하고 6개 모델을 비교 평가했습니다.

**나의 기여**
- 반려견 분류 프로젝트에서 구축한 이미지 데이터셋 공유
- React Native 기반 모바일 앱 프론트엔드 및 백엔드 개발 참여

**주요 결과**

| 지표 | 결과 |
|------|------|
| 최고 성능 모델 | **EfficientNet-B0** |
| Accuracy | **0.9927** |
| AUC-ROC | **0.9996** |
| 통계적 유의성 | **p < 0.0001** |

[📄 논문 보기](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12545404){: .btn .btn--primary}