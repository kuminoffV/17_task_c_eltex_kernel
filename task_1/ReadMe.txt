Kernel: arch/arm/boot/zImage is ready

Запуск: 

БЕЗ ФАЙЛОВОЙ СИСТЕМЫ
QEMU_AUDIO_DRV=none qemu-system-arm -M vexpress-a9 -kernel zImage -dtb vexpress-v2p-ca9.dtb -append "console=ttyAMA0" -nographic

или же 
make go

Выход:
CTRL+A потом X
