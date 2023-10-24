# dvswitch-setup

## Adding Names To Each CQ

```sh
cd /tmp
sudo wget "https://drive.google.com/uc?export=download&id=17Mke0HeTKGrYZDASfllM87o0KuWc-2j3" -O functions.php
sudo wget "https://drive.google.com/uc?export=download&id=1YldI5DJv6SlKTPtFMbAI1-4XCyRcO-2k" -O lh.php
sudo cp /var/www/html/include/functions.php /var/www/html/include/functions.php.bak
sudo cp /var/www/html/include/lh.php /var/www/html/include/lh.php.bak
sudo mv functions.php /var/www/html/include/functions.php
sudo mv lh.php /var/www/html/include/lh.php
sudo chmod +x /var/www/html/include/lh.php
```
<img src="https://github.com/ibshafique/dvswitch-setup/blob/main/assets/dashboard.png">
