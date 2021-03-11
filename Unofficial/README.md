https://drive.google.com/drive/folders/1WTWvOp-6B54hsCDpuo_hf2JKAaUwmZFG

Partition names if you are already on OpenWRT:
mtd write xiaomi-router-kernel1.bin kernel
mtd write xiaomi-router-rootfs0.bin ubi

Partition names if you are on stock firmware:
mtd write xiaomi-router-kernel1.bin kernel1
mtd -r write xiaomi-router-rootfs0.bin rootfs0