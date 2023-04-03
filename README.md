# Lenovo Thinkpad X13s
My progress about running Linux on Thinkpad X13s (Qualcomm SC8280XP gen3)

## Off-the-shelf Linux image
1. [archiso-x13s](https://github.com/ironrobin/archiso-x13s)
2. [Debian on Thinkpad X13s instructions](https://docs.google.com/document/d/1WuxE-42ZeOkKAft5FuUk6C2fonkQ8sqNZ56ZmZ49hGI/mobilebasic#heading=h.d1689esafsky)
3. Ubuntu concept team - [x13s](https://launchpad.net/~ubuntu-concept/+archive/ubuntu/x13s)
4. Ubuntu Concept X13s 23.04 (Lunar Lobster) Daily Build - [link](https://people.canonical.com/~xnox/ubuntu-concept/full/daily-live/current/)

## Source code gathering
1. [Linaro kernel work](https://git.linaro.org/people/manivannan.sadhasivam/linux.git)
2. [Steev's kernel work](https://github.com/steev/linux.git)
3. Battery management: [qrtr](https//github.com/andersson/qrtr.git), [pd-mapper](https://github.com/andersson/pd-mapper.git)

## Functionality
1. With Ubuntu 23.04 (Development Build)
2. Steev's Linux on linux-6.3-rc4 branch (laptop_defconfig, built-in ext4 and NVMe drivers)
3. GPU works (a690_gmu.bin & a690_sqe.fw), bluetooth works, 5G Wi-Fi works (board-2.bin), Sound works (SC8280XP-LENOVO-X13S-tplg.bin)
4. [Watch the video](https://twitter.com/merckhung/status/1642802461177155584)

# Microsoft Dev Kit 2023
My progress about running Linux on Microsoft Dev Kit 2023 (Qualcomm SC8280XP gen3)

![229471066-4e6c36de-13b4-44e5-9cf3-dfba9df92154](https://user-images.githubusercontent.com/1893015/229475366-cc29da80-dd7a-4d80-9366-df4452dbaffa.jpeg)

1. USB Type-A doesn't work yet
2. DisplayPort doesn't work yet
3. NVMe works
4. USB Type-C works!

5. Boots into Ubuntu Linux ARM64 kinetic
6. Wi-Fi driver works, but have not been tested yet
7. Bluetooth doesn't work yet

## Kernel source (DTB and defconfig)
1. [Linux kernel](https://github.com/merckhung/linux_ms_dev_kit/tree/ms-dev-kit-2023)

# Samsung Galaxy Go
My progress about running Linux on Samsung Galaxy Go (Qualcomm SC7180 gen2)

![198504487-5b67ad7a-3e8d-4623-9db2-e276fda4a162](https://user-images.githubusercontent.com/1893015/229474877-8e6feeb1-ce5c-4369-9ca6-22e8ebace527.jpeg)

## With ACPI
1. Boots into Ubuntu Linux ARM64 kinetic
2. USB works
3. Built-in keywork and touchpad don't work
4. Wi-Fi doesn't work yet
5. Bluetooth doesn't work yet.
6. UFS eMMC works

## With Device Tree
1. No UFS
2. Built-in keywork and touchpad work
3. Boots into Debian Linux from USB disk
