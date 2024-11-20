# kali_build
A custom *automated* Kali install 🚩 All your CTF tools in one place.  
- Designed for a totally fresh Kali install -- for usage at Defcon and the like. Automated with ansible. 
- The scripts are purposely designed as simply as possible so they are easy to customize/edit.

### Directions  
1. Install fresh Kali VM [(HERE)](https://www.kali.org/get-kali/#kali-platforms) remember to check the box for the *large toolset* during install.
2. `sudo apt update && sudo apt upgrade`
3. Install ansible: `sudo apt install ansible`
4. Clone this repo.
5. Change directory and run Playbook.
```
sudo ansible-playbook main_tools.yml
```

5. (Optional) Run the `shell.config` for a nice Tmux appearance and additional modules. Also includes terminator and a pretty shell config. It uses the Catppuccin theme 😃.   
```
ansible-playbook shell_config.yml
```

## 🔨 Tools list
- Pentesters should look at source code... (CTRL+F)

## 🆕 Requests / Additions  
If you would like a new tool added. Submit it as a `request` under the **Issues** tab. 

