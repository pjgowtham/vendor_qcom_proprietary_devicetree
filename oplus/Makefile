KALAMA_BASE_DTB += ../qcom/kalama.dtb ../qcom/kalama-v2.dtb
KALAMA_APQ_BASE_DTB += ../qcom/kalamap.dtb ../qcom/kalamap-v2.dtb

WAIPIO_BASE_DTB += ../qcom/waipio.dtb ../qcom/waipio-v2.dtb
WAIPIO_MTP_BASE_DTB += ../qcom/waipiop.dtb ../qcom/waipiop-v2.dtb

OPLUS_KALAMA_BOARDS += \
		wukong-21131-kalama-overlay.dtbo \
		salami-22811-kalama-overlay.dtbo \
		salami-22811-kalama-overlay-EVB.dtbo \
		salami-22811-kalama-overlay-T0.dtbo \
		wukong-21131-kalama-overlay-EVB.dtbo \
		xueying-22003-kalama-overlay.dtbo

OPLUS_WAIPIO_BOARDS += \
		baize-21001-waipio-overlay.dtbo \
		ferrari-21631-waipio-overlay.dtbo \
		jnc-20865-waipio-overlay.dtbo \
		kunpeng-21009-waipio-overlay.dtbo \
		mt-20845-waipio-overlay.dtbo \
		wly-20846-waipio-overlay.dtbo \
		wly-2084A-waipio-overlay.dtbo \
		wly-20846-waipio-overlay-EVB.dtbo \
		wly-2084A-waipio-overlay-EVB.dtbo \
		wly-20846-waipio-overlay-preT0.dtbo \
		wly-2084A-waipio-overlay-preT0.dtbo

kalama-overlays-dtb-y += $(OPLUS_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)
dtb-y += $(OPLUS_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)

waipio-overlays-dtb-y += $(OPLUS_WAIPIO_BOARDS) $(WAIPIO_BASE_DTB) $(WAIPIO_MTP_BASE_DTB)
dtb-y += $(OPLUS_WAIPIO_BOARDS) $(WAIPIO_BASE_DTB) $(WAIPIO_MTP_BASE_DTB)

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
