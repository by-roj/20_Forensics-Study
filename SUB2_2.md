# 2과목 - Windows

<br>

1. 윈도우즈 시스템에서 생성되는 이벤트 로그 중에서 유효하거나 유효하지 않은 로그온 시도와 같은 이벤트와 함께 리소스 사용과 관련된 이벤트도 포함하고 있는 것은 무엇인가? (가)

   가. 보안 로그

   나. 디렉터리 서비스 로그

   다. 파일 복제 서비스 로그

   라. IAS 로그

   <br>

2. 윈도우에서 NetBIOS 이름을 IP 주소로 변환할 때 WINS(Windows Internet Naming Service)를 이용하는데, 수행되는 절차가 순서상 올바른 것은? (다)

   | 보기                                                         |
   | ------------------------------------------------------------ |
   | 가. 이름이 16문자 이상인지 또는 이름에 마침표(.)가 포함되어 있는지 확인 (만약 그렇다면, DNS 서버에 이름 질의 요청) |
   | 나. 구성된 WINS 서버에 접속한 다음 WINS를 사용하여 해당 이름 확인 |
   | 다. 연결을 위한 인터넷 프로토콜(TCP/IP) 속성에서 'LMHOSTS 조회 가능'으로 설정되어 있을 경우 Lmhosts 파일 확인 |
   | 라. 이름이 클라이언트의 원격 이름 캐시에 저장되어 있는지 확인 |
   | 마. Hosts 파일 확인                                          |
   | 바. 서브넷에 로컬 IP 브로드캐스트 수행                       |
   | 사. DNS 서버에 이름 질의 요청                                |

   가. 가 - 나 - 다 - 라 - 마 - 바 - 사

   나. 가 - 마 - 라 - 바 - 다 - 나 - 사

   다. 가 - 라 - 나 - 바 - 다 - 마 - 사

   라. 마 - 바 - 라 - 가 - 나 - 다 - 사

<br>

3. 다음 보기에서 윈도우(Windows) 운영체제의 파일 시스템은 무엇인가? (가)

   가. NTFS

   나. Ext2

   다. HFS

   라. ZFS

<br>

4. 슬랙 공간(Slack Space)은 물리적인 구조와 논리적인 구조의 차이로 인해 발생하는 낭비공간이다. 아래 보기에서 슬랙 공간의 종류가 아닌 것은? (라)

   가. 램 슬랙

   나. 파일 슬랙

   다. 파일시스템 슬랙

   라. 마스터 슬랙

   <br>

   ⇒ 슬랙 공간

   - 파일 슬랙
     - 램 슬랙
     - 드라이브 슬랙
   - 파일시스템 슬랙
   - 볼륨 슬랙

<br>

5. 시그니처 기반 카빙 기법은 파일 포맷별로 존재하는 고유한 시그니처를 이용하는 방법이다. 다음 중 파일 포맷에 따른 헤더(Hex) 정보가 틀린 것은? (라)

   가. JPEG - FF D8

   나. GIF - 47 49 46 38 37 61 ("GIF87a")

   다. GIF - 47 49 46 38 39 61 ("GIF89a")

   라. PDF - 25 50 33 42 2D 30 E2 ("PDF")

   <br>

   ⇒ PDF Signature

   - 25 50 44 46 ("%PDF")

<br>

6. 윈도우에서 파일 및 디렉토리에 대한 권한을 부여할 때 올바른 규칙이 아닌 것은? (라)

   가. NTFS 접근 권한은 누적된다.

   나. 파일에 대한 접근 권한이 디렉토리에 대한 접근권한 보다 우선한다.

   다. '허용'보다는 '거부가' 우선이다.

   라. 디렉토리에 대한 접근 권한이 파일에 대한 접근권한 보다 우선한다.

   <br>

   ⇒ NTFS 사용 권한

   - 누적 사용 권한
     - 사용자의 자원에 대한 유효한 사용 권한은 개인 사용자 계정 및 사용자가 속해 있는 모든 그룹에 부여된 NTFS 사용 권한의 합
   - NTFS 파일 사용 권한은 NTFS 폴더 사용 권한에 우선
   - 특정 파일에 대하여 사용자 계정 및 그룹에 대한 거부는 다른 모든 경우에 우선

<br>

7. 다음 중 시스템에서 가장 좋은 패스워드는? (라)

   가. qwer1234

   나. 1234

   다. root

   라. rw@#34

<br>

8. 다음 Windows 기본 명령어 중에서 시스템에 등록된 모든 사용자 계정 정보를 얻을 수 있는 명령어는? (나)

   가. set user

   나. net user

   다. net ssions

   라. psloggedon

<br>

9. Windows에서 사용하는 FAT 파일시스템의 경우 첫 번째 섹터의 Offset 510~511에는 Signature가 존재한다. 해당 Signature 값은? (라)

   가. 0x6141

   나. 0x55AA

   다. 0x4161

   라. 0xAA55

<br>

10. Windows Server 2008에서 DNS Zone 파일 기본 위치는? (가)

    가. %SystemRoot%\System32\DNS

    나. %SystemRoot%\System32\Drivers\etc\DNS

    다. %SystemRoot%\System32\Drivers\etc

    라. %SystsemRoot%\System

<br>

11. 윈도우 운영체제의 레지스트리를 설명한 것 중 잘못된 것은?

    가. 레지스트리는 regedit.exe 전용 편집기에서 볼 수 있다.

    나. 레지스트리 백업 및 복구는 regedit.exe을 실행해야 한다.

    다. 윈도우 레지스트리 키는 HKEY_CLASS_ROOT, HKEY_CURRENT_USER, HKEY_LOCAL_MACHINE, HKEY_USERS, HKEY_CURRENT_CONFIG 등이 있다.

    라. 시스템 구성정보를 저장하는 데이터베이스로 SYSTEMS.DAT, USERS.DAT 파일이 있다.

    <br>

    ⇒ 레지스트리

    - Windows 폴더에 system.dat 파일과 user.dat 파일로 저장