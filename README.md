# adi
#project from:https://github.com/analogdevicesinc/hdl
#process : https://wiki.analog.com/resources/fpga/docs/build

## below is a note to remind me ##

#use hdl_2019_r1 branch

git checkout hdl_2019_r1

#using Vivado 2018.3 version

source /opt/Xilinx/Vivado/2018.3/settings64.sh

#go to the desired repo

$cd adi/hdl/projects/adrv9364z7020/ccbob_cmos

#then run "make"

$make

################################################################################################
#
#  runing result
#
################################################################################################

Building axi_ad9361 library [/home/willis/adi/hdl/library/axi_ad9361/axi_ad9361_ip.log] ... OK
Building util_cdc library [/home/willis/adi/hdl/library/util_cdc/util_cdc_ip.log] ... OK
Building util_axis_fifo library [/home/willis/adi/hdl/library/util_axis_fifo/util_axis_fifo_ip.log] ... OK
Building axi_dmac library [/home/willis/adi/hdl/library/axi_dmac/axi_dmac_ip.log] ... OK
Building axi_sysid library [/home/willis/adi/hdl/library/axi_sysid/axi_sysid_ip.log] ... OK
Building sysid_rom library [/home/willis/adi/hdl/library/sysid_rom/sysid_rom_ip.log] ... OK
Building axi_gpreg library [/home/willis/adi/hdl/library/axi_gpreg/axi_gpreg_ip.log] ... OK
Building util_cpack2 library [/home/willis/adi/hdl/library/util_pack/util_cpack2/util_cpack2_ip.log] ... OK
Building util_upack2 library [/home/willis/adi/hdl/library/util_pack/util_upack2/util_upack2_ip.log] ... OK
Building util_rfifo library [/home/willis/adi/hdl/library/util_rfifo/util_rfifo_ip.log] ... OK
Building util_tdd_sync library [/home/willis/adi/hdl/library/util_tdd_sync/util_tdd_sync_ip.log] ... OK
Building util_wfifo library [/home/willis/adi/hdl/library/util_wfifo/util_wfifo_ip.log] ... OK
Building util_clkdiv library [/home/willis/adi/hdl/library/xilinx/util_clkdiv/util_clkdiv_ip.log] ... OK
Building adrv9364z7020_ccbob_cmos project [/home/willis/adi/hdl/projects/adrv9364z7020/ccbob_cmos/adrv9364z7020_ccbob_cmos_vivado.log] ... OK



# project is built in /home/willis/adi/hdl/projects/adrv9364z7020/ccbob_cmos/








