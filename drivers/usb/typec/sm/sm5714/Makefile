#
# Makefile for sm5714 devices
#
subdir-ccflags-y := -Wformat
obj-$(CONFIG_PDIC_SM5714)	+= sm5714_typec.o sm5714_policy.o sm5714_pd.o
GCOV_PROFILE := $(CONFIG_KUNIT)
obj-$(CONFIG_KUNIT) += test/