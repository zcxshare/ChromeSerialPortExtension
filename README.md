# Chrome Serial Port Extension
##Introduction
The Serial Port Interface is a Google Chrome browser app to allow the use of serial ports comunication inside a web page.
The app acts as a wrapper between the web pages and the serial ports.
It uses the chrome.serial API to interact with the serial ports and the chrome.runtime messaging API to exchange information with the web page.
It is also provided a simple JavaScript library to use inside the web pages to access the services provided by the app.
## 使用
1. 在插件的manifest.json中的externally_connectable.matches中添加你要使用的页面的确定的url,如:http://192.168.8.240:8181/wms/skus/skuDetail.
2. 将项目中的serial_port.js添加到你的项目中,并修改extensionId为你插件的Id
3. 参照example.html编写代码
