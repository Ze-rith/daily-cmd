네트워크 감시 -><br>
사활 감시(ping) : <br>
!는 잘 됬다.<br>
.은 망했다<br>
상태 감시 :<br>
구조 복잡<br>
<br>
CDP : <br>
SNMP : <br>
SNMP 매니저 : 162 UDP<br>
SNMP 에이전트 : 161 UDP<br>
<br>
SMI : 관리 정보 구조<br>
MIB : 객체들의 데이터 베이스를 의미<br>
<br>
SNMP 메니저는 SNMP 에이전트에 대해 대상의 OID를 요청함<br>

SMI,MIB<br>
트리 구조<br>
1.ISO<br>
2.ORG<br>
3.DOD<br>
4.INTERNET<br>
5.MGMT<br>
6.MIB<br>
7...<br>
7...<br>
6...<br>
7...<br>
<br>
SNMP 메시지 정보는 크게 리퀘스트(G로 시작하는 리퀘스트는 다 SNMP 메니저) 리스폰스(, 나머지는 SNMP 메니저)<br>
<br>
라우터가 SNMP 매니저가 이상하다 -> IP 알려달라<br>
안물어봐도 알려달라 --> TRAP<br>
<br>
TRAP : 알려준다 한번 이밴트 발생하면<br>
INFORM : 계속 볼때까지 알려줌<br>
<br>
V1떄는 하나의 정보<br>
V2C는 여러개의 정보를 한번에<br>
V3는 현재 사용<br>
V1, V2 커뮤니티 명<br>
V2C는 유저명<br>
<br>
글로버 유니캐스트 주소<br>
ipv4의 글로버 ip 주소로 사용<br>
3bit부터 시작<br>
2000부터 시작<br>
<br>
ipv6<br>
자동으로 넣고 싶다 링크 로컬(link - local)<br>




