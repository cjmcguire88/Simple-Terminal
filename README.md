# **Suckless Simple-Terminal**

## **Patches applied:**
  - *anysize*
  - *scrollback*
  - *scrollback-mouse*
  - *scrollback-mouse-altscreen*
  - *desktopentry*
  - *xclearwin*
  - *w3m*
  - *sync* (part 2)
___
## **Other changes**
- *Colors: There are 4 different color schemes. OneDark, material, flat and bright . Default is flat. Switch out the  
           configs to change schemes.*  
- *MesloLGS NF font* (Download below or change font in config.h)  
|[MesloLGS NF Regular.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf)|
|[MesloLGS NF Bold.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold.ttf)|
|[MesloLGS NF Italic.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Italic.ttf)|
|[MesloLGS NF Bold Italic.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold%20Italic.ttf)|
___
## **Install**
- *edit config.mk to match your setup*
- `make clean install`
___

![st](st.png)

Note: ST looks for cflags in your environment variables. If you have them set you will get an optimized build!!!
