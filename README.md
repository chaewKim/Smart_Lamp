## 졸업작품
1. 프로젝트명 : 스마트 램프
2. 개요 : Flask, OpenCV, PyThorc 그리고 HumanFallDetection APi를 활용하여 넘어짐을 감지하고 사용자에게 이를 알리는 웹서비스를 만들어 넘어짐 사고를 보다 빠르게 감지하여 안전을 보장하기 위해 설계되었다.
3. 개발환경
- 운영체제 : Windows 10
- 개발 언어 : Python, C, HTML& javascript
- 사용하는 IDE : Pycharm, Visual Studio

4. 시스템 수행 시나리오

-시스템의 동작 방식은 먼저 좁은 골목길에서 보행자가 인식이 되면 아두이노의 PIR 센서가 사람을 인식하여 조명을 밝힌다. 그 후 5초의 시간이 흐르면 자동으로 LED가 꺼진다.
본 연구에서는 범죄 상황의 정의를 사람이 쓰러진 순간으로 정의를 하였고 가로등 밑을 지나가는 순간 범죄 상황이 발생하여 사람이 쓰러짐을 인식하게 되면 관제 센터에서는 실시간으로 경고문과 함께 상황을 볼 수 있다.

 ![image](https://github.com/user-attachments/assets/733fa327-890a-4db4-8ec3-804bcde1bbf2)

5. 주요 기능
-실시간 넘어짐 감지
  -OpenCV로 카메라 영상 스트리밍 처리
  -PyTorch 모델을 활용한 넘어짐 감지
-알림 시스템
  -넘어짐 감지되면 화면에서 경고 발생
-웹 인터페이스
  -Flask를 통한 사용자 친화적인 대시보드 제공
  -감지 결과 실시간 확인 가능 

7. 범죄 상황 인지 플로우 차트

   -사람이 쓰러진 경우
   
   ![image](https://github.com/user-attachments/assets/d9a2a83a-7bcf-406d-9392-bb35d3e9e37e)


8. 결과

   -범죄상황이 아닌 경우(쓰러지지 않은 경우)
   
![image](https://github.com/user-attachments/assets/c1759172-f744-4d47-98ca-db0173ca5e62)



   -범죄상황 발생 후 사람이 쓰러짐을 인식한 후

  ![image](https://github.com/user-attachments/assets/0c4dca0d-2415-442b-a3b0-6a33649f1353)

# 프로젝트 보고서 
[보고서 PDF 다운로드](./Smart%20Lamp%20최종보고서.pdf) <br>
[논문 PDF 다운로드](./졸업논문.pdf)

