# all-about-containers

I created this repo to list down all my learnings that i took in my journey to learn Kubernetes.

The following steps assume you have basic understanding of Linux
- First and foremost i think you should go through this video https://www.youtube.com/watch?v=8fi7uSYlOdc
This is a video from Liz Rice in the GO conference which makes you understand how containers are created in your machine.
There are small modifications you need to do inorder to make the example work.
  - Run the program as root user
  - Copy the existing root folder(/) and mark it as new root
  - You can try out https://btholt.github.io/complete-intro-to-containers/chroot where Brian Holt explains how chroot works
    - This is also a good learning on how containers are made in docker.
- Learn docker from TechWorld with Nana: https://www.youtube.com/playlist?list=PLy7NrYWoggjzfAHlUusx2wuDwfCrmJYcs & KodeKloud : https://www.youtube.com/watch?v=rmf04ylI2K0&t=751s
- Learn kubernetes basics from kubernetes.io hands on tutorial to understand the basics.
- For more detailed explanation and learning follow https://kube.academy/ where it starts from basics and also walks you through what is Cloud Native foundation and what are they trying to achieve to depolying kubernetes application with ease using helm.

Setup Go and run go run main.go run /bin/bash as root user in Windows(wsl)/Linux/Mac
