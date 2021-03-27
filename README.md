# Cloud-Academy-Course-Downloader

This is a utifiliy build by @syed-zain-ul-hassan using Python, Selenium and Tkinter. 

# How to Use
You need to download this python module and should have all the libraries mentioned in requirements.txt file.

1. Download the python module
2. Insatll the required libraries

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
3. Make changes in code where required e.g, the chromedriver.exe path etc.
```python
chromebrowser = 'YOUR_PATH_OF_EXE_FILE\\chromedriver.exe'
parent_path = "WHERE_TO_STORE_COURSE_CONTENT e.g, F:\\cloudAcademy\\"
```
5. Run the python module.
6. A UI program will open and ask you for Email, Password and Course URL. Course URL should be correct and shouldn't contains slash (/) or any space at the end of URL.

![image](https://user-images.githubusercontent.com/37849034/112725861-223a7c00-8f3c-11eb-953d-2eec61c0a809.png)

8. Chrome browser will open, and chrome driver will login you with your provided credentials. Then chrome driver will open course and will start downloading the videos.
9. Course content will be downloaded in your mentioned folder (specifiy your target folder in code).




