# Install UnitTestBot C/C++ server on Ubuntu 18.04–20.04

Whether you have Ubuntu 18.04–20.04 on your computer, Ubuntu 18.04 in WSL or a Docker container, follow the 
instructions to install the UnitTestBot C/C++ server.

1. Download a ZIP archive with the release artifact:
  ```bash
  wget https://github.com/UnitTestBot/UTBotCpp/releases/download/2022.12.0/utbot-release-2022.12.0.zip
  ```
You can choose the release on [GitHub](https://github.com/UnitTestBot/UTBotCpp/releases).

2. Install the `unzip` utility:
```bash
sudo apt-get install unzip
````
3. Unarchive the downloaded ZIP file:
  ```bash
  unzip utbot-release-2022.12.0.zip
  ```
4. Install and run the server with the _root_ privileges:
  ```bash
  sudo chmod +x unpack_and_run_utbot.sh && ./unpack_and_run_utbot.sh
  ```

To **restart** the server:
  ```bash
  sudo /utbot_distr/utbot_server_restart.sh
  ```
To **kill** the server, use `kill $pid`.

To **run** the UnitTestBot C/C++ server **on the other port**, navigate to the `utbot_distr` directory and run the script:
```sh
$ ./utbot_server_restart.sh $PORT
```
