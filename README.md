# join-discord-channel-sticky-button
This repository contains the main code and resources necessary to implement a "Join our Discord channel" sticky button. It was first implemented by Caravana do Absurdo's team in order to use it on their website:
https://caravanadoabsurdo.com.br/

![Element screenshot](https://github.com/caravana-do-absurdo/join-discord-channel-sticky-button/blob/main/res/img/discord-sticky-button-screenshot.png?raw=true)

## How to insert this element into your Wordpress website:
1 - Open the index.html file inside this repo
2 - Copy the HTML code inside the <body> tag
3 - Head to your Wordpress website dashboard, open Widgets and create a Text widget (it shouldn't matter much where you will put this widget, in my case I created it inside "Footer")
4 - Select "Text" instead of "Visual" in order to be allowed to insert HTML tags
5 - Paste the code there
6 - Copy the CSS code under the <style> tag
7 - Paste those classes where your site allows you to paste custom CSS classes (in my case, I installed the plugin [Simple Custom CSS](https://wordpress.org/plugins/simple-custom-css/) and pasted all my CSS code there)

> **Tip:** dont't forget to update the discord link under the href propriety, or else the button will always invite the user to join Caravana do Absurdo's discord channel, which is probably not what you want if you're following those steps
