# Semi-Automatic Custom ROM Builder [A11-M11\]
### I call it SACROMB - 2024 - Working as expected 

<br>⚬ This tool can create full flashble zip with any gsi</br>
</br>⚬ This tool support both arm32 and arm64</br>
</br>⚬ Arm64 still not supported (A64 maybe(?))</br>

# If you want to build arm32 custom rom
<br>⚬ You MUST use PHH based GSI above android 12</br>
</br>⚬ You can use GSIs Upto 3GB due to limitations of the tool.</br>

<br>⚬ Bugs in arm32</br>
<br>⚬ Non-existing Notch padding in some GSIs</br>

# If you want to build arm64 custom rom, 

<br>⚬ You MUST use PHH based GSIs above Android 10</br>
<br>⚬ ~~You can use Erfan/Nippon GSIs Android 10/11/12 only~~ 
*Might not work nor boot up*</br>

<br>⚬ Bugs in arm64</br>
<br>⚬ MTP/PTP</br>
<br>⚬ Buggy Camera in Android 13</br>


# How to Use this

<br>⚬ Fork into your github and use via github actions</br>

<br>1. Add Direct link of GSI</br>

Sourceforge example:
<br>⚬ Copy download link from your GSI then you will get link like this,</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/lineage-19.1-20230715-UNOFFICIAL-a64_bgN.img.xz/download
 ```
<br>⚬ then delete the /download then it will be like below</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/lineage-19.1-20230715-UNOFFICIAL-a64_bgN.img.xz
 ```
<br>⚬ the link must be end with .xz .img .7z .gz</br>

<br>2. Add Architecture</br>
<br>⚬ then add the arch as 32 or 64</br>

<br>3. Add Rom Name (*For identification purposes*)<br>
<br>⚬ then add the gsi name it should be [rom_name]_[version]_[sdm430]_[arm64_or_32]_[gapps_or_vanila]<br>
like this LineageOS_19.1_SDM439_ARM32_Gapps

<br>4. Download & Extract the zip file<br>
<br>⚬ cause the script is designed to compress the real flashable rom inside the one the user named it
in the workflow page.

# ⚬Telegram
<br>https://t.me/samsung_galaxy_m01_a01_m11_a11<br>
