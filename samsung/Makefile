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

ifeq ($(CONFIG_SEC_PLATFORM_B0Q),y)
SAMSUNG_WAIPIO_BOARDS += \
	b0q_usa_openw_w00_r00.dts \
	b0q_usa_openw_w00_r01.dts \
	b0q_usa_openw_w00_r02.dts \
	b0q_usa_openw_w00_r03.dts \
	b0q_usa_openw_w00_r04.dts \
	b0q_usa_openw_w00_r05.dts \
	b0q_usa_openw_w00_r06.dts \
	b0q_usa_openw_w00_r07.dts \
	b0q_usa_openw_w00_r08.dts \
	b0q_usa_openw_w00_r09.dts \
	b0q_usa_openw_w00_r10.dts \
	b0q_usa_openw_w00_r11.dts
endif

ifeq ($(CONFIG_SEC_PLATFORM_G0Q),y)
SAMSUNG_WAIPIO_BOARDS += \
	g0q_usa_openw_w00_r00.dts \
	g0q_usa_openw_w00_r01.dts \
	g0q_usa_openw_w00_r02.dts \
	g0q_usa_openw_w00_r03.dts \
	g0q_usa_openw_w00_r04.dts \
	g0q_usa_openw_w00_r05.dts \
	g0q_usa_openw_w00_r06.dts \
	g0q_usa_openw_w00_r07.dts \
	g0q_usa_openw_w00_r08.dts \
	g0q_usa_openw_w00_r09.dts \
	g0q_usa_openw_w00_r10.dts \
	g0q_usa_openw_w00_r11.dts \
	g0q_usa_openw_w00_r12.dts
endif

ifeq ($(CONFIG_SEC_PLATFORM_R0Q),y)
SAMSUNG_WAIPIO_BOARDS += \
	r0q_usa_openw_w00_r00.dts \
	r0q_usa_openw_w00_r01.dts \
	r0q_usa_openw_w00_r02.dts \
	r0q_usa_openw_w00_r03.dts \
	r0q_usa_openw_w00_r04.dts \
	r0q_usa_openw_w00_r05.dts \
	r0q_usa_openw_w00_r06.dts \
	r0q_usa_openw_w00_r07.dts \
	r0q_usa_openw_w00_r08.dts \
	r0q_usa_openw_w00_r09.dts \
	r0q_usa_openw_w00_r10.dts \
	r0q_usa_openw_w00_r11.dts \
	r0q_usa_openw_w00_r12.dts
endif

waipio-overlays-dtb-y += $(SAMSUNG_WAIPIO_BOARDS) $(WAIPIO_BASE_DTB) $(WAIPIO_APQ_BASE_DTB)
dtb-y += $(SAMSUNG_WAIPIO_BOARDS) $(WAIPIO_BASE_DTB) $(WAIPIO_APQ_BASE_DTB)

always-y        := $(dtb-y)
subdir-y        := $(dts-dirs)
clean-files := *.dtb *.reverse.dts *.dtbo
