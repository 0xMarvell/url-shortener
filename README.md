# URL SHORTENER
A simple program that will look at the path of any incoming web request and determine if it should redirect the user to a new page. It redirects to a new page if the url path matches any url path found in the program.  

## How to run program
 - Make sure your device is connected to the internet
 - Clone Repo ( <code>https://github.com/Marvellous-Chimaraoke/url-shortener.git</code> ) or download code as zip file 
 - Make sure to have at least Go version 1.17.6 installed on your device
 - Open the code base directory in terminal
 - For MacOS, Linux, Windows Powershell - Run <code>go run main/main.go</code>. A server will start on port 8080
 - Open up a browser window and open a localhost page <code>localhost:8080</code> or <code>127.0.0.1:8080</code>

## Pages to expect
 - Add <code>/mytwt</code> to the current url path in your browser and it will redirect to <a href="https://twitter.com/RokeMarvellous">this page</a>
 - Add <code>/yaml-godoc</code> to the current url path in your browser and it will redirect to <a href="https://godoc.org/gopkg.in/yaml.v2">this page</a>
 - Add <code>/mygithub</code> to the current url path in your browser and it will redirect to <a href="https://github.com/Marvellous-Chimaraoke">this page</a>
 - Add <code>/sourcecode</code> to the current url path in your browser and it will redirect to <a href="https://github.com/Marvellous-Chimaraoke/url-shortener">this page</a>