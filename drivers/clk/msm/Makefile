obj-$(CONFIG_COMMON_CLK_MSM)	+= clock.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= clock-dummy.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= clock-generic.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= clock-local2.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= clock-pll.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= clock-alpha-pll.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= clock-rpm.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= clock-voter.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= reset.o

obj-$(CONFIG_MSM_CLK_CONTROLLER_V2)	+= msm-clock-controller.o

obj-$(CONFIG_COMMON_CLK_MSM)	+= clock-debug.o

# MSM 8994
ifeq ($(CONFIG_COMMON_CLK_MSM), y)
	obj-$(CONFIG_ARCH_MSM8994)	+= clock-rpm-8994.o
	obj-$(CONFIG_ARCH_MSM8994)	+= clock-gcc-8994.o
	obj-$(CONFIG_ARCH_MSM8994)	+= clock-mmss-8994.o
	obj-$(CONFIG_ARCH_MSM8994)	+= clock-cpu-8994.o
endif

# MSM 8992
ifeq ($(CONFIG_COMMON_CLK_MSM), y)
	obj-$(CONFIG_ARCH_MSM8992)	+= clock-rpm-8992.o
	obj-$(CONFIG_ARCH_MSM8992)	+= clock-gcc-8992.o
	obj-$(CONFIG_ARCH_MSM8992)	+= clock-mmss-8992.o
	obj-$(CONFIG_ARCH_MSM8992)	+= clock-cpu-8994.o
endif

# MSM 8996
ifeq ($(CONFIG_COMMON_CLK_MSM), y)
	obj-$(CONFIG_ARCH_MSM8996) += clock-gcc-8996.o
	obj-$(CONFIG_ARCH_MSM8996) += clock-mmss-8996.o
	obj-$(CONFIG_ARCH_MSM8996) += clock-cpu-8996.o
endif

# MSM 8998
ifeq ($(CONFIG_COMMON_CLK_MSM), y)
	obj-$(CONFIG_ARCH_MSM8998)	+= clock-gcc-8998.o
	obj-$(CONFIG_ARCH_MSM8998)	+= clock-gpu-8998.o
	obj-$(CONFIG_ARCH_MSM8998)	+= clock-mmss-8998.o
	obj-$(CONFIG_ARCH_MSM8998)	+= clock-osm.o
endif

obj-$(CONFIG_COMMON_CLK_MSM)	+= gdsc.o
obj-$(CONFIG_COMMON_CLK_MSM)	+= mdss/
