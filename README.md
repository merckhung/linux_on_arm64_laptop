# Thinkpad X13s
My progress about running Linux on Thinkpad X13s (Qualcomm SC8280XP gen3)

## Off-the-shelf Linux image
1. [archiso-x13s](https://github.com/ironrobin/archiso-x13s)
2. [Debian on Thinkpad X13s instructions](https://docs.google.com/document/d/1WuxE-42ZeOkKAft5FuUk6C2fonkQ8sqNZ56ZmZ49hGI/mobilebasic#heading=h.d1689esafsky)

## Source code gathering
1. [Linaro kernel work](https://git.linaro.org/people/manivannan.sadhasivam/linux.git)
2. [Steev's kernel work](https://github.com/steev/linux.git)
3. Battery management: [qrtr](https//github.com/andersson/qrtr.git), [pd-mapper](https://github.com/andersson/pd-mapper.git)

# Microsoft Dev Kit 2023
My progress about running Linux on Microsoft Dev Kit 2023 (Qualcomm SC8280XP gen3)
1. USB Type-A doesn't work yet
2. DisplayPort doesn't work yet
3. NVMe works
4. USB Type-C works
5. Boots into Ubuntu Linux ARM64 kinetic
6. Wi-Fi driver works, but have not been tested yet
7. Bluetooth doesn't work yet

## Kernel source (DTB and defconfig)
1. [Linux kernel](https://github.com/merckhung/linux_ms_dev_kit/tree/ms-dev-kit-2023)

# Samsung Galaxy Go
My progress about running Linux on Samsung Galaxy Go (Qualcomm SC7180 gen2)

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
