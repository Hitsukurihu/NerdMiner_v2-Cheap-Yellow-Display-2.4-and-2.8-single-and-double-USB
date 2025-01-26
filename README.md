# NerdMiner_v2 for Cheap-Yellow-Displays 2.4" and 2.8"

<p align="center">
  <img src="https://github.com/jpduhen/NerdMiner_v2-Cheap-Yellow-Display/blob/main/img/nmv2.jpg" alt="Demo 1">
</p>
I couldn't get the webflasher at https://flasher.bitronics.store/ to work and had to use spacehuhn's web tool. This required uploading all four files and setting the appropriate offset at which they're flashed. I just wanted to make it a little easier so [Fr4nkFletcher](https://github.com/Fr4nkFletcher/NerdMiner_v2-Cheap-Yellow-Display) made this. 
I recently bought a 2.4 inch Cheap Yellow Display with only a USB-C connector. This CYD differs only from the 2.8" at the GPIO used for the display backlight: it uses GPIO27 instead of GPIO 21. So I compiled the latest nerdminer firmware (1.7.0) to get my 2.4" CYD Nerdminer. You can also still use the webflasher for the 2.8" CYD variants.  

## Install instructions

Visit the [webflasher](https://jpduhen.github.io/NerdMiner_v2-Cheap-Yellow-Display/flash.html) and click Connect

## NerdMiner configuration

After flashing, you will only need to setup your Wifi and BTC address.

Note: When the BTC address of your selected wallet is not provided, mining will not start.

#### Wifi Accesspoint


1. Connect to NerdMinerAP
   - AP: NerdMinerAP
   - PASS: MineYourCoins
2. Select your Wifi Network SSID and provide the password
3. Add your BTC address
4. Select invert color

   - If you are using public-pool.io and you want to set a custom name to your worker you can append a string with format _.yourworkername_ to the address

To remotely view your miner's progress, visit: [web.public-pool.io](https://web.public-pool.io/#/)

Happy NerdMining!
