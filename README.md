# 인공지능을 배우기 위한 가상 학습 환경 만들기 1.
  ## 아나콘다 파이썬 3.7 버전 설치
      
  인텔 Digital Readiness programs 중 AI for Youth Program의 <br>
  Stage 3. 실력키우기 / Module 5, Module 6, Module 8, Module 9 실습을 위한 가상 학습 환경 만들기에 대한 도움 자료입니다. 
  
  <a href="https://www.intel.com/content/www/us/en/corporate/artificial-intelligence/digital-readiness-home.html" target="_blank"> Intel® Digital Readiness Programs </a> <br>
  
  AI for Youth <br>
  For high school students.

  * 설치 프로그램 및 버전
    - Anaconda python 3.7 : 
      https://docs.anaconda.com/anaconda/packages/py3.7_win-64/
    - Tensorflow 2.8
    - Opencv
    - Pyserial
    - imultils
    
  <br><br>

## 1. 아나콘다(Anaconda) 설치

 1.1 아나콘다 파이썬 3.8 버전을 아나콘다 Archive 폴더에서 찾아 다운로드합니다.

 <a href="https://repo.anaconda.com/archive/" target="_blank"> <img src="https://github.com/BrainAI-Lab/venv/blob/main/Anaconda-venv-02.JPG" style="width:669px;height:257px;"> </a>

 다운로드 링크: https://repo.anaconda.com/archive/Anaconda3-2021.05-Windows-x86_64.exe <br>
 
 1.2 다운 받은 파일을 찾아 설치합니다. 설치 시 링크를 참고합니다.
 
 아나콘다 파이썬 3.8 버전 설치 링크 : https://docs.anaconda.com/anaconda/install/windows/
 
## 2. Visual Studion 패키지 설치
 참고 사이트 : https://docs.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170 <br>
 다운로드 링크: https://aka.ms/vs/17/release/vc_redist.x64.exe
 
  <img src="https://github.com/BrainAI-Lab/venv/blob/main/Anaconda-venv-04.JPG" style="width:760px;height:200px;">

## 3. 가상 학습 환경 만들기
  * 참고 링크: https://dojang.io/mod/page/view.php?id=2470<br>
 3.1 Anaconda Promt (Anaconda3) Command 창(아래 이미지 참고)에서 다음 순서대로 명령을 실행하여 가상 학습 환경을 만듭니다.
 
 <img src="https://github.com/BrainAI-Lab/venv/blob/main/Anaconda-venv-05.JPG" style="width:369px;height:156px;">
 
 - (base) C:\WINDOWS\system32\cd\
 - (base) C:\mkdir BrainAI
 - (base) C:\cd BrainAI
 - (base) C:\BrainAI>pip install --upgrade pip
    * 참고 링크: https://pypi.org/project/pip/
 - (base) C:\BrainAI>conda create --name BrainAI python=3.7
    * 참고 링크1: https://docs.conda.io/projects/conda/en/latest/commands/create.html
    * 참고 링크2: https://yganalyst.github.io/pythonic/anaconda_env_1/ 
 - (base) C:\BrainAI>conda activate BrainAI
    * 참고 링크: https://docs.conda.io/projects/conda/en/latest/commands.html#conda-vs-pip-vs-virtualenv-commands
 - (BrainAI) C:\BrainAI>

 3.2 Tensorflow 2.6.0 설치하기
 
 - (BrainAI) C:\BrainAI>conda update --name BrainAI pip
    * 참고 링크: conda update --name BrainAI pip==22.0.3
 - (BrainAI) C:\BrainAI>pip install --upgrade tensorflow==2.6.0
    * 참고 링크: https://www.tensorflow.org/install
 - (BrainAI) C:\BrainAI>pip install opencv-python
    * 참고 링크: https://pypi.org/project/opencv-python/
 - (BrainAI) C:\BrainAI>pip install imutils
    * 참고 링크: https://pypi.org/project/imutils/
 - (BrainAI) C:\BrainAI>pip install pyserial
 - (BrainAI) C:\BrainAI>jupyter lab

 3.3 가상 학습 환경 테스트

  Tensorflow 2.6.0 버전이 출력되면 가상 학습 환경이 정상적으로 설치된 것입니다.

<img src="https://github.com/BrainAI-Lab/venv/blob/main/Anaconda-venv-07.JPG" style="width:684px;height:234px;">


### 수고하셨습니다. 

