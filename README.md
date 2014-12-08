Bu proje marsboard-a20 için livesuit image oluşturmak içindir.

input dizininin altına uImage (kernel), u-boot.bin (u-boot), uEnv.txt (u-boot env), bootlogo.bpm (32-bit bpm dosyayı açılışta gösterilir) ve rootfs.ext4 dosyalarını koyunca ve aşağıdaki komutu çalıştırınca

make livesuit ROOTFS=input/rootfs.ext4 

yapınca output dizini altında livesuit image i oluşturur.

