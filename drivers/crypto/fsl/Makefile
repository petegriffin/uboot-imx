#
# Copyright 2014 Freescale Semiconductor, Inc.
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-y += sec.o
obj-$(CONFIG_FSL_CAAM) += jr.o fsl_hash.o jobdesc.o error.o
obj-$(CONFIG_CMD_BLOB)$(CONFIG_CMD_DEKBLOB) += fsl_blob.o
obj-$(CONFIG_RSA_FREESCALE_EXP) += fsl_rsa.o
obj-$(CONFIG_FSL_MFGPROT) += fsl_mfgprot.o
