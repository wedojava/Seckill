# Seckill


## Steps

### Install Selenium
```python
pip3 install selenium
```

### Install ChromeDriver

> Reference:
> https://www.jianshu.com/p/39716ea15d99


#### 1. download driver

[This is the official ChromeDriver download address.](https://chromedriver.storage.googleapis.com/index.html)

[taobao mirror of chromedriver](http://npm.taobao.org/mirrors/chromedriver/)

Check out the version of Chrome, view `chrome://settings/help` by your Chrome

Use The ChromeDriver download link to find the Chrome version and download it based on your computer’s platform type.

Download zip packages:

```
wget https://chromedriver.storage.googleapis.com/86.0.4240.22/chromedriver_mac64.zip
```


#### 2. setup it

Once the download is complete, UNZIP IT and place it in the **Scripts** folder under the Python installation path, or copy driver file to `/usr/bin` on MacOS.

Windows: `<your python root folder>\\Scripts`
Mac OS: `/usr/bin`

**Notice:**  On mac, it can't copy anything to the folder, so, copy it to any place your python can invoke it.
