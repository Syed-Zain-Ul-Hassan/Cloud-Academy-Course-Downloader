# Cloud Academy Course Downloader

This is a utiiliy build by @Syed-Zain-Ul-Hassan using Python, Selenium and Tkinter. 

# How to Use
You need to download this python module and should have all the libraries mentioned in requirements.txt file.

1. Install [Python](https://www.python.org/downloads/) on your computer as shown below.
<img src="https://user-images.githubusercontent.com/37849034/112749180-274e0880-8fda-11eb-87be-7ca6d14206a8.png" width="100" height="100">
3. Open the python module [Cloud Academy Course Downloader.py](https://raw.githubusercontent.com/Syed-Zain-Ul-Hassan/Cloud-Academy-DL/main/Cloud%20Academy%20Course%20Downloader.py) in RAW form and save it as .py file in your desired folder.
4. You should have [Google Chrome](https://www.google.com/chrome/thank-you.html?brand=BNSD&statcb=1&installdataindex=empty&defaultbrowser=0#) installed in your computer, then check the version of your chrome and download the relevent [ChromeDriver](https://chromedriver.chromium.org/downloads). 
5. Insatll below required python libraries. For this open [Install Pip Packages.cmd](https://raw.githubusercontent.com/Syed-Zain-Ul-Hassan/Cloud-Academy-DL/2533f9dfaa4d12d3f91eebbb77021635e7be80ab/Install%20Pip%20Packages.cmd) CMD file and save it as .cmd file in your desired folder. After downloading python (with pip), simply running it will install all required packages.

```python
pip install beautifulsoup4
pip install bs4
pip install lxml
pip install pyinstaller
pip install python-dateutil
pip install selenium
pip install times2
pip install tkintertable
pip install urllib3
pip install wget
```
5. Make changes in code where required e.g, the chromedriver.exe path etc.
```python
chromebrowser = 'YOUR_PATH_OF_EXE_FILE\\chromedriver.exe'
```
6. Run the python module.
7. A UI program will open and ask you for Email, Password and Course URL. Course URL should be correct and shouldn't contains slash (/) or any space at the end of URL.

![image](https://user-images.githubusercontent.com/37849034/112725861-223a7c00-8f3c-11eb-953d-2eec61c0a809.png)

8. Chrome browser will open, and chrome driver will login you with your provided credentials. Then chrome driver will open course and will start downloading the videos.
9. Course content will be downloaded in 'C:\\cloudAcademy' folder (you can specify your desired folder in code).
10. 




