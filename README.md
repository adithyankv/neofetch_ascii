#Custom ASCII art for neofetch

##How to use
Clone this repo and get the .txt file containing the ASCII art
`
git clone https://github.com/Adithyan-KV/neofetch_ascii.git
`
Now you can make neofetch use this ASCII file by using
`
neofetch --source path/to/ascii/file
`
If you donot want to go through the hassle of typing in that long command every time, you can make neofetch use our ASCII image by default. I believe that involves
tweaking the config file for neofetch itself. But i personally prefer having all my tweaks in my .bashrc where I can change them as necessary. So what I did was 
to create an alias for >neofetch as >neofetch --source path/to/ascii/file
