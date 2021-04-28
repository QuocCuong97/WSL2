# WSL2
- Download WSL2: https://aka.ms/wsl2
- Các feature cần enable khi sử dụng WSL2:
    - Hyper-V Platform
    - Windows Subsystem for Linux
- Set version mặc định cho WSL :
    ```powershell
    wsl --set-default-version 2
    ```
- Thay đổi version WSL cho instance :
    ```powershell
    wsl --set-version Ubuntu-20.04 2
    ```
- Show các instance WSL đã cài đặt trên máy :
    ```powershell
    wsl -l -v
    ```
    ```powershell
      NAME            STATE           VERSION
    * Ubuntu-20.04    Stopped         2
    ```
- Tắt toàn bộ các instance WSL đang chạy :
    ```powershell
    wsl --shutdown
    ```
- Access file trong WSL instance :
    ```bash
    cuongnq@CUOLAP:~$ explorer.exe .
    ```
    <img src=https://i.imgur.com/sbyUCn4.png>

- Cài đặt **WinKex** :
    ```
    sudo apt install -y kali-win-kex
    ```
    - Sử dụng **WinKex** :
        ```
        kex
        ```
    > Tham khảo cách sử dụng **WinKex** : https://www.kali.org/docs/wsl/win-kex/

- Cài đặt **Metasploit** :
    ```
    sudo apt install metasploit-framework
    ```

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media