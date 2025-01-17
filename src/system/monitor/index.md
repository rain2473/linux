---
layout: home
---

# 시스템 모니터링
시스템 관리를 위하여 시스템 상황을 상시 모니터링하고 관리하는 업무는 매우 중요하다.
  
## 시스템 측정
리눅스 운영체제에서 시스템 측정(System monitoring)은 시스템 자원(CPU, 메모리, 디스크 등)의 사용률과 성능, 네트워크 연결 상태 등의 정보를 지속적으로 수집하여 분석하는 작업을 말합니다. 시스템 측정을 통해 시스템의 안정성, 성능, 문제점 등을 파악하여 문제점을 해결하고 최적화된 시스템 운영을 할 수 있습니다.  


* [top](top) : 현재 CPU에 수행되고 있는 프로세스 상황을 CPU 자원을 많이 사용하는 순서대로 보여줌
* [vmstat](vmstat) : Linux vmstat 명령은 프로세스, 메모리, 페이징, 블록 IO 및 CPU 활동을 포함한 가상 메모리 통계를 표시합니다. 
* [iostat](iostat) : Linux의 iostat 명령은 시스템 입/출력(I/O) 사용 및 장치 활용 통계를 모니터링하는 데 사용됩니다.
* [netstat](netstat) : Linux netstat 명령은 네트워크 연결, 라우팅 테이블 및 네트워크 인터페이스 통계에 대한 정보를 표시하는 데 사용됩니다.

* [uptime](uptime) : Linux uptime 명령은 시스템 실행 시간, 현재 로그인한 사용자 수, 지난 1분, 5분, 15분 동안의 시스템 로드 평균을 표시합니다.

* [sar](sar) : sar 명령은 일정 기간 동안 CPU 사용량, 메모리 사용량, 디스크 I/O 작업, 네트워크 통계 등과 같은 시스템 활동 정보를 수집, 보고 및 분석하는 데 사용됩니다. 성능 문제를 진단 및 해결하고 시스템 리소스 활용을 최적화하는 데 사용할 수 있습니다.

## 시스템 상태 확인하기
* fsck : 파일 시스템 오류 확인
* du : 디스크 사용량 출력
* df : 
