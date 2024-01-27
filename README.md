# AndroidScreenShare2
AndroidScreenShare 어플 
참고 : <https://github.com/lesa1127/AndroidScreenShare>

# 디자인
![캡처](https://github.com/mmg1111-spec/AndroidScreenShare2/assets/93562291/e0c2a214-bfdd-4b78-ba38-f93315d0ce50)
![캡처2](https://github.com/mmg1111-spec/AndroidScreenShare2/assets/93562291/d3d985ab-2596-44aa-a19d-55c44b9221d2)
-  참고한 어플에서 디자인을 수정하고, 기능을 추가하였다.


# 추가한 기능
 ### 아이콘 같은 이미지 버튼을 추가하여 각각 버튼을 눌렀을때 기능을 하도록 추가하였다.
 #### 와이파이 : 안드로이드 내에 와이파이 설정으로 들어가는 기능 
   ![GIF 2024-01-27 오전 10-01-55](https://github.com/mmg1111-spec/AndroidScreenShare2/assets/93562291/6e87d989-ae21-499c-ba15-9f7689048f42)
 #### 물음표 : Viewpager2를 이용해 각 페이지에 어플을 사용하는 방식을 보여주는 가이드 역할을 하도록 하는 기능
 ![GIF 2024-01-27 오전 10-02-12](https://github.com/mmg1111-spec/AndroidScreenShare2/assets/93562291/868ea025-9761-4a06-ad4b-5ae118407045)
 #### 톱니바퀴 : 설정 역할을 하는 기능(공유, 피드백, 리뷰)
 ![GIF 2024-01-27 오전 10-02-29](https://github.com/mmg1111-spec/AndroidScreenShare2/assets/93562291/2a4f091d-56b0-4d04-9c9b-be697ff117aa)
 #### WIFI-IP 주소 : 버튼을 눌렀을 떄 와이파이에 접속되어 있다면 IP가 나오고, 와이파이 접속이 안되어있다면 와이파이 연결이 안되어있다고 토스트 메시지로 나오게 하는 기능
 ![GIF 2024-01-27 오전 10-02-48](https://github.com/mmg1111-spec/AndroidScreenShare2/assets/93562291/a0b3975a-d61d-4d24-8723-f0718704f583)


 # 실행
 ![GIF 2024-01-27 오전 10-11-12](https://github.com/mmg1111-spec/AndroidScreenShare2/assets/93562291/a0b01c05-ba87-4d45-8076-1bc0c21a9055)
 - 화면 공유 버튼을 시작하면 매개변수 설정 버튼이 안보이도록 구현하였다.
 - 공유하는 서버 기기에서 공유 중지 버튼 클릭시 클라이언트 기기에서 토스트 메시지로 종료되었다고 나오게 구현하였다.
 - sdk버전을 올리면서 공유할때 알람이 나오는 기능은 잘 되었지만, 공유 중지할시 알람이 삭제되는 기능이 잘 안되었지만 버튼을 추가하여 생성된 알람이 삭제되도록 구현하였다.

 # 소스 코드
 AndroidScreenShare2 소스코드 : <https://drive.google.com/file/d/1wV84QflBjCWqVHvFfrblF98zjRnGapnZ/view?usp=drive_link>
