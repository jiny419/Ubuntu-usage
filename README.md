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

#### cuda version 확인
$ nvcc --version

#### NVIDIA version 확인
$ cat /proc/driver/nvidia/version
$ nvidia-smi --query-gpu=driver_version --format=csv,noheader (for only version)

#### env 확인
$ python -m torch.utils.collect_env

#### check compatability with CUDA and NVIDIA

CUDA Toolkit | Linux x86_64 Driver Version
-------------------|-------------------
cuda 10.2(10.2.89) | >=440.33
cuda 10.1(10.1.105) | >=418.39
cuda 10.0(10.0.130) | >=410.48
cuda 9.2(9.2.88) | >=396.26
cuda 9.1(9.1.85) | >=390.46
cuda 9.0(9.0.76) | >=384.81
cuda 8.0(8.0.61 GA2) | >=375.26
cuda 8.0(8.0.44) | >=367.48
cuda 7.5(7.5.16) | >=352.31
cuda 7.0(7.0.28) | >=346.46
-----------------------------------------
