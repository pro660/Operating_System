# 🖥️ Operating System

운영체제 과목을 학습하며 정리한 이론, 실습 코드, 과제, 예제들을 모아둔 저장소입니다.  
프로세스, 스레드, CPU 스케줄링, 동기화, 메모리 관리, 파일 시스템, 시스템 콜 등  
운영체제의 핵심 개념을 **우분투(Ubuntu) 리눅스 환경 실습**과 함께 정리하는 것을 목표로 합니다.

---

## 📌 About This Repository

이 저장소는 단순히 과제 제출용 코드만 모아둔 공간이 아니라,  
운영체제 개념을 직접 구현하고 실습하면서 이해한 내용을 기록하는 학습 저장소입니다.

특히 실습은 **Ubuntu Linux 환경**을 기준으로 진행하며,  
터미널 명령어, C 언어 컴파일, 파일 입출력, 시스템 콜 사용 등  
리눅스 기반 운영체제 실습 경험을 함께 쌓는 데 중점을 두고 있습니다.

주요 내용은 다음과 같습니다.

- 운영체제 이론 정리
- C 언어 기반 실습 코드
- Ubuntu Linux 환경 실습
- 시스템 콜(System Call) 활용 예제
- 파일 입출력 및 프로세스 관련 실습
- 과제 및 개인 학습 내용 아카이빙

---

## 🎯 Study Goals

이 저장소를 통해 다음과 같은 목표를 가지고 학습합니다.

- 운영체제의 핵심 개념 이해
- 이론을 코드로 연결하는 능력 향상
- Ubuntu Linux 환경에서의 실습 경험 축적
- 시스템 콜 기반 저수준 프로그래밍 경험
- 프로세스, 메모리, 파일 관리 구조에 대한 이해
- 실습 결과를 체계적으로 정리하는 습관 형성

---

## 🧩 Main Topics

### 1. Process & Thread
- 프로세스와 스레드의 개념
- 프로세스 생성과 종료
- 부모/자식 프로세스
- 문맥 교환(Context Switch)

### 2. CPU Scheduling
- FCFS
- SJF
- Priority Scheduling
- Round Robin
- 스케줄링 성능 비교

### 3. Process Synchronization
- Race Condition
- Critical Section
- Mutex / Semaphore
- Deadlock

### 4. Memory Management
- 주소 바인딩
- 페이징(Paging)
- 세그멘테이션(Segmentation)
- 가상 메모리(Virtual Memory)

### 5. File System
- 파일과 디렉터리 구조
- 파일 접근 방식
- 파일 복사 및 입출력
- 시스템 콜 기반 파일 처리

### 6. System Calls
- `open()`
- `read()`
- `write()`
- `close()`
- 프로세스 및 파일 제어 관련 시스템 콜 학습

### 7. Linux Practice
- 우분투 터미널 명령어 실습
- `gcc`를 이용한 C 프로그램 컴파일
- 파일/디렉터리 관리
- 리눅스 기반 개발 환경 적응

---

## 🐧 Practice Environment

이 저장소의 실습은 **Ubuntu Linux** 환경을 기준으로 진행합니다.

운영체제 과목 특성상 시스템 콜, 파일 처리, 터미널 명령어, 컴파일 과정을  
직접 다뤄보는 것이 중요하기 때문에, 실습 환경 역시 리눅스 기반으로 구성했습니다.

주요 실습 환경 예시는 다음과 같습니다.

- **OS**: Ubuntu Linux / Window(Only Using VSC)
- **Shell**: Bash
- **Compiler**: gcc
- **Editor**: VS Code / Terminal
- **Execution Environment**: VMware

---

## 🛠️ Tech Stack

- **Language**: C
- **Environment**: Ubuntu / Linux / Window(Only Using VSC)
- **Compiler**: gcc
- **Editor**: VS Code / Terminal
- **Version Control**: Git, GitHub

---

## 📂 Project Structure

```bash
Operating-System/
├── README.md
├── task.c #과제 파일