# XDS110-Debug-Probe-JTAG-Adapter
JTAG Adapter board for TI-20 JTAG header.

这是一个将TI-20 JTAG接口转接为TI-14、ARM Cortex Debug 10P、ARM Serial Wire Debug and XH2.54 UART Jack.

由于一些在设计时没考虑到的线序问题，如果您需要使用常用的IDC 20Pin JTAG排线，请将TI-20 JTAG接口的简牛插座焊接在反面如图所示。

该转接板已在Texas Instrument Code Composer Studio 和 Keil MDK 和 VisualGDB环境下测试通过，可以正常仿真目标期间。

如果对DIY 一个XDS110探针刚兴趣，可以移步[OSHWHub](https://oshwhub.com/dczyewen/xds110-debug-probe)，制作您自己的XDS110探针。该设计具有标准的TI-20 JTAG Header， 可以仿真绝大多数ARM内核处理器以及TI DSP、mmWave Soc、 Wireless Socs。 详情请见[TI的产品手册](https://software-dl.ti.com/ccs/esd/documents/xdsdebugprobes/emu_xds110.html)。