# kali_build
A custom *automated* Kali install 🚩 All your CTF tools in one place.  
Designed for a totally fresh Kali install -- for usage at Defcon and the like.   
Automated with ansible. The scripts are fairly simple and literally just one file, so it should be fairly easy to customize/edit.

### Directions  
1. Install fresh Kali VM [(HERE)](https://www.kali.org/get-kali/#kali-platforms).
2. Install ansible: `sudo apt install ansible`
3. Clone this repo.
4. Change directory and run Playbook.
```
sudo ansible-playbook main_tools.yml
```

5. (Optional) Run the `shell.config` for a nice Tmux appearance and additional modules. Also includes terminator and a pretty shell config. It's mostly Catppuccin themed.   
```
ansible-playbook shell_config.yml
```

## 🔨 Tools list
- Pentesters should look at source code...

## 📑 Wordlists
- Statistically likely usernames

## 🆕 Requests / Additions  
If you would like a new tool added. Submit it as a `request` under the **Issues** tab. 

