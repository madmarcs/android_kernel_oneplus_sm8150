# SPDX-License-Identifier: GPL-2.0
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY_QCOM),y)
dtb-$(CONFIG_ARCH_QCOM)	+= apq8016-sbc.dtb
dtb-$(CONFIG_ARCH_QCOM)	+= apq8096-db820c.dtb
dtb-$(CONFIG_ARCH_QCOM)	+= ipq8074-hk01.dtb
dtb-$(CONFIG_ARCH_QCOM)	+= msm8916-mtp.dtb
dtb-$(CONFIG_ARCH_QCOM)	+= msm8992-bullhead-rev-101.dtb
dtb-$(CONFIG_ARCH_QCOM)	+= msm8994-angler-rev-101.dtb
dtb-$(CONFIG_ARCH_QCOM)	+= msm8996-mtp.dtb
ifeq ($(CONFIG_ARM64),y)
dtb-$(CONFIG_ARCH_QCS405) += qcs405-rumi.dtb \
		qcs405-iot-sku1.dtb \
		qcs405-iot-sku2.dtb \
		qcs405-iot-sku3.dtb \
		qcs405-iot-sku4.dtb \
		qcs405-iot-sku5.dtb \
		qcs405-iot-sku6.dtb \
		qcs405-iot-sku7.dtb \
		qcs405-iot-sku8.dtb \
		qcs405-iot-sku9.dtb \
		qcs405-iot-sku10.dtb \
		qcs405-iot-sku11.dtb \
		qcs405-iot-sku12.dtb \
		qcs401-iot-sku1.dtb
else
dtb-$(CONFIG_ARCH_QCS405) += qcs403-iot-sku1.dtb \
			qcs403-iot-sku2.dtb \
			qcs403-iot-sku3.dtb \
			qcs403-iot-sku4.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SM8150) += \
		sm8150-cdp-overlay.dtbo \
		sm8150-mtp-overlay.dtbo \
		sm8150-rumi-overlay.dtbo \
		sm8150-qrd-overlay.dtbo \
		sm8150-qrd-dvt-overlay.dtbo \
		sa8155-adp-star-overlay.dtbo \
		sa8155p-adp-star-overlay.dtbo \
		sa8155-v2-adp-air-overlay.dtbo \
                sa8155p-v2-adp-air-overlay.dtbo \
		sa8155-adp-alcor-overlay.dtbo \
		sa8155p-adp-alcor-overlay.dtbo \
		sm8150-sdx50m-cdp-overlay.dtbo \
		sm8150-sdx50m-mtp-overlay.dtbo \
		sm8150-sdx50m-mtp-2.5k-panel-overlay.dtbo \
		sm8150-sdx50m-qrd-overlay.dtbo \
		sm8150-sdxprairie-cdp-overlay.dtbo \
		sm8150-sdxprairie-mtp-overlay.dtbo \
		sm8150-sdxprairie-v2-cdp-overlay.dtbo \
		sm8150-sdxprairie-v2-mtp-overlay.dtbo \
		sm8150-hdk-overlay.dtbo

sm8150-cdp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-mtp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-rumi-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-qrd-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-hdk-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-qrd-dvt-overlay.dtbo-base := sm8150-v2.dtb sm8150p-v2.dtb
sa8155-adp-star-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-adp-star-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
sa8155-v2-adp-air-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-v2-adp-air-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
sa8155-adp-alcor-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-adp-alcor-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
sm8150-sdx50m-cdp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdx50m-mtp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdx50m-mtp-2.5k-panel-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdx50m-qrd-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdxprairie-cdp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdxprairie-mtp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
endif
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SM8150) += \
		sm8150-mtp-overlay.dtbo \
		sm8150-sdxprairie-mtp-overlay.dtbo \
		guacamole-overlay-t0.dtbo \
		guacamole-overlay-evt1.dtbo \
		guacamole-overlay-evt2.dtbo \
		guacamole-overlay-evt2-second.dtbo \
		guacamole-overlay-evt3.dtbo \
		guacamole-overlay-dvt.dtbo \
		guacamole-overlay-pvt.dtbo \
		guacamoleb-overlay-t0.dtbo \
		guacamoleb-overlay-evt.dtbo \
		guacamoleb-overlay-dvt.dtbo \
		guacamoleb-overlay-pvt.dtbo \
		sm8150-sdx50m-mtp-overlay.dtbo \
		guacamole-sdx50m-overlay-t0.dtbo \
		guacamole-sdx50m-overlay-evt1.dtbo \
		guacamole-sdx50m-overlay-evt2.dtbo \
		guacamole-sdx50m-overlay-dvt.dtbo \
		guacamole-sdx50m-overlay-pvt.dtbo \
		guacamoles-sdx50m-overlay-t0.dtbo \
		guacamoles-sdx50m-overlay-evt.dtbo \
		guacamoles-sdx50m-overlay-dvt.dtbo \
		guacamoles-sdx50m-overlay-pvt.dtbo \
		hotdogb-overlay-t0.dtbo \
		hotdogb-overlay-evt.dtbo \
		hotdogb-overlay-evt-second.dtbo \
		hotdogb-overlay-dvt.dtbo \
		hotdogb-overlay-dvt-second.dtbo \
		hotdogb-overlay-pvt.dtbo \
		hotdogb-overlay-pvt-second.dtbo \
		hotdog-overlay-t0.dtbo \
		hotdog-overlay-evt.dtbo \
		hotdog-overlay-dvt.dtbo \
		hotdog-overlay-pvt.dtbo

sm8150-mtp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdxprairie-mtp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-overlay-t0.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-overlay-evt1.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-overlay-evt2.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-overlay-evt2-second.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-overlay-evt3.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-overlay-dvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-overlay-pvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamoleb-overlay-t0.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamoleb-overlay-evt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamoleb-overlay-dvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamoleb-overlay-pvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdx50m-mtp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-sdx50m-overlay-t0.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-sdx50m-overlay-evt1.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-sdx50m-overlay-evt2.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-sdx50m-overlay-dvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamole-sdx50m-overlay-pvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamoles-sdx50m-overlay-t0.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamoles-sdx50m-overlay-evt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamoles-sdx50m-overlay-dvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
guacamoles-sdx50m-overlay-pvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdog-overlay-t0.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdog-overlay-evt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdog-overlay-dvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdog-overlay-pvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdogb-overlay-t0.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdogb-overlay-evt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdogb-overlay-evt-second.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdogb-overlay-dvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdogb-overlay-dvt-second.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdogb-overlay-pvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
hotdogb-overlay-pvt-second.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdxprairie-v2-cdp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sm8150-sdxprairie-v2-mtp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
else
dtb-$(CONFIG_ARCH_SM8150)	+= sm8150-rumi.dtb \
	sm8150-mtp.dtb \
	sm8150-cdp.dtb \
	sm8150-qrd.dtb \
	sa8155-adp-star.dtb \
	sa8155p-adp-star.dtb \
	sa8155-v2-adp-star.dtb \
	sa8155p-v2-adp-star.dtb \
	sa8155-v2-adp-air.dtb \
	sa8155p-v2-adp-air.dtb \
	sa8155-adp-alcor.dtb \
	sa8155p-adp-alcor.dtb \
	sm8150-v2-rumi.dtb \
	sm8150-v2-mtp.dtb \
	sm8150-v2-cdp.dtb \
	sm8150-v2-qrd.dtb \
	sm8150-v2-qrd-dvt.dtb \
	sm8150p-mtp.dtb \
	sm8150p-cdp.dtb \
	sm8150p-qrd.dtb \
	sm8150p-v2-mtp.dtb \
	sm8150p-v2-cdp.dtb \
	sm8150p-v2-qrd.dtb \
	sm8150-hdk.dtb \
	sm8150p-hdk.dtb
endif

dtb-$(CONFIG_QTI_GVM) += sa8155-vm.dtb \
	sa8155-vm-lv.dtb \
	sa8155-vm-lv-mt.dtb \
	sa8155-vm-la-mt.dtb \
	sa6155p-vm.dtb \
	sa8195-vm.dtb

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SDMSHRIKE) += \
		sdmshrike-cdp-overlay.dtbo \
		sdmshrike-mtp-overlay.dtbo \
		sa8195p-adp-star-overlay.dtbo

sdmshrike-cdp-overlay.dtbo-base := sdmshrike.dtb sdmshrike-v2.dtb
sdmshrike-mtp-overlay.dtbo-base := sdmshrike.dtb sdmshrike-v2.dtb
sa8195p-adp-star-overlay.dtbo-base := sa8195p.dtb
else
dtb-$(CONFIG_ARCH_SDMSHRIKE)	+= sdmshrike-rumi.dtb \
	sdmshrike-mtp.dtb \
	sdmshrike-cdp.dtb \
	sdmshrike-v2-mtp.dtb \
	sa8195p-adp-star.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SM6150) += \
		sm6150-rumi-overlay.dtbo \
		sm6150-qrd-overlay.dtbo \
		sm6150-idp-overlay.dtbo \
		sm6150p-qrd-overlay.dtbo \
		sm6150p-idp-overlay.dtbo \
		sm6150-external-codec-idp-overlay.dtbo \
		sm6150-usbc-idp-overlay.dtbo \
		sm6150-usbc-minidp-idp-overlay.dtbo \
		sm6150-cmd-mode-display-idp-overlay.dtbo \
		sa6155-adp-star-overlay.dtbo \
		sa6155p-adp-star-overlay.dtbo \
		sa6155-adp-air-overlay.dtbo \
		sa6155p-adp-air-overlay.dtbo \
		sa6155p-v2-adp-star-overlay.dtbo \
		sa6155p-v2-adp-air-overlay.dtbo \
		qcs610-iot-overlay.dtbo \
		qcs410-iot-overlay.dtbo

sm6150-rumi-overlay.dtbo-base := sm6150.dtb
sm6150-qrd-overlay.dtbo-base := sm6150.dtb
sm6150-idp-overlay.dtbo-base := sm6150.dtb
sm6150p-qrd-overlay.dtbo-base := sm6150p.dtb
sm6150p-idp-overlay.dtbo-base := sm6150p.dtb
sm6150-external-codec-idp-overlay.dtbo-base := sm6150.dtb
sm6150-usbc-idp-overlay.dtbo-base := sm6150.dtb
sm6150-usbc-minidp-idp-overlay.dtbo-base := sm6150.dtb
sm6150-cmd-mode-display-idp-overlay.dtbo-base := sm6150.dtb
sa6155-adp-star-overlay.dtbo-base := sa6155.dtb
sa6155p-adp-star-overlay.dtbo-base := sa6155p.dtb
sa6155p-v2-adp-star-overlay.dtbo-base := sa6155p.dtb
sa6155-adp-air-overlay.dtbo-base := sa6155.dtb
sa6155p-adp-air-overlay.dtbo-base := sa6155p.dtb
sa6155p-v2-adp-air-overlay.dtbo-base := sa6155p.dtb
qcs610-iot-overlay.dtbo-base := sm6150.dtb
qcs410-iot-overlay.dtbo-base := sm6150.dtb
else
dtb-$(CONFIG_ARCH_SM6150)	+= sm6150-rumi.dtb \
	sm6150-qrd.dtb \
	sm6150-idp.dtb \
	sm6150p-qrd.dtb \
	sm6150p-idp.dtb \
	sm6150-external-codec-idp.dtb \
	sm6150-usbc-idp.dtb \
	sm6150-usbc-minidp-idp.dtb \
	sm6150-cmd-mode-display-idp.dtb \
	sa6155-adp-star.dtb \
	sa6155p-adp-star.dtb \
	sa6155-adp-air.dtb \
	sa6155p-adp-air.dtb \
	sa6155p-v2-adp-star.dtb \
	sa6155p-v2-adp-air.dtb \
	qcs610-iot.dtb \
	qcs410-iot.dtb

endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SDMMAGPIE) += \
		sdmmagpie-idp-overlay.dtbo \
		sdmmagpie-atp-overlay.dtbo \
		sdmmagpie-rumi-overlay.dtbo \
		sdmmagpie-qrd-overlay.dtbo \
		sdmmagpiep-idp-overlay.dtbo \
		sdmmagpiep-atp-overlay.dtbo \
		sdmmagpiep-qrd-overlay.dtbo \
		sdmmagpie-external-codec-idp-overlay.dtbo \
		sdmmagpie-usbc-idp-overlay.dtbo \
		sdmmagpie-dual-display-idp-overlay.dtbo

sdmmagpie-idp-overlay.dtbo-base := sdmmagpie.dtb
sdmmagpie-atp-overlay.dtbo-base := sdmmagpie.dtb
sdmmagpie-rumi-overlay.dtbo-base := sdmmagpie.dtb
sdmmagpie-qrd-overlay.dtbo-base := sdmmagpie.dtb
sdmmagpiep-idp-overlay.dtbo-base := sdmmagpiep.dtb
sdmmagpiep-atp-overlay.dtbo-base := sdmmagpiep.dtb
sdmmagpiep-qrd-overlay.dtbo-base := sdmmagpiep.dtb
sdmmagpie-external-codec-idp-overlay.dtbo-base := sdmmagpie.dtb
sdmmagpie-usbc-idp-overlay.dtbo-base := sdmmagpie.dtb
sdmmagpie-dual-display-idp-overlay.dtbo-base := sdmmagpie.dtb
else
dtb-$(CONFIG_ARCH_SDMMAGPIE)	+= sdmmagpie-rumi.dtb \
	sdmmagpie-idp.dtb \
	sdmmagpie-atp.dtb \
	sdmmagpie-qrd.dtb \
	sdmmagpiep-idp.dtb \
	sdmmagpiep-atp.dtb \
	sdmmagpiep-qrd.dtb \
	sdmmagpie-external-codec-idp.dtb \
	sdmmagpie-usbc-idp.dtb \
	sdmmagpie-dual-display-idp.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_TRINKET) += \
		trinket-rumi-overlay.dtbo \
		trinket-idp-overlay.dtbo \
		trinket-qrd-overlay.dtbo \
		trinket-external-codec-idp-overlay.dtbo \
		trinket-usbc-external-codec-idp-overlay.dtbo \
		trinket-usbc-idp-overlay.dtbo \
		trinket-dp-idp-overlay.dtbo

trinket-rumi-overlay.dtbo-base := trinket.dtb
trinket-idp-overlay.dtbo-base := trinket.dtb
trinket-qrd-overlay.dtbo-base := trinket.dtb
trinket-external-codec-idp-overlay.dtbo-base := trinket.dtb
trinket-usbc-external-codec-idp-overlay.dtbo-base := trinket.dtb
trinket-usbc-idp-overlay.dtbo-base := trinket.dtb
trinket-dp-idp-overlay.dtbo-base := trinket.dtb
else
dtb-$(CONFIG_ARCH_TRINKET)	+= trinket-rumi.dtb \
	trinket-idp.dtb \
	trinket-qrd.dtb \
	trinket-external-codec-idp.dtb \
	trinket-usbc-external-codec-idp.dtb \
	trinket-usbc-idp.dtb \
	trinket-dp-idp.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_ATOLL) += \
		atoll-idp-overlay.dtbo\
		atoll-qrd-overlay.dtbo\
		atoll-rumi-overlay.dtbo

atoll-idp-overlay.dtbo-base := atoll.dtb
atoll-qrd-overlay.dtbo-base := atoll.dtb
atoll-rumi-overlay.dtbo-base := atoll.dtb
else
dtb-$(CONFIG_ARCH_ATOLL)	+= atoll-idp.dtb\
	atoll-qrd.dtb\
	atoll-rumi.dtb
endif

dtb-$(CONFIG_ARCH_SDXPRAIRIE) += sdxprairie-rumi.dtb \
	sdxprairie-cdp.dtb \
	sdxprairie-dsda-cdp.dtb \
	sdxprairie-mtp.dtb \
	sdxprairie-pcie-ep-mtp.dtb \
	sdxprairie-mtp-cpe.dtb \
	sdxprairie-cdp-cpe.dtb \
	sdxprairie-cdp-256.dtb \
	sdxprairie-mtp-256.dtb \
	sdxprairie-mtp-aqc.dtb \
	sdxprairie-dsda-mtp.dtb \
	sdxprairie-v2-cdp.dtb \
	sdxprairie-v2-mtp.dtb \
	sa515m-ccard.dtb \
	sa515m-ccard-pcie-ep.dtb \
	sa515m-ccard-usb-ep.dtb

ifeq ($(CONFIG_ARM64),y)
always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
else
targets += dtbs
targets += $(addprefix ../, $(dtb-y))

$(obj)/../%.dtb: $(src)/%.dts FORCE
	$(call if_changed_dep,dtc)

dtbs: $(addprefix $(obj)/../,$(dtb-y))
endif
clean-files	:= *.dtb *.dtbo
