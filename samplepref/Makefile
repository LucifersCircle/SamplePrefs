include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = samplepref
samplepref_FILES = iDHSamplePrefsRootListController.m
samplepref_INSTALL_PATH = /Library/PreferenceBundles
samplepref_FRAMEWORKS = UIKit
samplepref_PRIVATE_FRAMEWORKS = Preferences

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/samplepref.plist$(ECHO_END)
