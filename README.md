<h1>이력서</h1>   
<h2>소개</h2>                                                                                                                                 
<ul>
  <img src="https://user-images.githubusercontent.com/37283294/48554860-e4b49580-e922-11e8-99cc-a022c4c6cc17.jpg"/>
  <li>이름 : 김동영</li>
  <li>성별 : 남</li>
  <li>생년월일 : 1994.02.18</li>
  <li>Email : dongyoung0218@gmail.com</li>
  <li>github : https://github.com/DONGYYYYY</li>
</ul>

<h2>학력사항</h2>
<ul>
  <li>한림대학교 재학 ( 2012 ~ 2018 )</li>    
</ul>

<h2>사용 기술</h2>
<ul>
  <li>C</li>
  <li>+OpenCV</li>
  <li>JAVA</li>
  <li>+Android Studio</li>
  <li>C++</li>
  <li>Python</li>
  <li>Linux</li>
  <li>Raspberry PI</li>
  <li>Arduino</li>
  <li>MySQL</li>
</ul>

<h2>프로젝트</h2>

<ol>
  <h3><li>캡스톤 디자인</li></h3>
  <ol>
    <li>차단기(서보 모터) / 차량 주차 여부(초음파 센서) / 장애인 차량 파악(HM-10블루투스 모듈을 활용한 비콘) / 주변에 장애인차량 존재 여부 파악(제누이노101을 활용한 비콘 탐색)</li>
        <li>Raspberry Pi : 아두이노에서 장애인차량의 MAC ADDRESS파악 후 장애인 차량 MAC　ADDRESS를 가지고 있는 DataBase와 비교 초음파 센서를 통한 주차 여부를 주차 DataBase에 저장( PHP를 활용하여 주차 여부 갱신 확인 ) </li>
<!--         <ul>
        <img src="https://user-images.githubusercontent.com/37283294/48555389-6822b680-e924-11e8-9cbe-b82be120b511.png"/><br>
        그림 1. 일반차량 접근시
        </ul>
        <ul>
        <img src="https://user-images.githubusercontent.com/37283294/48555395-6a851080-e924-11e8-8488-25d49ba36f62.png"/><br>
        그림 2. 장애인차량 접근시
        </ul>
        <br> -->
        <li>에지 검출과 템플릿 매칭을 활용한 차선 침범 여부 파악 (직선 값의 변화를 파악을 통한 침범 판단) </li>
<!--         <ul>
        <img src="https://user-images.githubusercontent.com/37283294/48555399-6e189780-e924-11e8-893b-51aada1bcf4b.png"/><br>
        그림 3. 에지 검출한 동영상
        </ul>
        <ul>
        <img src="https://user-images.githubusercontent.com/37283294/48555403-707af180-e924-11e8-83b8-d7370f75e560.png"/><br>
        그림 4. 탬플릿 매칭할 비교 이미지
        </ul>
        <ul>
        <img src="https://user-images.githubusercontent.com/37283294/48555405-72dd4b80-e924-11e8-9f98-273599e8c1f0.png"/><br>
        그림 5. 그림 3과 그림 4와의 템플릿 매칭을 통해 얻은 유사값
        </ul> -->
        <li>깃허브 주소 : https://github.com/DONGYYYYY/Bluetooth-based-handicapped-parking-area-system</li>
        <li>시연 동영상 주소</li>
        <ul>
          <li>차선 침범시 부저 및 LED 작동 : https://youtu.be/49GRxaLLxJM</li>
          <li>블루투스 비콘을 사용한 주차장 차단기 : https://youtu.be/3ID35AJobgA</li>
    </ul>
  </ol><br>
  <h3><li>매장 & 주방 연동 시스템(POS기기)</li></h3>
  <ol>
    <li>파일 입출력을 활용한 POS기기 구현</li>
    <li>깃허브 주소 : https://github.com/DONGYYYYY/POS</li>
    <li>시연 동영상 주소 : https://www.youtube.com/watch?v=FstPrcxi2eg </li>
  </ol><br>
  <h3><li>마리오 게임</li></h3>
  <ol>
    <li>Android Studio를 사용하여 Custom View를 활용한 image Sprite 충돌 판정을 활용한 마리오 게임 구현</li>
    <li>깃허브 주소 : https://github.com/DONGYYYYY/MarioGame</li>
    <li>시연 동영상 주소 : https://youtu.be/C4t4fhh5qhA </li>
  </ol>
  <br>
  <h3><li>캠핑장 어플</li></h3>
  <ol>
    <li>Android Studio</li>
      <ul>
        <li>기상청 , 공공 데이터 포럼에서 제공하는 API를 사용하여 캠핑장 정보, 날씨정보를 JSON형식으로 읽어서 활용</li>
        <li>Spring-boot프로젝트가 가지고 있는 DB내용을 get,post방식을 사용하여 이용 ( 한줄평 )</li>
        <li>Android Studio소스에 해당하는 github 주소 : https://github.com/DONGYYYYY/SeoulCamp_ver1</li>
      </ul>
    <li>Spring boot ( STS 사용 )</li>
      <ul>
        <li>한줄평에 사용 될 데이터베이스를 관리하는 Spring-boot프로젝트를 STS를 사용하여 구현</li>
        <li>Spring-boot소스에 해당하는 github 주소 : https://github.com/DONGYYYYY/Seoul-Camping_server</li>
    </ul>
    <li>Android Studio 와 Spring-boot는 git commit을 통하여 push & pull을 하여 협동작업을 진행</li>
  </ol>
  <br>
  <h3><li>동물병원 예약 어플 ( 진행중 )</li></h3>
  <ol>
      <li>Android Studio</li>
      <ul>
        <li>서울시 공공데이터에서 동물병원 정보 API활용 예정 </li>
        <li>Spring-boot프로젝트가 가지고 있는 DB내용을 get,post방식을 사용하여 이용 예정 ( 한줄평 , 계정 정보 , 병원 예약내용)</li>
        <li>Android Studio소스에 해당하는 github 주소 : https://github.com/DONGYYYYY/Petspital_ver0</li>
      </ul>
    <li>Spring boot ( STS 사용 )</li>
      <ul>
        <li>한줄평, 계정 정보, 병원 예약내용에 사용 될 데이터베이스를 관리하는 Spring-boot프로젝트를 STS를 사용하여 구현</li>
    </ul>
  <li>Android Studio 와 Spring-boot는 git commit을 통하여 push & pull을 하여 협동작업을 진행중</li>
  <li>최종적으로 동물병원 예약 시스템을 어플을 통해서 할 수 있도록 만들 예정 ( 프로젝트 진행중인 단계 )</li>
  </ol>
  <br>
   <h3><li>Linux & C를 활용한 프로젝트</li></h3>
  <ul>
    <li>서버와 클라이언트간의 중복 파일 검색 서버 & 클라이언트 설계 및 구현 / 블록 기반 해쉬함수 및 스레드를 활용</li>
  </ul>
  <br>
     <h3><li>OpenCV : 차연산을 활용한 횡단보도 안전 시스템 </li></h3>
      <ol>
        <li>OpenCV에서 차연산을 활용하여 일정 주기 단위( 신호등 빨간불,파란불 ) 에 따른 Tracking & 동영상 저장 및 캡쳐 프로그램</li>
        <li>깃허브 주소 : https://github.com/DONGYYYYY/OpenCV_Project </li>
        <li>시연 동영상 주소 : https://youtu.be/5CYLx_UwrsA </li>        
  </ol>
  <br>
  <h3><li>Arduino를 활용한 프로젝트</li></h3>
  <ul>
    <li>스마트폰 음성 인식을 통한 아두이노 센서 원격 제어 ( 초음파 센서 , LED 센서 , 부저 , 온습도 센서 , LCD 등 ) L</li>
  </ul>
  </br>
  <h3><li>향수 제어 프로젝트</li></h3>
  <ol>
    <li>Raspberry PI</li>
     <ul>
       <li>MagicMirror 오픈소스를 활용하여 UI 구성</li>
       <li>음성인식을 하기 위해서 Google API활용하여 음성인식을 사용</li>
       <li>필요 대화 내용을 js파일을 수정하여 향수를 음성으로 작동할 수 있도록 사용 ( 시리얼통신을 할때 system call을 활용하여 작동 ) </li>
       <li>MagicMirror 오픈소스 깃허브 주소 : https://github.com/MichMich/MagicMirror</li>
    </ul>
    <li>Arduino</li>
     <ul>
       <li>라즈베리파이에서 시리얼 통신으로 받은 값에 따라 해당 향수 작동 ( Servo모터 두개를 활용 )</li>
       <li>적외선 거리 센서의 값이 일정 값 이하일 경우에 적외선 거리 센서 위치에 해당하는 향수를 뿌리도록 작동 ( 향수 작동은 위와 동일 ) </li>
       <li>Arduino소스에 해당하는 깃허브 주소 : https://github.com/DONGYYYYY/Sopoong_automaticPerformance</li>
     </ul>
  </ol>
  </br>
</ol>



