# Contabo


## VPS M SSD

```
----------------------------------------------------------------------
CPU model            : Intel(R) Xeon(R) CPU E5-2620 v3 @ 2.40GHz
Number of cores      : 4
CPU frequency        : 2399.996 MHz
Total size of Disk   : 295.2 GB (209.1 GB Used)
Total amount of Mem  : 12015 MB (7703 MB Used)
Total amount of Swap : 0 MB (0 MB Used)
System uptime        : 112 days, 12 hour 1 min
Load average         : 0.66, 0.63, 0.80
OS                   : Ubuntu 16.04.5 LTS
Arch                 : x86_64 (64 Bit)
Kernel               : 4.4.0-135-generic
----------------------------------------------------------------------
I/O speed(1st run)   : 98.9 MB/s
I/O speed(2nd run)   : 101 MB/s
I/O speed(3rd run)   : 102 MB/s
Average I/O speed    : 100.6 MB/s
----------------------------------------------------------------------
Node Name                       IPv4 address            Download Speed
CacheFly                        205.234.175.175         11.9MB/s
Linode, Tokyo, JP               106.187.96.148          8.38MB/s
Linode, Singapore, SG           139.162.23.4            8.41MB/s
Linode, London, UK              176.58.107.39           11.9MB/s
Linode, Frankfurt, DE           139.162.130.8           11.9MB/s
Linode, Fremont, CA             50.116.14.9             10.4MB/s
Softlayer, Dallas, TX           173.192.68.18           9.58MB/s
Softlayer, Seattle, WA          67.228.112.250          9.26MB/s
Softlayer, Frankfurt, DE        159.122.69.4            11.8MB/s
Softlayer, Singapore, SG        119.81.28.170           7.27MB/s
Softlayer, HongKong, CN         119.81.130.170          7.40MB/s
----------------------------------------------------------------------
```

```
fio-2.2.10
Starting 1 process
test: Laying out IO file(s) (1 file(s) / 1024MB)
Jobs: 1 (f=1): [m(1)] [75.0% done] [206.7MB/72299KB/0KB /s] [52.9K/18.8K/0 iops] [eta 00m:01s]
test: (groupid=0, jobs=1): err= 0: pid=8576: Fri Apr 26 11:56:19 2019
  read : io=784996KB, bw=209836KB/s, iops=52458, runt=  3741msec
  write: io=263580KB, bw=70457KB/s, iops=17614, runt=  3741msec
  cpu          : usr=10.80%, sys=81.50%, ctx=1302, majf=0, minf=9
  IO depths    : 1=0.1%, 2=0.1%, 4=0.1%, 8=0.1%, 16=0.1%, 32=0.1%, >=64=100.0%
     submit    : 0=0.0%, 4=100.0%, 8=0.0%, 16=0.0%, 32=0.0%, 64=0.0%, >=64=0.0%
     complete  : 0=0.0%, 4=100.0%, 8=0.0%, 16=0.0%, 32=0.0%, 64=0.1%, >=64=0.0%
     issued    : total=r=196249/w=65895/d=0, short=r=0/w=0/d=0, drop=r=0/w=0/d=0
     latency   : target=0, window=0, percentile=100.00%, depth=64

Run status group 0 (all jobs):
   READ: io=784996KB, aggrb=209835KB/s, minb=209835KB/s, maxb=209835KB/s, mint=3741msec, maxt=3741msec
  WRITE: io=263580KB, aggrb=70457KB/s, minb=70457KB/s, maxb=70457KB/s, mint=3741msec, maxt=3741msec

Disk stats (read/write):
  sda: ios=184931/63061, merge=0/48, ticks=45172/19772, in_queue=64888, util=96.81%
```
