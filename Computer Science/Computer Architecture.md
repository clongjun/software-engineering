# 1-2 컴퓨터의 구조 (Computer Architecture)

컴퓨터는 데이터를 입력받아 처리한 후 결과를 출력하는 시스템으로, 여러 하드웨어 장치가 서로 협력하여 동작한다. 컴퓨터의 기본 구조는 **입력장치(Input Device)**, **중앙처리장치(CPU)**, **기억장치(Memory)**, **보조기억장치(Secondary Storage)**, **출력장치(Output Device)** 로 구성된다.

A computer is a system that receives data, processes it, and outputs results. It operates through the cooperation of multiple hardware components. The basic structure of a computer consists of **Input Device**, **Central Processing Unit (CPU)**, **Memory**, **Secondary Storage**, and **Output Device**.

---

### 1. 입력장치 (Input Device)

입력장치는 **사용자로부터 데이터나 명령어를 받아 컴퓨터가 처리할 수 있는 디지털 신호로 변환하는 장치**이다.

**주요 역할**

- 데이터 입력
- 명령어 입력
- 외부 정보를 디지털 데이터로 변환

**특징**

- 사용자와 컴퓨터가 상호작용하는 장치
- 입력된 데이터는 주기억장치(RAM)에 저장된 후 CPU가 처리한다.

**종류**

| 장치 | 기능 |
|---|---|
| 키보드 | 문자 및 숫자 입력 |
| 마우스 | 위치 선택 및 명령 입력 |
| 스캐너 | 문서 및 이미지를 디지털 데이터로 변환 |
| 마이크 | 음성을 디지털 신호로 변환 |
| 웹캠 | 영상을 디지털 데이터로 입력 |

### 1. Input Device

An input device is **a device that receives data or instructions from users and converts them into digital signals that the computer can process.**

**Main Functions**

- Input data
- Input commands
- Convert external information into digital data

**Characteristics**

- A device that allows interaction between users and computers.
- Input data is stored in main memory (RAM) and then processed by the CPU.

**Types**

| Device | Function |
|---|---|
| Keyboard | Inputs text and numbers |
| Mouse | Selects positions and enters commands |
| Scanner | Converts documents and images into digital data |
| Microphone | Converts voice into digital signals |
| Webcam | Inputs video as digital data |

---

### 2. 중앙처리장치 (CPU)

CPU는 **컴퓨터의 두뇌**로, 프로그램의 명령어를 해석하고 연산과 제어를 수행하는 핵심 장치이다.

**주요 역할**

- 명령어 해석
- 산술 연산 수행
- 논리 연산 수행
- 시스템 전체 제어

CPU는 **산술논리장치**, **제어장치**, **레지스터**로 구성된다.


### 2. Central Processing Unit (CPU)

The CPU is the **brain of the computer** and is the core component that interprets program instructions and performs calculations and control operations.

**Main Functions**

- Interpret instructions
- Perform arithmetic operations
- Perform logical operations
- Control the entire system

The CPU consists of the **Arithmetic Logic Unit (ALU)**, **Control Unit (CU)**, and **Registers**.

---

### 산술논리장치

산술논리장치는 모든 산술 및 논리 연산을 수행하는 장치이다.

**역할**

- 산술 연산
- 논리 연산
- 비교 연산

### Arithmetic Logic Unit (ALU)

The Arithmetic Logic Unit (ALU) performs all arithmetic and logical operations.

**Functions**

- Arithmetic operations
- Logical operations
- Comparison operations

---

### 제어장치

제어장치는 프로그램의 명령어를 해석하고 컴퓨터의 모든 장치가 올바른 순서로 동작하도록 제어한다.

**역할**

- 명령어 해석
- 메모리 접근 제어
- 입출력장치 제어
- CPU 내부 동작 제어

### Control Unit (CU)

The Control Unit (CU) interprets program instructions and controls all computer components so that they operate in the correct sequence.

**Functions**

- Interpret instructions
- Control memory access
- Control input/output devices
- Control internal CPU operations

---

### 레지스터

레지스터는 CPU 내부에 위치한 **가장 빠른 기억장치**로, 연산에 필요한 데이터를 일시적으로 저장한다.

**특징**

- CPU 내부에 위치
- 매우 작은 저장 공간
- 매우 빠른 처리 속도
- 연산 중인 데이터와 명령어를 임시 저장

### Registers

Registers are the **fastest memory units inside the CPU** and temporarily store data required for processing.

**Characteristics**

- Located inside the CPU
- Very small storage capacity
- Very fast processing speed
- Temporarily stores data and instructions being processed

---

### 3. 기억장치

기억장치는 프로그램과 데이터를 저장하는 장치이며, **주기억장치**와 **보조기억장치**로 구분된다.

### 3. Memory

Memory is a device that stores programs and data. It is divided into **Main Memory** and **Secondary Storage**.

---

**주기억장치**

CPU가 직접 접근하여 사용하는 기억장치이다.

**RAM**

**역할**

- 실행 중인 프로그램 저장
- 작업 중인 데이터 저장

**특징**

- 읽기와 쓰기가 가능
- 전원이 꺼지면 데이터가 삭제되는 휘발성 메모리

**Main Memory**

Main memory is the memory directly accessed by the CPU.

**RAM (Random Access Memory)**

**Functions**

- Stores running programs
- Stores data currently being processed

**Characteristics**

- Supports both reading and writing
- Volatile memory that loses data when power is turned off

---

**ROM**

**역할**

- 컴퓨터 부팅에 필요한 기본 프로그램 저장

**특징**

- 읽기 전용 메모리
- 전원이 꺼져도 데이터가 유지되는 비휘발성 메모리

**ROM (Read-Only Memory)**

**Functions**

- Stores basic programs required for computer booting

**Characteristics**

- Read-only memory
- Non-volatile memory that keeps data even when power is turned off

---

### 4. 보조기억장치

보조기억장치는 프로그램과 데이터를 장기간 저장하는 장치이다.

CPU는 보조기억장치에 직접 접근하지 않고, 필요한 데이터를 주기억장치(RAM)로 불러와 처리한다.

**특징**

- 비휘발성 기억장치
- 대용량 저장 가능
- 주기억장치보다 속도가 느림

**종류**

| 장치 | 특징 |
|---|---|
| SSD | 반도체 기반의 고속 저장장치 |
| HDD | 자기 디스크 기반의 대용량 저장장치 |
| USB 메모리 | 휴대용 저장장치 |
| CD/DVD | 광학 저장장치 |

### 4. Secondary Storage

Secondary storage is a device used to store programs and data for a long period of time.

The CPU does not directly access secondary storage. Instead, required data is loaded into main memory (RAM) and then processed.

**Characteristics**

- Non-volatile storage device
- Supports large-capacity storage
- Slower than main memory

**Types**

| Device | Characteristics |
|---|---|
| SSD | High-speed semiconductor-based storage device |
| HDD | Large-capacity magnetic disk storage device |
| USB Flash Drive | Portable storage device |
| CD/DVD | Optical storage device |

---

### 5. 출력장치

출력장치는 컴퓨터가 처리한 결과를 사용자가 이해할 수 있는 형태로 전달하는 장치이다.

**주요 역할**

- 화면 출력
- 문서 출력
- 음성 출력

**종류**

| 장치 | 기능 |
|---|---|
| 모니터 | 화면 출력 |
| 프린터 | 문서 인쇄 |
| 스피커 | 음성 출력 |
| 프로젝터 | 화면 확대 출력 |

### 5. Output Device

An output device delivers the processed results of a computer in a form that users can understand.

**Main Functions**

- Display output
- Print documents
- Produce audio output

**Types**

| Device | Function |
|---|---|
| Monitor | Displays output on the screen |
| Printer | Prints documents |
| Speaker | Produces audio output |
| Projector | Displays enlarged output |

---

### 컴퓨터 구조 요약

| 구성 요소 | 역할 | 특징 |
|---|---|---|
| 입력장치 | 데이터와 명령 입력 | 사용자와 컴퓨터를 연결 |
| 중앙처리장치(CPU) | 연산 및 제어 수행 | 컴퓨터의 핵심 장치 |
| 주기억장치(RAM/ROM) | 프로그램과 데이터 저장 | CPU가 직접 접근 |
| 보조기억장치 | 데이터 영구 저장 | 대용량·비휘발성 |
| 출력장치 | 처리 결과 출력 | 사용자에게 결과 전달 |

### Summary of Computer Architecture

| Component | Role | Characteristics |
|---|---|---|
| Input Device | Inputs data and commands | Connects users and computers |
| Central Processing Unit (CPU) | Performs calculations and control | Core component of a computer |
| Main Memory (RAM/ROM) | Stores programs and data | Directly accessed by CPU |
| Secondary Storage | Permanently stores data | Large-capacity and non-volatile |
| Output Device | Outputs processed results | Delivers results to users |
