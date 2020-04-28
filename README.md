# Qu1cksc0pe
This tool allows to analyze windows and linux executables.<br>
You can get used dll files, functions, sections, segments, urls and domains from your suspicious files.<br>
Qu1cksc0pe aims to get even more information about suspicious files and helps to user realizing what that file capable of.

- Usage: ```python3 qu1cksc0pe.py --file suspicious_file --windows/--linux```
- Alternative usage: ```python3 qu1cksc0pe.py --file [PATH TO FILE] --windows/--linux```

# Screenshot
![Screen](.Screenshot.png)

# Updates
- <b>28/04/2020</b>: Statistics upgraded.

# Scan arguments
<b>####Windows Scan####</b><br>
<b>Usage</b>: ```python3 qu1cksc0pe.py --file suspicious_file --windows```<br><br>

<b>####Metadata####</b><br>
<b>Usage</b>: ```python3 qu1cksc0pe.py --file suspicious_file --metadata```<br><br>

<b>####DLL####</b><br>
<b>Usage</b>: ```python3 qu1cksc0pe.py --file suspicious_file --dll```<br><br>

<b>####URL####</b><br>
<b>Usage</b>: ```python3 qu1cksc0pe.py --file suspicious_file --url```<br><br>

<b>####VirusTotal####</b><br>
<b>Attention!</b><i> this argument needs VirusTotal api key.</i><br>
<i>To get your api key go to the VT website</i>: <b>https://www.virustotal.com/</b>

<b>Usage for --vtFile</b>: ```python3 qu1cksc0pe.py --file suspicious_file --vtFile```<br>
<b>Usage for --vtUrl</b>: ```python3 qu1cksc0pe.py --vtUrl```<br>

<b>####Linux Scan####</b><br>
<b>Attention!</b><i> this argument needs binutils/readelf.</i><br>
<i>To get binutils/readelf do this</i>: ```sudo apt-get install binutils``` </i><br>

<b>Usage</b>: ```python3 qu1cksc0pe.py --file suspicious_elf_file --linux```<br>
