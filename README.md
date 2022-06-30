# URL SHORTENER

A simple program that will look at the path of any incoming web request and determine if it should redirect the user to a new page. It redirects to a new page if the url path matches any url path found in the program.  

## How to run program

- Make sure your device is connected to the internet.
- Clone Repo.

    ```bash
    git clone https://github.com/0xMarvell/url-shortener.git
    ```

- Make sure to have at least Go version 1.17.6 installed on your device
- Open the code base directory in terminal
- Run program. A server will start on port 8080:
  - MacOS/linux

      ```go
      go build . && ./main
      ```

  - WIndows Powershell

      ```go
      go build .; ./main
      ```

- Open up a browser window and open a localhost page.

    ```
    localhost:8080
    ```

## Pages to expect

- Add ```/mytwt``` to the current url path in your browser and it will redirect to [this page](https://twitter.com/RokeMarvellous)
- Add ```/yaml-godoc``` to the current url path in your browser and it will redirect to [this page](https://godoc.org/gopkg.in/yaml.v2)
- Add `/mygithub` to the current url path in your browser and it will redirect to [this page](https://github.com/0xMarvell)
- Add `/sourcecode` to the current url path in your browser and it will redirect to [this page](https://github.com/0xMarvell/url-shortener)
