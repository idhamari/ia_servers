# Useful Server Tips

Since I started using [proxmox]() and testing different servers, I am adding here some tips, links, and useful settings for beginners.

## My Setup:

- Proxmox machine with number of containers and virtual machines. The proxmox server has access to GPUs and Physical HDD
- A router that allows forwarding to specific machine on the networks. In my case it forwards to the Proxmox machine.
- Nginx installed on the Proxmox server, it accepts the coming requests from my public domain and its subdomains then forwards them to the correct machine
- A main domain that has number of sub-domains e.g. the main domain is connected to my public IP address via a script runs on Proxmox server
  - main-domain.com
  - sub1.main-domain.com
  - sub2.main-domain.com
- I don't have a static IP, so I am using paid Dynamic DNS service that allows updating the IP automatically for my domains.
- I am using a free certificate service that needed to be updated every a few months (this done automatically via a script).
- I am using Ubuntu as operating system

I will try to write these tutorial whenever I have time.

## [Cost of the setup]()
   
  - One time cost of a good router. 
  - One time cost of buying a domain.
  - Monthly cost of electricity. 
  - Monthly cost of good internet connection.
  - Yearly rent of Dynamic DNS service.
  - One can get also extra support service from Proxmox and other web apps if needed.


## [Installing Proxmox server]()


## [Installing Nginx and certificates]()

Reverse proxy server that allows access multiple machines using one IP address

## [Installing Next cloud]()

File storage server with video conference and other nice features

## [Installing Keycloak]()

Authentication server that allws login to different services

## [Installing TrueNAS]()

Shared storage server

## [Installing ShareLatex]()

Latex server

## [Installing MailCow]()

Email server

## [Installing Notebook server]()

## [Installing DNN server]()

Configure access to GPU and runs deep learning tool
