all:	result.vcd
result.vcd:	1to8.vhdl	1to8Test.vhdl
	ghdl	-a	-fsynopsys	1to8.vhdl
	ghdl	-a	-fsynopsys	1to8Test.vhdl
	ghdl	-e	-fsynopsys	demux_test
	ghdl	-r	-fsynopsys	demux_test	--vcd=result.vcd
clean:
	rm	-rf	result.vcd

