vendor := $(srctree)/$(src)

ifneq "$(wildcard $(vendor)/qcom)" ""
	subdir-y += qcom
	subdir-y += audio-devicetree
	subdir-y += camera-devicetree
	subdir-y += display-devicetree
	subdir-y += mmrm-devicetree
	subdir-y += video-devicetree
endif
