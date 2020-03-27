# Cypress WiFi Host Driver Board Support Package Integration Release Notes
This library helps streamline the process of getting the WiFi Host Driver (WHD) setup and running with Cypress provided Board Support Packages (BSPs) that include a WLAN chip.

### What's Included?
* APIs for setting up the WHD interface with the BSP's SDIO interface.
* APIs for connecting WHD to LwIP memory buffers (whd_buffer_funcs_t)
* Framework for connecting WHD to LwIP network interface (whd_netif_funcs_t)

### What Changed?
#### v1.0.0
* Initial release supporting SDIO communication and the LwIP network stack

### Supported Software and Tools
This version of the RTOS Abstraction API was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox Software Environment         | 2.0     |
| GCC Compiler                              | 7.4     |
| IAR Compiler                              | 8.32    |
| ARM Compiler                              | 6.11    |


### More information
Use the following links for more information, as needed:
* [API Reference Guide](https://cypresssemiconductorco.github.io/whd-bsp-integration/html/modules.html)
* [Cypress Semiconductor](http://www.cypress.com)
* [Cypress Semiconductor GitHub](https://github.com/cypresssemiconductorco)
* [ModusToolbox](https://www.cypress.com/products/modustoolbox-software-environment)

---
© Cypress Semiconductor Corporation, 2019-2020.