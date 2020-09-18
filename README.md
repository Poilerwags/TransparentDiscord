# TransparentDiscord

![Example](https://i.imgur.com/LVCC1Kp.jpg)

The theme is far from perfect and I will likely continuously update it so please, 
if you have any questions or suggestions, feel free to contact me on Discord at Gies#2934.

**install using powercord.** https://powercord.dev
## Easy Install (recommended)
1. go to ``Settings`` > ``Themes`` > ``Quick CSS tab``
2. Paste this into the textarea on the first line and modify the url's to whatever you want: 
```css
@import url("https://raw.githack.com/Poilerwags/TransparentDiscord/master/Theme.m.css");

:root{
  
  /* Custom Background Url [url("image")]*/
  --ColAppBG: url('https://i.imgur.com/k6hST83.png');
  
  /* Custom Home Icon Url [url("image")]*/
  --HomeIconImg: url("https://pbs.twimg.com/media/EYX1joIU4AAz3oX.jpg");
}
```   
3. enjoy
  
## Manual install
1. make a plain css file. name it ``Theme.css``  
2. put in ``powercord/src/themes/[Insert Theme Name]``
3. put this into your css file and modify the url's to whatever you want:  
```css 
@import url("https://raw.githack.com/Poilerwags/TransparentDiscord/master/Theme.m.css");

:root{
  
  /* Custom Background Url [url("image")]*/
  --ColAppBG: url('https://i.imgur.com/k6hST83.png');
  
  /* Custom Home Icon Url [url("image")]*/
  --HomeIconImg: url("https://pbs.twimg.com/media/EYX1joIU4AAz3oX.jpg");
}
```  

```diff
if this doesent work copy the contents of the link into the css file. 
- You will lose auto updates by doing this! 
```
4. download the ``powercord_manifest.json`` from this repo and put it in the same folder.  
5. ``Ctrl + R`` on discord to refresh it.
6. If you want to turn the theme off or on, also switch themes, i recommend installing this plugin: https://github.com/LandenStephenss/Themer.  
7. enjoy
