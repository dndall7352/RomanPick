# RomanPick - Signal
## 1. 프로젝트 개요
주제 : 콘텐츠 기반 유사도 추천 시스템을 사용한 로맨스 웹소설 추천 서비스, RomanPick
 - 로그인 없이 좋아하는 단어, 문학책, 감정 기반으로 웹소설을 추천받을 수 있는 서비스
 - 주요 기능
   - 클러스터링을 통한 RomanPick만의 카테고리화 추천
   - 드래그앤드롭, ISBN 입력, 카메라 촬영을 통한 해당 문학책과 유사한 로맨스 웹소설 추천
   - 기쁨, 당황, 상처, 슬픔, 불안, 분노의 리뷰 감정 분석을 통한 추천
팀명 : Signal
팀원 : 박혜진(팀장, 감정 분석(Koelectra)),
       백용훈(Back-end, 바코드 이미지 인식(cv2, pyzbar)),
       오소아(Front-end),
       이동수(텍스트 임베딩(SentenceTransformer), 클러스터링(K-means)),
       김태경(Front-end),
       서승현(텍스트 임베딩(SentenceTransformer), 클러스터링(K-means))
총 프로젝트 기간 : 2023.05.29 ~ 2023.06.22

uvicorn main:app --reload main.py 실행 명령어

https://www.microsoft.com/ko-KR/download/details.aspx?id=40784
pyzbar(바코드 인식) 쓰기 위한 visual studio 2013 설치 필수
