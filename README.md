# AIFFELTON

팀프로젝트로 진행되는 AIFFELTHON의 파일을 업로드 하는 저장소 입니다. 

***
### 팀명: 김장

### 프로젝트 목표: 리뷰 챗봇을 통한 리뷰의 질 개선

### 프로젝트 기간: 2022. 08.16 ~ 2022. 09.26

### 팀원: 김건국 / 김영래 / 장한영

***
# ⚔️ 1. 프로젝트 설명

배달 플랫폼의 경우 소비자들은 리뷰를 통해 해당 음식점의 정보를 얻는다.  
단순한 또는 무성의한 리뷰는 소비자들로 하여금 정보를 얻는데 제한이 있다.  
팀에서 설정한 음식 리뷰의 3요소(맛,양(서비스),배달)를 충족시키는 리뷰를 작성하도록 권고함으로 인해   
리뷰의 질을 개선하고 새로운 음식점을 접하는 소비자가 정보 취득하기 용이하게 한다.  
  
또한, 소비자가 작성한 리뷰에 대해 감정분석을 통해 판매자가 전체 리뷰를 검토하는 것이 아닌  
긍정리뷰 또는 부정리뷰만 판별할 수 있도록 리스트를 제공 한다.

***
# 📈 2. Flow Chart

***

# 📱 3. 사용 모델 및 데이터셋

- 사용 모델 : Klue-Bert을 통한 3요소 분류와 감정분석
- 데이터셋 : 크롤링 데이터셋 + 모두의 말뭉치 데이터셋 
- 웹 구현 : Streamlit
- 프레임워크 : Pytorch 


***
# 🎓 4. 프로젝트 진행 과정

- **데이터 수집 및 레이블링** : 08.16 ~ 08.28
  * 데이터 크롤링 
  * Active Learning을 통한 레이블링

- **모델 구축 및 학습** : 08.29 ~ 09.16
  * MLM Task를 통한 모델 고도화
  * WandB Sweep을 통한 Hyper Parameter 최적화
 
- **Streamlit 학습** : 08.31 ~ 09.11
- **Streamlit 구현** : 09.12 ~ 09.23
  * 웹 구현 및 CSS를 통한 디자인

***
# 🎬 5. 시연 영상
