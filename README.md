# webapp_yolo
ㅇㅣ 프로그램은 yolov5.pt 원형 모델을 이용하여 
Object Detect를 하는 파이썬 프로그램을 하였고 
파이썬 코드를 index.html로 바꾸어 달라고 coPilot을 이용해서 진행 하였다. 


#수업자료 #robot

#20250409

#로봇반진도



1. 인공지능의역사

파일

05. 인공지능의 역사_이미지인식분야.pptx


2. colab이란?

https://colab.research.google.com/drive/1l-TeKSPZZ2Hrf_3c2fpNqqN_5Vwt1m9l?usp=sharing

삭제
05_colab init.ipynb
Colab notebook
colab.research.google.com

3. 객체탐지와 Yolo in coLAB

https://colab.research.google.com/drive/151tO9qmmV6RowgXiQX-W7yMH3f4hMWJI?usp=sharing

삭제
Google Colab Notebook
Run, share, and edit Python notebooks
colab.research.google.com

4. 파이썬으로 사물인식 앱 만들기



 4.1 폴더 만들기 - code로 열기 - 터미널 열고

 4.2 가상환경 만들기

 4.3 가상환경과 프로젝트 연결하기

 4.4 코파일럿과 작업

copilot-edit에 입력ㅎㅏ는 프롬프트는 다음과 같다

"

파이썬과 opencv로  yolov5 모델을 이용해서 웹카메라로 사물인식하는 간단한 코드를 작성해줘

"

코드 공유 함.

(yolov5s.pt를 자동 다운로드 함)



파일

webcam_yolo_gui.py


youtube에서 동영상을 다운로드 받을려면

pip install yt-dlp 가 있어야 하고



yt-dlp -f mp4 -o "youtube_video.mp4" https://youtu.be/JfCE2MRFEGA?si=eMNIAFRhDFgH2nbG

삭제
SAN FRANCISCO - Rainy Day Street Walk in Downtown San Francisco, California, USA, Travel, 4K UHD
SAN FRANCISCO - Rainy Day Street Walk in Downtown San Francisco, California, USA, Travel, 4K UHDSAN FRANCISCO - 비오는 날, 도시풍경, 다운타운 샌프란시스코, 캘리포니아, 미국, 여행, 거리풍경...
www.youtube.com

이 명령으로 해당 주소의 동영상을 다운로드 받을수 있음 .



프롬프트는 이렇게 작성했어.

"

원래 코드를 내가 다운로드 받아 놓은 youtube_video.mp4를 플레이 하면서 디택션 하는 코드를 작성해서 youtube_detext.py에 저장하고 플레이가 종료 되면 반복 되도록 만들어줘

"



결과물은 이렇게





오늘 수업 마지막으로 

프롬프트를 이렇게 해서 

자 이번엔 웹카메라와 파이썬 코드로 되어 있는 것을 웹에서 구동 할 수 있게 iindex.html로 만들어줘

결과를 한번 보자 
