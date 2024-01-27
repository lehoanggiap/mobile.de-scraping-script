![Build Status](https://github.com/lehoanggiap/mobile.de-scraping-script/actions/workflows/build.yml/badge.svg)
<h2>What the hell I'm trying to do with this source code?</h2>
Scraping website http://Mobile.de?lang=en

<h2>What I can not do?</h2>
I still get stuck with the bot detection from this website. From my guess, it is using the akam bot, you can read the links here: 
<ul>
    <li>https://www.akamai.com/</li>
    <li>https://stackoverflow.com/questions/63972523/selenium-access-denied</li>
</ul>

<b>I tried to replace cdc_ in chromedriver.exe and set the driver_execute_path=path/to/chromedriver.exe in to the code like below but it is useless</b>

```python
driver = uc.Chrome(headless=False,use_subprocess=False,version_main=version_main,options=options,driver_executable_path="C:/Users/GiaplH/Downloads/chromedriver-win64/chromedriver.exe")
```

<h2>What do you need to run this repostiory?</h2>
<h3>Programming</h3>
<ul>
    <li>Python 3.9.0</li>
    <li>undetected_chromedriver 3.4.7</li>
    <li>selenium 4.9.1</li>
</ul>

<h3>Browsing</h3>
<ul>
    <li>Chrome version: lastest</li>
</ul>

