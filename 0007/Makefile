
target-y = \
	multipleinheritance

multipleinheritance_files-y = \
	calculatorform.cpp \
	calculatorform.moc \
	../0006/ui/calculatorform.ui \
	main.cpp

multipleinheritance_cxxflags-y += \
	$(shell pkg-config Qt5Widgets --cflags) -std=c++11

multipleinheritance_ldflags-y += \
	$(shell pkg-config Qt5Widgets --libs)

include ../Makefile.lib
