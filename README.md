# 🖥️ Operating System

운영체제 과목을 학습하며 정리한 이론, 실습 코드, 과제, 예제들을 모아둔 저장소입니다.  
프로세스, 스레드, CPU 스케줄링, 동기화, 메모리 관리, 파일 시스템, 시스템 콜 등  
운영체제의 핵심 개념을 코드와 함께 정리하는 것을 목표로 합니다.

---

## 📌 About This Repository

이 저장소는 단순히 과제 제출용 코드만 모아둔 공간이 아니라,  
운영체제 개념을 직접 구현하고 실습하면서 이해한 내용을 정리하는 학습 기록입니다.

주요 내용은 다음과 같습니다.

- 운영체제 이론 정리
- C 언어 기반 실습 코드
- 시스템 콜(System Call) 활용 예제
- 파일 입출력 및 프로세스 관련 실습
- 과제 및 개인 학습 내용 아카이빙

---

## 🎯 Study Goals

이 저장소를 통해 다음과 같은 목표를 가지고 학습합니다.

- 운영체제의 핵심 개념 이해
- 이론을 코드로 연결하는 능력 향상
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

---

## 🛠️ Tech Stack

- **Language**: C
- **Environment**: Ubuntu / Linux
- **Compiler**: gcc
- **Editor**: VS Code / Terminal
- **Version Control**: Git, GitHub

---

## 📂 Project Structure

```bash
Operating-System/
├── README.md
├── theory/              # 운영체제 이론 정리
├── practice/            # 수업 시간 실습 코드
├── assignments/         # 과제 코드
├── system-calls/        # 시스템 콜 관련 예제
├── file-io/             # 파일 입출력 실습
└── notes/               # 개인 학습 메모 및 정리