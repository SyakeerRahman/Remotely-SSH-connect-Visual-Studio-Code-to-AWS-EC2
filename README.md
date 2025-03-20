# Remotely-SSH-connect-Visual-Studio-Code-to-AWS-EC2

## EC2 and Terminal Level

During the EC2 instance creation, we can setup new key pair
<img width="620" alt="image" src="https://github.com/user-attachments/assets/f22735ab-3134-4469-9ef0-1320b28c5452" />

<img width="319" alt="image" src="https://github.com/user-attachments/assets/f7175b44-51b3-4ca6-9b53-36260c429c83" />

when trying to connect to that particular SSH instances

<img width="326" alt="image" src="https://github.com/user-attachments/assets/b46b138d-cf91-47f4-aa9b-0835ba99c02f" />

open terminal and cd to the where pem file located (currently in Downloads)
<img width="568" alt="image" src="https://github.com/user-attachments/assets/76185da8-6188-411e-821c-1c1d6dbec39f" />

## Visual Studio Code level

open vscode and search for remote ssh, install

connect to host  > configure SSH > choos C:\Users\Syakeer\.ssh\config
<img width="406" alt="image" src="https://github.com/user-attachments/assets/5116db47-470e-4ad2-b404-ffb33f79df51" />

in the config file write this

Host testing-remote-connect
  Hostname <ip address>
  User ubuntu
  IdentityFile <pem file path>
  





