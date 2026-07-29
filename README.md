<div align="center">
    <p align="center">
        <a href="https://www.freebsd.org/">
          <img width="35%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Freebsd_logo.svg" />
        </a>
    </p>

# [FreeBSD](https://wikipedia.org/wiki/FreeBSD) Toolkit
</div>

[![FreeBSD](https://img.shields.io/badge/FreeBSD-AB2B28?style=for-the-badge&logo=freebsd&logoColor=white)]()
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/playlist?list=PL9V4Zu3RroiUwctva2Y_V3L-5jzjv030s&si=_uuGUxSOMFOkrE32)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/freebsd/)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefence"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```bsd
sudo pkg update
sudo pkg upgrade
```
## Install SSH server

```bsd
sudo pkg install openssh-portable
sudo sysrc sshd_enable=YES
sudo service sshd start
```

## Install Tools

- Development Tools
    ```bsd
    sudo pkg install git curl wget gcc llvm cmake python 
    ```

- Virtualization Tools
    ```bsd
    sudo pkg install qemu
    ```

- Browser
    ```bsd
    sudo pkg install firefox chromium tor-browser
    ```
- IDE
    ```bsd
    sudo pkg install geany vscode
    ```
- Multimedia
    ```bsd
    sudo pkg install vlc
    ```

##

### My Awesome Lists
You can access the my awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/cybersecurity-dev/FreeBSD-Toolkit/graphs/contributors)!

[🔼 Back to top](#freebsd-toolkit)
