# Netcup SSD-backed (4 shared cores)

```
----------------------------------------------------------------------
CPU model            : QEMU Virtual CPU version 2.5+
Number of cores      : 4
CPU frequency        : 2399.996 MHz
Total size of Disk   : 735.0 GB (279.0 GB Used)
Total amount of Mem  : 7989 MB (991 MB Used)
Total amount of Swap : 3814 MB (216 MB Used)
System uptime        : 92 days, 20 hour 28 min
Load average         : 0.27, 0.58, 1.27
OS                   : Debian GNU/Linux 9
Arch                 : x86_64 (64 Bit)
Kernel               : 4.9.0-8-amd64
----------------------------------------------------------------------
I/O speed(1st run)   : 240 MB/s
I/O speed(2nd run)   : 228 MB/s
I/O speed(3rd run)   : 446 MB/s
Average I/O speed    : 304.7 MB/s
----------------------------------------------------------------------
Node Name                       IPv4 address            Download Speed
CacheFly                        205.234.175.175         76.8MB/s      
Linode, Tokyo, JP               106.187.96.148          7.48MB/s      
Linode, Singapore, SG           139.162.23.4            9.15MB/s      
Linode, London, UK              176.58.107.39           38.4MB/s      
Linode, Frankfurt, DE           139.162.130.8           90.1MB/s      
Linode, Fremont, CA             50.116.14.9             13.6MB/s      
Softlayer, Dallas, TX           173.192.68.18           3.21MB/s      
Softlayer, Seattle, WA          67.228.112.250          7.85MB/s      
Softlayer, Frankfurt, DE        159.122.69.4            80.4MB/s      
Softlayer, Singapore, SG        119.81.28.170           9.01MB/s      
Softlayer, HongKong, CN         119.81.130.170          7.05MB/s      
----------------------------------------------------------------------
```

```
fio-2.16
Starting 1 process
Jobs: 1 (f=1): [m(1)] [100.0% done] [564KB/172KB/0KB /s] [141/43/0 iops] [eta 00m:00s]      
test: (groupid=0, jobs=1): err= 0: pid=15794: Fri Apr 26 12:00:20 2019
  read : io=3070.4MB, bw=7338.7KB/s, iops=1834, runt=428452msec
  write: io=1025.8MB, bw=2451.5KB/s, iops=612, runt=428452msec
  cpu          : usr=1.33%, sys=8.38%, ctx=730770, majf=0, minf=8
  IO depths    : 1=0.1%, 2=0.1%, 4=0.1%, 8=0.1%, 16=0.1%, 32=0.1%, >=64=100.0%
     submit    : 0=0.0%, 4=100.0%, 8=0.0%, 16=0.0%, 32=0.0%, 64=0.0%, >=64=0.0%
     complete  : 0=0.0%, 4=100.0%, 8=0.0%, 16=0.0%, 32=0.0%, 64=0.1%, >=64=0.0%
     issued    : total=r=785996/w=262580/d=0, short=r=0/w=0/d=0, drop=r=0/w=0/d=0
     latency   : target=0, window=0, percentile=100.00%, depth=64

Run status group 0 (all jobs):
   READ: io=3070.4MB, aggrb=7338KB/s, minb=7338KB/s, maxb=7338KB/s, mint=428452msec, maxt=428452msec
  WRITE: io=1025.8MB, aggrb=2451KB/s, minb=2451KB/s, maxb=2451KB/s, mint=428452msec, maxt=428452msec

Disk stats (read/write):
  sda: ios=786112/265395, merge=6/1332, ticks=25750952/1579732, in_queue=27337600, util=100.00%
```

# Netcup SSD (2 dedicated cores)

```
----------------------------------------------------------------------
CPU model            : Intel(R) Xeon(R) Gold 6140 CPU @ 2.30GHz
Number of cores      : 2
CPU frequency        : 2294.604 MHz
Total size of Disk   : 126.0 GB (26.0 GB Used)
Total amount of Mem  : 20083 MB (825 MB Used)
Total amount of Swap : 0 MB (0 MB Used)
System uptime        : 22 days, 16 hour 2 min
Load average         : 0.10, 1.04, 1.61
OS                   : Debian GNU/Linux 9
Arch                 : x86_64 (64 Bit)
Kernel               : 4.9.0-8-amd64
----------------------------------------------------------------------
I/O speed(1st run)   : 286 MB/s
I/O speed(2nd run)   : 370 MB/s
I/O speed(3rd run)   : 363 MB/s
Average I/O speed    : 339.7 MB/s
----------------------------------------------------------------------
Node Name                       IPv4 address            Download Speed
CacheFly                        205.234.175.175         92.6MB/s      
Linode, Tokyo, JP               106.187.96.148          8.53MB/s      
Linode, Singapore, SG           139.162.23.4            8.66MB/s      
Linode, London, UK              176.58.107.39           41.2MB/s      
Linode, Frankfurt, DE           139.162.130.8           107MB/s       
Linode, Fremont, CA             50.116.14.9             13.8MB/s      
Softlayer, Dallas, TX           173.192.68.18           1.97MB/s      
Softlayer, Seattle, WA          67.228.112.250          4.79MB/s      
Softlayer, Frankfurt, DE        159.122.69.4            49.7MB/s      
Softlayer, Singapore, SG        119.81.28.170           2.18MB/s      
Softlayer, HongKong, CN         119.81.130.170          1.43MB/s   
```

```
fio-2.16
Starting 1 process
Jobs: 1 (f=1): [m(1)] [100.0% done] [118.3MB/40440KB/0KB /s] [30.3K/10.2K/0 iops] [eta 00m:00s]
test: (groupid=0, jobs=1): err= 0: pid=22089: Fri Apr 26 11:53:44 2019
  read : io=3070.4MB, bw=118525KB/s, iops=29631, runt= 26526msec
  write: io=1025.8MB, bw=39596KB/s, iops=9898, runt= 26526msec
  cpu          : usr=7.46%, sys=35.57%, ctx=89709, majf=0, minf=9
  IO depths    : 1=0.1%, 2=0.1%, 4=0.1%, 8=0.1%, 16=0.1%, 32=0.1%, >=64=100.0%
     submit    : 0=0.0%, 4=100.0%, 8=0.0%, 16=0.0%, 32=0.0%, 64=0.0%, >=64=0.0%
     complete  : 0=0.0%, 4=100.0%, 8=0.0%, 16=0.0%, 32=0.0%, 64=0.1%, >=64=0.0%
     issued    : total=r=785996/w=262580/d=0, short=r=0/w=0/d=0, drop=r=0/w=0/d=0
     latency   : target=0, window=0, percentile=100.00%, depth=64

Run status group 0 (all jobs):
   READ: io=3070.4MB, aggrb=118524KB/s, minb=118524KB/s, maxb=118524KB/s, mint=26526msec, maxt=26526msec
  WRITE: io=1025.8MB, aggrb=39595KB/s, minb=39595KB/s, maxb=39595KB/s, mint=26526msec, maxt=26526msec

Disk stats (read/write):
  sda: ios=781995/261452, merge=0/92, ticks=1221860/391124, in_queue=1613408, util=99.81%
```
