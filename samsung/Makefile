# SPDX-License-Identifier: GPL-2.0

WAIPIO_BASE_DTB += ../qcom/waipio.dtb ../qcom/waipio-v2.dtb
WAIPIO_APQ_BASE_DTB += ../qcom/waipio.dtb ../qcom/waipio-v2.dtb

ifeq ($(CONFIG_SEC_PLATFORM_B4Q),y)
SAMSUNG_WAIPIO_BOARDS += \
	b4q_eur_openx_w00_r00.dts \
	b4q_eur_openx_w00_r01.dts \
	b4q_eur_openx_w00_r02.dts \
	b4q_eur_openx_w00_r03.dts \
	b4q_eur_openx_w00_r04.dts \
	b4q_eur_openx_w00_r05.dts \
	b4q_eur_openx_w00_r06.dts \
	b4q_eur_openx_w00_r07.dts \
	b4q_eur_openx_w00_r08.dts \
	b4q_eur_openx_w00_r09.dts \
	b4q_eur_openx_w00_r10.dts
endif

ifeq ($(CONFIG_SEC_PLATFORM_Q4Q),y)
SAMSUNG_WAIPIO_BOARDS += \
	q4q_eur_openx_w00_r00.dts \
	q4q_eur_openx_w00_r01.dts \
	q4q_eur_openx_w00_r02.dts \
	q4q_eur_openx_w00_r03.dts \
	q4q_eur_openx_w00_r04.dts \
	q4q_eur_openx_w00_r05.dts \
	q4q_eur_openx_w00_r06.dts \
	q4q_eur_openx_w00_r07.dts \
	q4q_eur_openx_w00_r08.dts \
	q4q_eur_openx_w00_r09.dts \
	q4q_eur_openx_w00_r10.dts \
	q4q_eur_openx_w00_r11.dts \
	q4q_eur_openx_w00_r12.dts \
	q4q_eur_openx_w00_r13.dts \
	q4q_eur_openx_w00_r14.dts
endif

waipio-overlays-dtb-y += $(SAMSUNG_WAIPIO_BOARDS) $(WAIPIO_BASE_DTB) $(WAIPIO_APQ_BASE_DTB)
dtb-y += $(SAMSUNG_WAIPIO_BOARDS) $(WAIPIO_BASE_DTB) $(WAIPIO_APQ_BASE_DTB)

always-y        := $(dtb-y)
subdir-y        := $(dts-dirs)
clean-files := *.dtb *.reverse.dts *.dtbo
