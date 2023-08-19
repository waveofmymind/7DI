### 1. OSI 7계층에 대해서 설명해주세요.
물리 계층: 하드웨어 전송 기술을 사용하며, 비트 단위로 전기적인 신호를 주고받습니다.
데이터 링크 계층: 신뢰성 있는 전송을 보장하기 위한 계층이며, MAC주소를 사용합니다. 통신 단위는 프레임입니다.
네트워크 계층: IP 주소를 사용하며, 노드를 거칠때마다 라우팅해주는 역할을 담당합니다. 통신 단위는 패킷입니다.
전송 계층: 사용자가 데이터를 주고받을 수 있도록 해주며, TCP/UDP가 이에 해당합니다. 통신 단위는 세그먼트입니다.
세션 계층: 데이터를 만들어내는 계층이며, TCP/IP 세션을 만들고 소멸시킵니다. 대표적으로 RPC, Socket이 있습니다.
표현 계층: 인코딩이나 암호화 등의 동작이 이 계층에서 이루어집니다.
응용 계층: 응용 프로세스와 연관되어 응용 서비스를 수행하며, HTTP, FTP 프로토콜이 이에 해당합니다.

### 2. TCP UDP의 차이점에 대해 설명해주세요.
우선 TCP가 UDP에 비해 신뢰성이 높습니다. 연결형, 비연결형이기 때문입니다.

패킷 교환 방식은 TCP는 가상 회선 방식, UDP는 데이터 그램 방식이기 때문에, TCP는 요청 데이터에 대한 순서를 보장합니다.

속도는 TCP는 UDP에 비해 빠릅니다. TCP는 연결이 필요하기 때문에 3/4-handshake 과정을 거치기 때문입니다.

