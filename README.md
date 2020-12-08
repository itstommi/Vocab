[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

# About
Displays a new vocabulary word everyday in your terminal using Python with Selenium. If you have questions, feel free to pm me on [Reddit](https://reddit.com/user/ImportantDesk) (Ignore my comments before 6/2/2020 as they are now outdated. Everything you need to know is included below).

## Pictures
![Demo Gif](demo.gif)
![Screenshot](https://i.imgur.com/IfwgKjL.png)

## Requirements
Run the following commands:
<br><br>
```pip install requests``` <br>
```pip install bs4```

## Files
<b>.hyper.js</b> - My Hyper config file <br>
<b>.bash_profile</b> - My bash configuration <br>
<b>vocab.py</b> - The python file to scrape dictionary.com for the word of the day

## Updates
<b>6/2/2020</b> - Please read the important notes! If you cloned/downloaded before 6/2/2020, I have updated this repository. Instead of using hyper-init to run commands, I just put them in .bash_profile

## Important Notes
- The terminal I use is called [Hyper](https://hyper.is).
- If you just want the Python script that displays the word, just look at <b>vocab.py</b>. If you're interested in the Hyper configuration or Bash stuff, keep reading.
- I made this on Mac running Bash terminal
- The new macOS Catalina uses Zsh instead of Bash, but I switched back to Bash using Hyper (in the config file, it is on line 108). Please change this accordingly as there are instructions in the file.
- On macOS Catalina, switching back to Bash gives an ugly message everytime a new terminal window opens, so I configured .bash_profile to remove the message. If you never got the message in the first place, you can remove lines 1-3 on the .bash_profile
- The code in .bash_profile is commented. Please look thru and make changes if needed (change the path on the 'vocab' command in the .bash_profile according to where you clone/download)
- On lines 155-157 of the .hyper.js file, those are the plugins I prefer.
- On lines 158-161 of the .hyper.js file, I left cool plugins for you guys to check out
