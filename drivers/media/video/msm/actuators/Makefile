GCC_VERSION      := $(shell $(CONFIG_SHELL) $(PWD)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
EXTRA_CFLAGS += -Idrivers/media/video/msm
EXTRA_CFLAGS += -Idrivers/media/video/msm/io
obj-$(CONFIG_MSM_ACTUATOR) += msm_actuator.o
obj-$(CONFIG_IMX074_ACT) += imx074_act.o
obj-$(CONFIG_DW9712_ACT) += dw9712_act.o
obj-$(CONFIG_S5K3H2_ACT) += s5k3h2_act.o
obj-$(CONFIG_OV8820_ACT) += ov8820_act.o
