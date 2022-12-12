# Nuclei OpenOCD Distribution

## 2022.12

This is release 2022.12 of openocd.

* nor/spi:add w25q512jv
* add 'init resethalt' command
* feature:auto search custom flashloader path
* fix riscv-debug v0.11 call riscv_run_algorithm error.


## 2022.08

This is release 2022.08 of openocd.

* spi_nor:add xt25f256b mac25l1633e gd25q80b gd25le32e en25s40a by25q32al fm25q128 gd25B512me.
* merge upstream https://github.com/riscv/riscv-openocd commit id 52177592f9d3afc6a008f8e1b321cf74e823018f.
* custom flashloader don't rely on 'src/flash/nor/spi.c', fix memory leaks bug.


## 2022.04

This is release 2022.04 of openocd.

* add DSP ucode csr register
* Adjustment simulation timeout param
* Fix after write_bank/write_image command read date error bug
* Add custom flash loader in openocd, please refer wiki for how to use it
* Custom flash loader: add 'simulation' parameter for simulation test.


## 2022.01

This is release 2022.01 of openocd.

* optimize cjtag support for nuclei cjtag
* spi_nor: add BoHong bh25d80a bh25d40a bh25d20a
* spi_nor: Add Micron MT25QU512
* flash:"flash bank" command add simulation param
* add nuclei all custom csr
* spi_nor: Add MXIC MX25U51245G
* transport/ftdi: Update to new standard cJTAG sequence
* flash: add XinSheng RISC-V MCU CM32M4xxR flash program driver
* Add nuspi loader support.
* Add nuspi SPI flash driver support.
* Enable multi-core debug.
* Previous fespi loader will be rerouted to nuspi loader.
* Changes are based on [openocd for riscv 0.11.0](https://github.com/riscv/riscv-openocd/commit/6edf98db7f98c5e24bc51cf98419bdf5bbc530e6)
