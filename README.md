# manual for STM32 discovery IDE setup
### 2018 06 08 updated
### Jeeseop Kim


## Download the IDEs

* stm32cubemx: make the frame of the project based on gui
```
http://www.st.com/en/development-tools/stm32cubemx.html
```

* Truestudio: stm32 ide based on Eclipse ide, project frame made on stm32cubemx can be opened using this
```
http://www.st.com/en/development-tools/truestudio.html
```


## Prerequisites

find the 'texane/stlink' repository under github

* follow the instruction to setup st relative files(ubuntu needs manual setup. follow the instruction in this repository)

* there are some requirement packages for ubuntu. Check it(libusb-1.0 & cmake etc)



## Notes

* base code writing and compiling should use IDE downloaded

* generate .bin and .elf file format

* command for flashing
```
st-flash write /bin/slug.bin 0x08000000
```


