# OpenWRT-CI
云编译OpenWRT固件
官方版：
https://github.com/immortalwrt/immortalwrt.git

高通版：
https://github.com/VIKINGYFY/immortalwrt.git

参考源码：
https://github.com/VIKINGYFY/OpenWRT-CI

# 固件简要说明：
MEDIATEK系列、QUALCOMMAX系列、ROCKCHIP系列、X86系列。

# 目录简要说明：
workflows——自定义CI配置
Scripts——自定义脚本
Config——自定义配置

# 修改内容：
1、增加OpenAppFilter
2、主题改成Argon
3、定时译改成手动编译，执行对应的action编译对应的固件
4、增加pushplus推送，环境变量增加PUSHPLUS_TOKEN，输入对应值，编译完成后会发送通知

## MediaTek平台（mediatek_filogic）
- abt_asr3000
- cetron_ct3003
- cetron_ct3003-ubootmod
- cmcc_a10-stock
- cmcc_a10-ubootmod
- cmcc_rax3000m
- cmcc_rax3000me
- cudy_tr3000-256mb-v1
- cudy_tr3000-v1
- cudy_tr3000-v1-ubootmod
- glinet_gl-mt3000
- glinet_gl-mt6000
- glinet_gl-x3000
- glinet_gl-xe3000
- h3c_magic-nx30-pro
- h3c_magic-nx30-pro-nmbm
- huasifei_wh3000-emmc
- imou_lc-hx3001
- jcg_q30-pro
- jdcloud_re-cp-03
- konka_komi-a31
- netcore_n60
- netcore_n60-pro
- nokia_ea0326gmp
- qihoo_360t7
- ruijie_rg-x60-pro
- tplink_tl-7dr7230-v1
- tplink_tl-7dr7230-v2
- tplink_tl-7dr7250-v1
- tplink_tl-xdr4288
- tplink_tl-xdr6086
- tplink_tl-xdr6088
- tplink_tl-xtr8488
- xiaomi_mi-router-ax3000t
- xiaomi_mi-router-ax3000t-ubootmod
- xiaomi_mi-router-wr30u-stock
- xiaomi_mi-router-wr30u-ubootmod
- xiaomi_redmi-router-ax6000-stock
- xiaomi_redmi-router-ax6000-ubootmod
- zyxel_ex5700-telenor
## Rockchip平台（rockchip_armv8）
- friendlyarm_nanopc-t4
- friendlyarm_nanopc-t6
- friendlyarm_nanopi-r2c
- friendlyarm_nanopi-r2c-plus
- friendlyarm_nanopi-r2s
- friendlyarm_nanopi-r3s
- friendlyarm_nanopi-r4s
- friendlyarm_nanopi-r4se
- friendlyarm_nanopi-r4s-enterprise
- friendlyarm_nanopi-r5c
- friendlyarm_nanopi-r5s
- friendlyarm_nanopi-r6c
- friendlyarm_nanopi-r6s
- lunzn_fastrhino-r66s
- lunzn_fastrhino-r68s
- xunlong_orangepi-5
- xunlong_orangepi-5-plus
- xunlong_orangepi-r1-plus
- xunlong_orangepi-r1-plus-lts
## X86平台
- 支持所有X86_64架构的设备（CONFIG_TARGET_ALL_PROFILES=y）
- 提供GRUB和VMDK镜像格式
## Qualcomm平台
### IPQ50XX系列
- jdcloud_re-cs-03
### IPQ60XX系列
- anysafe_e1
- cmiot_ax18
- glinet_gl-ax1800
- glinet_gl-axt1800
- jdcloud_re-cs-02
- jdcloud_re-ss-01
- link_nn6000-v1
- link_nn6000-v2
- linksys_mr7350
- linksys_mr7500
- qihoo_360v6
- redmi_ax5
- redmi_ax5-jdcloud
- xiaomi_ax1800
- zn_m2
### IPQ807X系列
- aliyun_ap8220
- linksys_homewrk
- linksys_mx4200v1
- linksys_mx4200v2
- linksys_mx4300
- linksys_mx5300
- linksys_mx8500
- qnap_301w
- redmi_ax6
- redmi_ax6-stock
- xiaomi_ax3600
- xiaomi_ax3600-stock
- xiaomi_ax9000
- xiaomi_ax9000-stock
