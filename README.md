# node-benchmarks

## Benchmarks

1. `wget -qO- bench.sh | bash`

2. `fio --randrepeat=1 --ioengine=libaio --direct=1 --gtod_reduce=1 --name=test --filename=random_read_write.fio --bs=4k --iodepth=64 --size=1G --readwrite=randrw --rwmixread=75`
