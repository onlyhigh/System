시스템 프로그래밍 정리 (VM / JVM / WSL)
1. VM (Virtual Machine, 가상 머신)

가상 머신(Virtual Machine)은 하나의 물리적인 컴퓨터에서 여러 개의 가상 컴퓨터 환경을 실행할 수 있도록 하는 기술이다.

즉, 실제 컴퓨터 한 대에서 여러 운영체제를 동시에 사용할 수 있게 한다.

특징

하나의 하드웨어에서 여러 운영체제를 실행할 수 있다.

서로 독립적인 환경을 제공한다.

테스트 환경이나 개발 환경에서 많이 사용된다.

예시

VMware

VirtualBox

Hyper-V

2. JVM (Java Virtual Machine)

JVM(Java Virtual Machine)은 Java 프로그램을 실행하기 위한 가상 머신이다.

Java 프로그램을 컴파일하면 **.class 파일(바이트코드)**이 생성되며, 이 바이트코드를 실행하는 역할을 JVM이 담당한다.

특징

운영체제에 관계없이 Java 프로그램을 실행할 수 있다.

"Write Once, Run Anywhere" 개념을 가능하게 한다.

메모리 관리와 Garbage Collection 기능을 제공한다.

주요 구성 요소

Class Loader

Runtime Memory Area

Execution Engine

3. WSL (Windows Subsystem for Linux)

WSL은 Windows 운영체제에서 Linux 환경을 사용할 수 있도록 해주는 기능이다.

즉, 별도의 가상 머신을 사용하지 않고 Windows 안에서 Linux 명령어와 프로그램을 실행할 수 있다.

특징

Windows 환경에서 Linux 사용 가능

개발 환경 구축에 유용

Linux 명령어와 프로그램 실행 가능

WSL2 특징

실제 Linux 커널 사용

성능 향상

파일 시스템 속도 개선

정리

VM : 하나의 컴퓨터에서 여러 운영체제를 실행할 수 있게 하는 가상 컴퓨터 기술

JVM : Java 프로그램을 실행하는 가상 머신

WSL : Windows에서 Linux 환경을 실행할 수 있게 해주는 기능
