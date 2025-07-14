# miniHslink

迷你版Hslink硬件

硬件上具备TVS保护电路，整体尺寸缩小，PCB尺寸为17*28mm；

*BUG：串口复用了UART0，烧录hslink BL时可通过排针的RX TX口进行烧录，但主线hslink使用的是uart2，因此需要修改代码才能正常使用串口；因led使用了的是普通led（hslink主线使用的是ws2812），因此灯效会有问题。*

## 3D预览图
![alt text](<work flow/TOP.png>)
![alt text](<work flow/BUTTON.png>)
![alt text](<work flow/hpm_dap-0.png>)