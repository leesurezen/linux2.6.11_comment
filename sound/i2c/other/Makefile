#
# Makefile for ALSA
# Copyright (c) 2003 by Jaroslav Kysela <perex@suse.cz>
#

snd-ak4117-objs := ak4117.o
snd-ak4xxx-adda-objs := ak4xxx-adda.o
snd-tea575x-tuner-objs := tea575x-tuner.o

# Module Dependency
obj-$(CONFIG_SND_PDAUDIOCF) += snd-ak4117.o
obj-$(CONFIG_SND_ICE1712) += snd-ak4xxx-adda.o
obj-$(CONFIG_SND_ICE1724) += snd-ak4xxx-adda.o
obj-$(CONFIG_SND_FM801_TEA575X) += snd-tea575x-tuner.o
