################################################################################
#
#   Copyright (c) 2014 Minoca Corp.
#
#    This file is licensed under the terms of the GNU General Public License
#    version 3. Alternative licensing terms are available. Contact
#    info@minocacorp.com for details. See the LICENSE file at the root of this
#    project for complete licensing information.
#
#   Binary Name:
#
#       GenFFS
#
#   Abstract:
#
#       This module builds the GenFFS build utility, which can create a single
#       FFS file.
#
#   Author:
#
#       Evan Green 6-Mar-2014
#
#   Environment:
#
#       Build
#
################################################################################

BINARY = genffs

BUILD = yes

BINPLACE = tools/bin

BINARYTYPE = build

INCLUDES += $(SRCROOT)/os/uefi/include;

OBJS = genffs.o

include $(SRCROOT)/os/minoca.mk

