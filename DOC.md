# How to install

Open terminal window and type

`git clone https://github.com/riankashyap/speakBook`   

<p align="center">
  <img src="./images/8.jpg" alt=""/>
</p>

`cd speakBook`     
`bash ./INSTALL`   

<p align="center">
  <img src="./images/9.jpg" alt=""/>
</p>

To check if everything was installed properly type the follow and match with the below screenshots

`espeak -v && xsel -v`     

<p align="center">
  <img src="./images/10.jpg" alt=""/>
</p>

# How to use

Say you come across a long pdf on human psychology like i have here...

<p align="center">
  <img src="./images/1.jpg" alt=""/>
</p>

Highlight on the text you want to be read out loud. Press windows + R key.

<p align="center">
  <img src="./images/2.jpg" alt=""/>
</p>

To save the same as audiobook (File saves in home dir as *myaudio.wav*) press alt + R key.

# Know issues

On some computers shortcut keys must be enabled manually for the program to work

1.On your ubuntu machine click open your setting panel

<p align="center">
  <img src="./images/3.jpg" alt=""/>
</p>

2.Select and open keyboard and navigate to shortcuts tab.

<p align="center">
  <img src="./images/4.jpg" alt=""/>
</p>

3.Go to custom and create a shortcut with the following configuration

`name: speakBook`    
`shortcut : super + r`       
`command : bash -c "xsel | espeak"`     

<p align="center">
  <img src="./images/5.jpg" alt=""/>
</p>

<p align="center">
  <img src="./images/6.jpg" alt=""/>
</p>

4.To enable save audiobook feature, create a shortcut with the following configuration

`name: speakBook_save`    
`shortcut : alt + r`   
`command : bash -c "xsel | espeak --stdout > myaudio.wav"`   

<p align="center">
  <img src="./images/7.jpg" alt=""/>
</p>
