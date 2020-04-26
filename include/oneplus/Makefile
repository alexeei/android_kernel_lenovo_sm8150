obj-$(CONFIG_OPCHAIN) += uxcore/
CORE_PATH = $(KBUILD_SRC)/include/oneplus/uxcore/core
ifeq ($(CORE_PATH),$(wildcard $(CORE_PATH)))
obj-$(CONFIG_OPCHAIN) += uxcore/core/
endif

obj-$(CONFIG_MEMPLUS) += memplus/
CORE_PATH = $(KBUILD_SRC)/include/oneplus/memplus/core
ifeq ($(CORE_PATH),$(wildcard $(CORE_PATH)))
obj-$(CONFIG_MEMPLUS) += memplus/core/
endif

obj-$(CONFIG_SMART_BOOST) += smartboost/
CORE_PATH = $(KBUILD_SRC)/include/oneplus/smartboost/core
ifeq ($(CORE_PATH),$(wildcard $(CORE_PATH)))
obj-$(CONFIG_SMART_BOOST) += smartboost/core/
endif

obj-$(CONFIG_DEFRAG) += defrag/
CORE_PATH = $(KBUILD_SRC)/include/oneplus/defrag/core
ifeq ($(CORE_PATH),$(wildcard $(CORE_PATH)))
obj-$(CONFIG_DEFRAG) += defrag/core/
endif

obj-$(CONFIG_FSC) += fsc/
obj-$(CONFIG_HOUSTON) += houston/
obj-$(CONFIG_CONTROL_CENTER) += control_center/
obj-$(CONFIG_AIGOV) += aigov/
