# Cherry-Blossom


![Prompt](https://github.com/jemhv/Cherry-Blossom/blob/main/images/cherry-blossom-terminal.png?raw=true)

> Neofetch Theme (optional)
![Prompt](https://github.com/jemhv/Cherry-Blossom/blob/main/images/cherry-blossom-default.png?raw=true)

> Custom heart ascii (optional)

![Prompt](https://github.com/jemhv/Cherry-Blossom/blob/main/images/cherry-blossom.png?raw=true)

(The image is just a representation of the design, it may vary depending on the terminal used and the font. This example uses Arch Linux with konsole as the terminal)

# Starship Prompt Theme.

> Requirements for installing --- 
1. OS: Linux, MacOs
2. Starship Prompt (https://starship.rs/) Please follow the installation for your OS.
3. git
4. MesloLG Nerd Font https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/Meslo.zip 
5. Neofetch (optional if you want the neofetch theme also)

> Installation guide for the prompt
1. Download the files in your home directory.
2. Copy the starship.config file in your ~/.config directory
(Do the following step only if you need the neofetch theme).
3. Copy ascii.txt && config.conf in your neofetch directory location.


> or simply copy paste the following code in your terminal (This example uses linux, you may have different directory based on your OS)
```
git clone https://github.com/jemhv/Cherry-Blossom.git
cd Cherry-Blossom
cp -r starship.toml ~/.config/

```
# Neofetch theme
> To get the neofetch theme type the following code (To get the custom Ascii image please uncomment image-source in the config.conf file)
```
cp -r ascii.txt config.conf ~/.config/neofetch/

```


#### Troubleshoot
>> If you're getting ``` No such file or directory ``` please run ``` neofetch ``` in your terminal.
>> If you've downloaded starship for the first time you should do ``` source ~/.bashrc ``` in your terminal.

