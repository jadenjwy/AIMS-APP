AIMS APP TUTORIAL
=================
이 튜토리얼에서는 에임스(AIMS)의 사용자 조작법에 대해서 알아볼 것입니다. 프로젝트의 설정 및 실행 방법과 환경설정, 그 외에 에임스를 사용하는 데에 필요한 것들을 살펴보겠습니다.
다운로드 및 설치 

This tutorial will run you through AIMS' interface. We're going to look at application preference, the Projects and everything you need to know to get started with the AIMS.

1.설치
--------------------------
[AIMS.APCC21.ORG](http://aims.apcc21.org)에 접속하여 운영체제에 맞는 프로그램을 다운받아 설치합니다.
설치 과정과 유저 인터페이스는 윈도우와 맥 모두 같습니다.
설치가 끝나는 경우 바탕화면에 아이콘이 생성되고 프로그램이 바로 실행됩니다.

![set-up](./set-up.png) 

2.실행 화면
----------------------
 첫화면에서 AIMS의 News에 대해 알 수 있고 새로운 프로젝트를 추가할 수 있습니다. 우측 상단의 버튼을 눌러서 설정 변경도 가능합니다. 


![first-main](./first-main.png)



우측 상단의 설정 버튼을 누르는 경우 프로젝트를 저장하는 공간인 **Workspace directory**나 프로젝트를 위해 공유하는 데이터를 저장하는 공간인 **Database Directory**를 변경할 수 있습니다.


![application-preference](./application-preference.png)


3.프로젝트의 생성
---------------- 

첫 화면에서 프로젝트를 추가하여 프로젝트 타입과 프로젝트명을 설정합니다. 


![create-a-new-project](./create-a-new-project.png)


생성된 프로젝트 중 실행할 프로젝트를 선택합니다


![project](./project.png)


프로젝트를 선택해서 들어온 첫화면에서는 좌측상단의 홈버튼으로 첫페이지로 이동할 수 있습니다. 중앙 상단의 재생 버튼 프로젝트를 실행할 수 있고, 새로재생 버튼으로 프로젝트를 다시 시작할 수 있습니다. 우측에는 해당 프로젝트의 이름과 설명을 확인할수 있습니다.


![project-main-1](./project-main-1.png)


패키지 정보란에는 이름과 버전 정보, 패키지 의존성에 대해 알 수 있습니다. export 버튼으로 현재 결과값을 저장하여(OOO.aims.proj) 다른 pc에서도 불러올 수 있습니다.  
Reset Workflow Status 설명
Reset All Settings 설명


![project-main-2](https://github.com/antonionote85/AIMS-APP/blob/master/project-main-2.png)


4.프로젝트 실행전 설정
------------------
프로젝트의 카드는 각각에 해당하는 task(실행하는 코드)가 있으며 프로젝트는 최상단의 카드부터 순차적으로 진행됩니다.

목적의 설정 복수 선택가능


![objective](https://github.com/antonionote85/AIMS-APP/blob/master/objective.png)


데이터 소스 - 지역선택


![data-source](https://github.com/antonionote85/AIMS-APP/blob/master/data-source.png)


로컬데이터


![local-data](https://github.com/antonionote85/AIMS-APP/blob/master/local-data.png)
![local-data-2](https://github.com/antonionote85/AIMS-APP/blob/master/local-data-2.png)


evaluate observed data


![evaluate observed data](https://github.com/antonionote85/AIMS-APP/blob/master/evaluate%20observed%20data.png
)


stop


![stop](https://github.com/antonionote85/AIMS-APP/blob/master/stop.png)
![stop-2](https://github.com/antonionote85/AIMS-APP/blob/master/stop-2.png)


down scale


![downscale](./downscale.png)


climate-change-index-calculation


![climate-change-index-calculation](./climate-change-index-calculation.png)
![climate-change-index-calculation-2](./climate-change-index-calculation-2.png)


weight-factor-and-uncertainly-for-GCMs


![weight-factor-and-uncertainly-for-GCMs](./weight-factor-and-uncertainly-for-GCMs.png)
![weight-factor-and-uncertainly-for-GCMs-2](./weight-factor-and-uncertainly-for-GCMs-2.png)


modeling-drought-index


![modeling-drought-index](./modeling-drought-index.png)
![modeling-drought-index-2](./modeling-drought-index-2.png)


references


![references](./references.png)


5.프로젝트의 실행
---------------------


프로젝트의 설정을 마친 후 재생 버튼으로 프로젝트를 실행할 수 있습니다.
'**서브 페키지 디펜던스**'들을 설치 하지 않았기 때문에 첫 프로젝트의 실행시간이 다소 길어질 수 있습니다.
프로젝트를 실행하는 경우 다른 버튼들은 비활성화됩니다.


![project-start-1](./project-start-1.png)


'**running**'의 표시는 해당 카드의 task가 실행되고 있음을 의미합니다.


![project-start-2](./project-start-2.png)


'error'가 나는 경우 로그파일을 확인하여 이유를 확인할 수 있습니다.


![project-start-3](./project-start-3.png)


해당 카드의 tast만 실행하고자 하는 경우 '**run-this-section-only**'를 선택합니다.


![run-this-section-only](./run-this-section-only.png)
