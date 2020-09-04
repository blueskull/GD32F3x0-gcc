# GD32F3x0-gcc
GigaDevice GD32F3x0 gcc project template

Includes official V2.02 firmware library (SPL), gcc linker script, makefile and demo program.

When downloading using stm32loader, make sure to modify the program so that it flushes the input buffer every time after resetting the IC, so that nothing printed from user program ends up in stm32loader's response buffer to confuse it.

See issue 48 of stm32loader for more detail andhow to patch up.
