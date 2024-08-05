### CPU
- ``` cat /proc/cpuinfo ```
- ``` lscpu ```

### MEMORY
- ```free -h```
- ```lsmem```
- ```dmidecode -t memory```

### DISK
- ``` df -h```
- ```fdisk -l```
- ```lsblk  #인식하는 디스크 Tree 형태 출력```
- ```du ```
```sh
ex) du -h --max-depth=1 | sort -hr # 현재 디렉터리의 파일 용량 내림차순 정렬

ex) du -hsx * | sort -rh | head -n 10 # 상위 10개 디렉터리 용량 보기
```
### NETWORK
- ```ifconfig```
- ```ip a```

### PCI 버스
- ``` lspci ```
ex ) lspci | grep -i nvidia
