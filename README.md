#### rins_web_crawler.py
- 정기 점검 시 7일간의(금~목) 트래픽 체크 및 API 이력 조회를 하기 위한 웹 크롤러

#### rins_maintenance_macro.py
- 정기 점검 매크로
- 특정 프로그램을 통해 서버 접속이 가능하며, 자동화 스크립트 등 배포가 제한된 환경
- 서버 접속 간 호스트명을 캡처하여 문자 인식 진행, 해당 서버가 일치할 경우만 점검 진행
- GUI를 컨트롤하여 순차 처리

#### sp_maintenance_macro.py
- 정기 점검 매크로
- 특정 프로그램을 통해 서버 접속이 가능하며, 자동화 스크립트 등 배포가 제한된 환경
- GUI를 컨트롤하여 순차 처리

#### wcs_docx_auto.py
- 정기 점검 후 결과 보고서 자동화

#### ssh_auto.py
- ssh 프로그램을 이용한 서버 접속이 가능한 경우, 1번 파일에 서버 리스트, 2번 파일에 명령어를 작성하여 실행
- tb 환경, vm에 활용
