# Mechanum Wheel Controller via toio™Visual Programming
Version 1.0.0
<img src="https://raw.githubusercontent.com/tetunori/MechanumWheelControlVisProg/assets/screen1.png" width="640px">
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/toio?src=hash&amp;ref_src=twsrc%5Etfw">#toio</a> のVisual Programmingでメカナムホイールを完全に理解した。<br>ついにtoioのキューブは全方位移動を手に入れましたww<br><br>先日の機構モジュールの応用編となりますが、詳細は長くなるので、以下のQiita記事にて。<a href="https://t.co/3YrRGB4cYp">https://t.co/3YrRGB4cYp</a> <a href="https://t.co/nSYxmhL0Ua">pic.twitter.com/nSYxmhL0Ua</a></p>&mdash; Tetsunori NAKAYAMA | 中山 哲法 (@tetunori_lego) <a href="https://twitter.com/tetunori_lego/status/1210191833608769536?ref_src=twsrc%5Etfw">December 26, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
YouTube -> https://youtu.be/c4uEohRcmfE

# Description
This is a tool that enables us to control an omni-directional mobile robot made by two toio™Core Cube and 4 mechanum wheels simultaneously.  
It is implemented under toio™Visual Programming environment.   
See [this article](https://qiita.com/tetunori_lego/items/37477c40b16f8eab384f) in detail.

# Usage
## Preparation
1. Visit [Developper version of toio™Visual Programming](https://toio.github.io/toio-visual-programming/dev/) and open "MechanumWheelControlVisProg.sb3" download from this repository.
2. Connect with 2 toio™Core Cubes. By using **q key**, we can light and check Head Cube. Also, we can exchange Head/Tail cubes by **1/2 keys**. 
3. Press Green flag.

## Operation
|Category  |Operation  | UI  |
|---|---|---|
|Omni-direction move|8 directions<BR>by ↑/↓/←/→|<img width="490" alt="omni.png" src="https://raw.githubusercontent.com/tetunori/MechanumWheelControlVisProg/assets/screen21.png">|
|Turn around<BR>center<BR>(red point)|r + ←/→|<img width="488" alt="rotation.png" src="https://raw.githubusercontent.com/tetunori/MechanumWheelControlVisProg/assets/screen22.png">|
|Turn around<BR>Head/tail<BR>(red point)|h/t + ←/→|<img width="489" alt="headtail.png" src="https://raw.githubusercontent.com/tetunori/MechanumWheelControlVisProg/assets/screen23.png">|
|Turn around<BR>l/r wheel<BR>(red point) |d/f + ←/→|<img width="488" alt="fd.png" src="https://raw.githubusercontent.com/tetunori/MechanumWheelControlVisProg/assets/screen24.png">|
|Check Head | q key | Light Head Cube in white. |
|Exchange Head/Tail Cubes | 1/2 key |1: Cube1 is Head. <BR>2: Cube2 is Head.|
|Adjust speed| Slider | <img width="165" alt="Speedslider.png" src="https://raw.githubusercontent.com/tetunori/MechanumWheelControlVisProg/assets/screen25.png"><BR>Default value is 40. |

## Working demo
- Omni-directional move
    - Twitter -> https://twitter.com/tetunori_lego/status/1210191833608769536
    - YouTube -> https://youtu.be/c4uEohRcmfE
- Rotation in detail
    - Twitter -> https://twitter.com/tetunori_lego/status/1210192042141184002
    - YouTube -> https://youtu.be/LZZqrjRLbag

# Licence
This software is released under the MIT License, see LICENSE.

# Author
Tetsunori NAKAYAMA.

# References
toio™  
https://toio.io/


