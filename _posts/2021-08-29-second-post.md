프로세스 관련

fork : 새로운 프로세스를 생성합니다.

exec : 새로운 프로세스를 수행합니다.

exit : 프로세스 수행을 종료합니다.

wait : fork 후 exec에 의해 실행되는 프로세스의 상위 프로세스가 하위 프로세스 종료 등의 event를 기다립니다.

kill : 프로세스를 제거합니다.

getpid : 자신의 프로세스 아이디를 얻습니다.

getppid : 부모 프로세스 아이디를 얻습니다.

& : 백그라운드 처리를 위해 명령의 끝에 입력합니다.

signal : 신호를 받았을 때 프로세스가 취할 동작을 지정합니다.

pipe : 프로세스 간 통신을 위한 경로를 설정합니다.



파일 및 디렉터리 & 기타관련

create : 파일을 생성합니다.

open : 파일을 사용할 수 있는 상태로 준비시킵니다.

close : 파일을 닫습니다.

cp : 파일을 복사합니다.

mv : 파일을 이동시키거나 이름을 변경합니다.

rm : 파일을 삭제합니다.

cat : 파일 내용을 화면에 표시합니다.

chmod : 파일의 보호 모드를 설정하여 파일의 사용 허가를 지정합니다.

chown : 소유자를 변경합니다.

find : 파일을 찾습니다.

mknod : 특수 파일을 생성합니다.

mount : 파일 시스템을 마운팅합니다. 

unmount : 파일 시스템의 마운팅을 해제합니다.

mkfs : 파일 시스템을 생성합니다.

fsck : 파일 시스템을 검사하고 보수합니다.

mkdir : 디렉터리를 생성합니다.

chdir : 현재 사용할 디렉터리 위치를 변경합니다.

rmdir : 디렉터리를 삭제합니다.

ls : 현재 디렉터리 내의 파일 목록을 확인합니다.

finger : 사용자 정보를 표시합니다.
