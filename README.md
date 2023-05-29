##### html, css, javasctipt, jQuery, DarkTheme
# Rukbik's Cube Everywhere! --- WCA version (DarkTheme)
### seanachanpai

## Versions
這是高中自主學習完成的作品記錄，有：
  - python版
  - python+flask/html/css/javascript版
  - html/css/javascript版
#### on Local
  - python版：使用 matplotlib (+numpy)畫出可操作的魔術方塊，僅可單機使用；
#### on Heroku (太久沒用，帳號失效了啊!!!)
  - python/flask + matplotlib：matplotlib畫出的圖形，配合flask打包成webapp，發布到 heroku上 [[→ t7-02a]](https://t702a.herokuapp.com)。
  - python/flask + plotly：改用plotly畫出的圖形(interactive)，用flask打包成webapp，deploy to heroku上 [[→ t8-03]](https://t803.herokuapp.com)。
  - python/flask + html/css/javascript：改用html/css繪圖、javascript控制、flask製作webapp，heroku上發布 [[→ t9-05]](https://t905.herokuapp.com)。
  - (WCA version) python/flask + html/css/javascript：改用html/css繪圖、javascript控制、flask製作webapp，heroku上發布 [[→ t9-06]](https://t906.herokuapp.com) 
#### on Github
  - (WCA version) html+css+javascript版：webapp改成static html，放在 github pages上 [[currentProject t9-07]](https://eugenepai.github.io/t907/)
  - (WCA version / Dark theme) Dark theme version of t9-07,  with added game timer and congratulation animation when RC is solved [[Dark Theme t9-08]](https://eugenepai.github.io/t908/)
  - (WCA version / Dark theme) t9-08在mobile device上整個cube黑掉，只能在PC上正常顯示，原因在於原來使用:after的pseduo-element (:after)來製作color sticker的底黑，疑似與新的browser版本不相容(z-index or matrix3d)，導致底黑跑到彩色sticker上面。(解法：底黑與彩色sticker各用一個div，再用一個div包起來，利用div stack後來居上的default順序來避免z-index跨browser相容性問題---- solved!!)[[→ t9-09]](https://eugenepai.github.io/t909/)

## WCA  / World Cube Association / 世界方塊協會
- [WCA競賽規則](https://www.worldcubeassociation.org/regulations/translations/chinese-traditional/)
- [WCA Regulations](https://www.worldcubeassociation.org/regulations/)

## How to Play
- How to Play (WCA Rules) [[here]](https://eugenepai.github.io/t907/howToPlay.html)
- need help to solve Rubik's Cube? [[Hint]](https://eugenepai.github.io/t908/reference/RC_SolveStepsSummary.jpg)  / very useful reference [[here]](https://cubesolve.com/)

## Support or Contact

- Having trouble with playing cube? [contact support](https://rubiks.seanachan.tw/contact).
