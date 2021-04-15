# thinkpad

Check your network hardware:
```bash
lspci | grep Network
```

Network controller: Intel Corporation Wireless-AC 9462

Download Wifi Driver: https://wireless.wiki.kernel.org/_media/en/users/drivers/iwlwifi-9000-pu-b0-jf-b0-34.618819.0.tgz

copy wifi firmware file:
```bash
sudo cp iwlwifi-9000-pu-b0-jf-b0-34.ucode /lib/firmware
```

restart network:
```bash
sudo service network-manager restart
```

Source: https://www.intel.com/content/www/us/en/support/articles/000005511/wireless.html

