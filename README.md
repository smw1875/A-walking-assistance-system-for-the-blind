# A-walking-assistance-system-for-the-blind

본 프로젝트는 시각장애인 보행 보조 시스템으로 시각장애인이 횡단보도를 건널때 횡단보도와 신호등의 정보를 알려줘서 안정적으로 보행할 수 있도록 한다. 

프로젝트 제품은 흰지팡이를 베이스로하여 라즈베리파이, 초음파센서, 진동 모듈, 카메라 등의 부품으로 이루어져 있다.

사용자는 길을 걷다가 초음파 센서로 장애물을 판단하여 진동모듈의 세기를 통해 장애물과의 거리를 확인할 수 있다.
카메라를 통해 횡단보도와 신호등의 정보를 듣고 TTS를 이용하여 현재 신호등의 상태를 알 수 있다.

카메라로 객체 인식을 위한 딥러닝 모델은 yolov5n을 사용하였으며 yolov5모델중 가장 작고 fps가 높기 때문에 선택하였다.
빅데이터를 수집하기 위해 roboflow에서 데이터를 이용하였다.

시연영상 : https://drive.google.com/file/d/1TlC7cMIVKmrJPa-Ag0m0J3gMlm-MROs8/view?usp=sharing

보고서 : https://drive.google.com/file/d/1vvdGnlgtwbqmks4u5S7yBp1zQxbiPvrD/view?usp=sharing
