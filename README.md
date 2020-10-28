## Ubuntu-usage


#### 현재 위치에서 파일의 개수 세기 
$ ls -l | grep ^- | wc -l

#### 현재 디렉토리의 하위 파일 개수 세기
$ find . -type f | wc -l

#### 파일 이동
$ mv beforefolder afterfolder

#### 디렉토리 삭제
$ rmdir

#### 파일 삭제
$ rm 

#### 원격 파일 전송
$ scp ./source destination_user@destination_ipaddress:/home/ncidata/jinyeong/source 

#### 현재 위치 확인
$ pwd

#### 디렉토리 목록 확인
$ ls
$ ls -l
