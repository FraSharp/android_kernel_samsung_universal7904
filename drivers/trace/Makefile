#
# Makefile for trace.
#

ifeq ($(CONFIG_SOC_EXYNOS8895),y)
obj-$(CONFIG_EXYNOS_ITMON) += exynos8895-itmon.o
endif
ifeq ($(CONFIG_SOC_EXYNOS7872),y)
obj-$(CONFIG_EXYNOS_ITMON) += exynos7872-itmon.o
endif
ifeq ($(CONFIG_SOC_EXYNOS7885),y)
obj-$(CONFIG_EXYNOS_ITMON) += exynos7885-itmon.o
endif
obj-$(CONFIG_EXYNOS_SNAPSHOT) += exynos-ss.o
obj-$(CONFIG_EXYNOS_CORESIGHT) += exynos-coresight.o
obj-$(CONFIG_EXYNOS_CORESIGHT_ETM) += exynos-coresight-etm.o
obj-$(CONFIG_EXYNOS_CORESIGHT_STM) += of_coresight.o coresight.o coresight-stm.o
obj-$(CONFIG_EXYNOS_DRAMTEST) += dramtest.o

obj-$(CONFIG_EXYNOS_CONSOLE_DEBUGGER) += exynos-condbg.o exynos-condbg-dev.o
