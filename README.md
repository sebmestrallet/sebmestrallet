<!-- you know it's gonna be fancy when there's more HTML than Markdown -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/save_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/save_black.png">
  <img alt="Save" src="icons/save_black.png">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/add_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/add_black.png">
  <img alt="Add" src="icons/add_black.png">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/cut_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/cut_black.png">
  <img alt="Cut" src="icons/cut_black.png">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/copy_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/copy_black.png">
  <img alt="Copy" src="icons/copy_black.png">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/paste_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/paste_black.png">
  <img alt="Paste" src="icons/paste_black.png">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/run_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/run_black.png">
  <img alt="Run" src="icons/run_black.png">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/stop_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/stop_black.png">
  <img alt="Stop" src="icons/stop_black.png">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/restart_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/restart_black.png">
  <img alt="Restart" src="icons/restart_black.png">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="icons/fast_forward_white.png">
  <source media="(prefers-color-scheme: light)" srcset="icons/fast_forward_black.png">
  <img alt="Fast-forward" src="icons/fast_forward_black.png">
</picture>
<br/>

## 💼 Work

<!-- use a HTML table to be able to put code blocks inside -->
<table>
  <tr>
    <td>[1]:</td>
    <td><pre lang="python">
import SebastienMestrallet as about_me                                                               
print(about_me.current_position)
</pre></td>
  </tr>
</table>

absolute,left=520px,top=100px

<table>
  <tr>
    <td>[2]:</td>
    <td><pre lang="python">
print(about_me.experiences.current_position)                                                         
</pre></td>
  </tr>
</table>

PhD student in geometry processing at CEA, France

## 🔧 Tools I use

<table>
  <tr>
    <td>[3]:</td>
    <td><pre lang="python">
import pandas as pd                                                                                  
from random import randrange
df = pd.read_csv('tools_I_use.csv')
for idx in df.index:
    if randrange(10) == 0:
        df['URL'][idx] = 'https://youtu.be/dQw4w9WgXcQ'
display_with_links(df)
</pre></td>
  </tr>
</table>

&nbsp; | name | category | notes
-------|------|-------------|-------
0 | [VSCode](https://code.visualstudio.com) | code editor | Quite satisfied but maybe one day I'll learn how to use (and quit) Neovim
1 | [Zsh](https://www.zsh.org/) | Unix shell | With Oh my Zsh and Spaceship prompt of course!
2 | [C++](https://isocpp.org/) | programming language | I hate C++. This is a SOS. Please help me.
3 | [Python](https://www.python.org/) | programming language| You shouldn't be surprised it's on the list
4 | [Rust](https://www.rust-lang.org) | programming language | What I'd be continuing to learn if I had more time
5 | [Typst](https://github.com/typst/typst) | typesetting | LaTeX? You mean the slow and messy thing?
6 | [reveal.js](https://revealjs.com/) | presentation framework | Works everywhere & easily animated/extended
7 | [LocalSend](https://localsend.org/#/) | file sharing | You dreamed it you have it : your AirDrop alternative
8 | [Excalidraw](https://excalidraw.com/) | drawing | Simple - beautiful - feature-complete - always up-to-date
9 | [Obsidian](https://obsidian.md/) | knowledge management | Link your notes!!!
10 | [AnyType](https://anytype.io/) | knowledge management | How computer files should have been designed from the beginning

## 👀 Interests

<table>
  <tr>
    <td>[4]:</td>
    <td><pre lang="python">
[interest for interest in about_me.interests if 'coffee' not in interest]                            
</pre></td>
  </tr>
</table>

['graphic design',<br/>
&nbsp;'data visualization',<br/>
&nbsp;'web development with PWA, Wasm, WebGPU',<br/>
&nbsp;'educational mock-ups of algorithms',<br/>
&nbsp;'interactive scientific visualizations',<br/>
&nbsp;'knowledge management',<br/>
&nbsp;'productivity tools']
