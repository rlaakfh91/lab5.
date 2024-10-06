## I/O Redirection
Standard Output : 
기본적으로 스크린, 다른것으로 바꿀 수 있음(커멘드 뒤 >)

(>> 파일이름) 하면 어펜딩

## Standard Input : 
기본적으로 키보드로

< 쓰면 파일을 input으로 ex) sort < words.txt > sorted_words.txt : 사전순으로 단어정리

## Pipelines '|' 
아웃풋을 그다음단계 인풋으로

## Expansion
echo : 뒤 텍스트 출력
echo * : 현재 작업중인 디렉토리 파일들 출력
echo ~  : 현재 유저의 홈 디렉토리 출력

## Tip
\\ : 줄바꿈, 그다음 커맨드 계속 기다리게, 가독성 위해
History : 이전 사용한 명령어들

## Permissions
권한 부여 : reading, writing executing
소유자/그룹/나머지사용자
-rwxrwxrwx
-/d : 레귤러파일/디렉토리
첫번째 rwx 소유자 권한
두번째 rwx 그룹 권한
세번째 rwx 나머지사용자 권한
chmod : 권한 변환
chmod nnn 2진수로 권한 부여 EX) 600 : 소유자 권한만 rw

### Superuser : 모든 파일에 권한 sudo

## Text Editors
vi, vim / Emacs / nano / gedit / kwrite

### wget :
url로 파일 다운로드

### curl 
: 파일 다운로드 + 업로드 ex) curl -o [파일]

### grep(Global Regular Expression Print) 
: 텍스트 서치할 때 / grep "검색 단어" 파일
-i 대소구분 x / -v 포함안한거 / -n 라인넘버 / -r 하위디렉토리까지
