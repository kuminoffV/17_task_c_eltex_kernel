
.PHONY := clean

bin1 := client
bin2 := serv
CC:= gcc

all: run
	
go:
		QEMU_AUDIO_DRV=none qemu-system-arm -M vexpress-a9 -kernel zImage -dtb vexpress-v2p-ca9.dtb -append "console=ttyAMA0" -nographic

clean: 
		rm -rf init *.gz
		

