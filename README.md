<html>
  <head>
  </head>
  <body>
    <h1>음악유사성 판별데이터를 활용한 아이디어 해커톤</h1>
    <h5>전체 서비스 과정</h5>
    <ol>
      <li>MIDI 파일에서 학습 데이터 추출</li>
      <li>음원 분위기 감성사전을 통한 음원 분위기 추출
        <br>MIDI 파일의 요소에서 주파수를 추출하여 감성 분석을 위한 음악의 템포, 역동성, 진폭변화, 
  밝기, 잡음 등 5가지 음악의 요소 선택
      </li>
      <li>음원 장르 사전을 통한 음원 장르 추출
        <br>MIDI 파일의 요소에서 ID3vl에서 제안된 125가지 장르의 파악을 위한 템포, 박자, 멜로디의 
  높낮이, 악기 등의 음악의 요소를 선택
      </li>
      <li>1,2,3번에서 추출한 정보로 데이터베이스 구축</li>
      <li>데이터베이스에 추출한 정보를 Muse GAN을 이용하여 학습
        <br>MuseGan : 시계열 데이터를 사용하여 작곡하는 것이 아닌 악기 간의 조화를 중시하며 곡을 작곡하는 AI 모델
      </li>
      <li>학습 모델로 유사도 측정 및 시각화 </li>
      <li>유사도가 높은 구간에 대하여 추천 서비스 구현</li>
    </ol>
  </body>
</html>
