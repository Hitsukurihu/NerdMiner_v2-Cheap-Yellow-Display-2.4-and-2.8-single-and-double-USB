# NerdMiner_v2 350KH/s version for Cheap-Yellow-Displays 2.4" 2.8 (one and 2 USB-ports) S2 Mini Wemos and C3 Super Mini"

<p align="center">
  <img src="https://github.com/jpduhen/NerdMiner_v2-Cheap-Yellow-Display/blob/main/img/nmv2.jpg" alt="Demo 1">
</p>
I recently bought a 2.4 inch Cheap Yellow Display (ESP32-2432S024R) with only a USB-C connector. This CYD differs only from the 2.8" at the GPIO used for the display backlight: it uses GPIO27 instead of GPIO 21 and the RGB-LED GPIO's 16 and 17 (Green/Blue) are switched. So I compiled the latest nerdminer firmware from [evgenykzz2](https://github.com/evgenykzz2) as mentioned in this [discussion] https://github.com/BitMaker-hub/NerdMiner_v2/discussions/572 to get my 350 KH/s (!!!) 2.4" CYD Nerdminer. I added this selection to the webflasher. You can also still use the webflasher for the 2.8" CYD variants. 

 
I couldn't get the webflasher at https://flasher.bitronics.store/ to work and had to use spacehuhn's web tool. This required uploading four files and setting the appropriate offset at which they're flashed. I just wanted to make it a little easier so I forked [Fr4nkFletcher](https://github.com/Fr4nkFletcher/NerdMiner_v2-Cheap-Yellow-Display) and modified it into this.  

## Install instructions

Visit my [webflasher](https://jpduhen.github.io/NerdMiner_v2-Cheap-Yellow-Display-2.4-and-2.8-single-and-double-USB/) and click Connect

## NerdMiner configuration

After flashing, you will only need to setup your Wifi and BTC address.

Note: When the BTC address of your selected wallet is not provided, mining will not start.

#### Wifi Accesspoint


1. Connect to NerdMinerAP
   - AP: NerdMinerAP
   - PASS: MineYourCoins
2. Select your Wifi Network SSID and provide the password
3. Add your BTC address, optionally you can add an identifier, see below
4. Select invert color for the 2.4"CYD

   - If you are using public-pool.io and you want to set a custom name to your worker you can append a string with format _.yourworkername_ to the address

To remotely view your miner's progress, visit: [web.public-pool.io](https://web.public-pool.io/#/)

Happy NerdMining!
