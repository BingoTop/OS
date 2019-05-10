# OS
### 버퍼링
> 프로세서와 입출력장치의 속도 차이로 생긴 유후시간이 없도록 입출력장치별로 입출력 버퍼를 두어, 
> 프로세서가 연산을 할 때 동시에 다른 작업을 입출력 하는 방법

버퍼
> 프로세서가 어떤 작업을 처리하는 동안 버퍼에 다음으로 처리할 작업을 미리 읽어 저장해 두는 메모리이다.
### 스풀링
> 속도가 빠른 디스크를 버퍼처럼 사용하여 입출력장치에서 미리 읽는 것
> 별개의 오프라인 장치 사용, 여러 작업의 입출력과 계산을 함께 사용 가능
## 교착상태

> 프로세스가 결코 일어나지 않을 사건을 기다리는 상태가 되면 교착(Dead lock)상태에 빠졌다고 말한다.
> 교착상태는 시스템 자원에 요구가 뒤엉킨 상태로, 두 프로세스가 사용하는 자원을 서로 기다리고 있을 때 발생

## 교착상태의 예
### 둘 이상의 작업이 대기 상태로 중요한 자원을 사용하려고 기다릴 때 발생
### 자원의 요청과 해제가 중요

1. 스풀링 시스템에서 발생하는 교착 상태
2. 디스크를 공유할 때 발생하는 교착 상태
3. 네트워크에서 발생하는 교착 상태
