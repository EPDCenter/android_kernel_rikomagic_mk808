#
# Makefile for HDMI linux kernel module.
#

ccflags-$(CONFIG_HDMI_RK30_DEBUG) = -DDEBUG -DHDMI_DEBUG

obj-$(CONFIG_HDMI_RK30) += rk30_hdmi_hw.o rk30_hdmi_edid.o rk30_hdmi_lcdc.o rk30_hdmi_task.o rk30_hdmi_sysfs.o rk30_hdmi.o
obj-$(CONFIG_HDCP_RK30) += hdcp/
