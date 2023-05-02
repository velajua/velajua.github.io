---
layout: post
title: Tcp Local Transfer
subtitle: A TCP implemetation to send text and files over a local network.
gh-repo: velajua/tcp_local_transfer
gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/python.png
cover-img: /assets/img/python-banner_.jpg
tags: [TCP, Python, Socket, Tkinter, Ip, Server, Client]
comments: true
---

This [`repository`](https://github.com/velajua/tcp_local_transfer) contains scripts which allow the user to send both text and files from the client (sender) to the server (receiver) via a TCP connection through a local network.

## Requirements
Python 3.x
tkinter (for GUI)

The requirements can be installed by using `pip install -r requirements.txt`

## Usage
- Run the server script on the receiving end by executing `python receiver.py` on the command line.
- Run the client script on the sending end by executing `python sender.py` on the command line.
- Enter the IP address and port number of the server (receiver) into the client GUI to establish a connection.
- To send a file, click the "Browse" button and select a file from your local machine. Then click the `Send File` checkbox and the `Submit` button to transfer the file to the server. The file will be saved in the same directory as the server script.
- To send a text message, simply type the message into the text box and click the `Submit` button. The message will be displayed in the chat window on the server side.

### Sender Example

![sender](https://github.com/velajua/tcp_local_transfer/blob/main/img/sender.png)

### Receiver Example

![receiver](https://github.com/velajua/tcp_local_transfer/blob/main/img/receiver.png)

## Notes
- The default IP address used by the server is the local host (127.0.0.1).
- The default port number used is chosen at random from the available ports.
- The server script will display the received file name and the IP address and port number of the client that sent the file.
- The chat window on the server side will display the IP address and port number of the client that sent the text message, along with the message itself.
- The client script will display an error message if the connection to the server cannot be established or if the selected file cannot be sent.
