## WARNING:

! This is my adaptation of the marlin 2.x for SKR 2.0
! use this as your own risk !

### Main params:
- printing configuration: 210x210x240mm
- pla 210@60 / abs 250@80
- mecaniccal switch based on anet a8
- Main board: SKR 2.0 rev B (f429) with 2208 in UART MODE
- Motors nema 17s: 1X/Y and 2xZ
- based on a custom AM8

## Original content

### review
　You can find a complete review with detailed features of our electronics in [Spanish](https://3dwork.io/complete-guide-skr2/) and [English](https://3dwork.io/en/complete-guide-skr2/) on [3dwork.io](https://3dwork.io/).

### Note
  * Due to the shortage of MCU, SKR-2 has two versions with `STM32F407VGT6` and `STM32F429VGT6`. Note that we need to set up different environments in Marlin [platformio.ini](https://github.com/bigtreetech/SKR-2/blob/master/Firmware/Marlin-bugfix-2.0.9.2.x/platformio.ini).<br/>
  * `default_envs = BIGTREE_SKR_2`<br/>
    <img src=Images/f407.jpg width="400" /><br/>
  * `default_envs = BIGTREE_SKR_2_F429`<br/>
    <img src=Images/f429.jpg width="400" /><br/>
