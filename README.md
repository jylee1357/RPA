# RPA
Robotic Process Automation

# UiPath Components
- UiPath Studio: This component uses visual aids such as diagrams and flowcharts to design automation processes.
It also involves the coding and sequencing of these processes. It consists of Graphical User Interface (GUI) buttons, drag and drop features,
and pre-built templates.
- UiPath Robot (Desktop, PC): In this component, multiple bots are deployed to execute the automation processes using pre-defined rules.
- UiPath Orchestrator: This component functions as a web-based application that schedules, deploys, and manages processes.

# Wild Card
1. Asterisk (*) - replaces zero or more characters
2. Question mark (?) - replaces a single character

When using selector editor, we can use * to replace things that change. 
<webctrl aaname = 'first place Jack harlow' -> 'first place *' 
idx = '1'-> idx = '*'

# IP 변경에 의한 설정 변경
 - 공통 변경
  1. 관리자 권한으로 메모장 실행
  2. C:\Windows\System32\drivers\etc\hosts 열기
  3. 변경된 IP     uipath.rpa.com  으로 수정
  4. 저장

 - 오케스트레이터
  1.시작 - IIS(인터넷 정보 서비스 관리) 실행
  2. 왼쪽 [연결] 하단에  '>' 클릭 - 사이트 왼쪽에 '>' 클릭 - UiPath Orchestrator 클릭
  3. [웹 사이트 관리] - '다시 시작' 클릭
  4. 오케스트레이터 접속 확인

hosts 파일 변경하는것은 오케스트레이터 및 봇에 모두 적용해야합니다
