
# Support resistance indicator for Mql5

In [trading technical analysis](https://www.investopedia.com/terms/t/technicalanalysis.asp), it's common to look for 
potential support and resistance trend lines. These tools are very useful when it come to understand trend movements and 
anticipate rebounds or breakthroughs.

This project aim to create a Mql5 indicator capable of displaying such support and resistance lines over a candle chart 
by using [hough line transform](https://en.wikipedia.org/wiki/Hough_transform).

## Work environment setup

1.1. Install MetaEditor 5

Download link:

    https://www.metatrader5.com/en/download

1.2. (Optional) Create a symbolic link (symlink) from the standard MQL5 directory to an external folder where your actual project files live.

    mklink [[/d] | [/h] | [/j]] <link> <target>

    e.g. mklink /d "C:\Users\<YourUser>\AppData\Roaming\MetaQuotes\Terminal\<Hash>\MQL5\Experts\MyEA" "D:\MyGitProjects\MyEA"

2.1. Install Visual Studio Code (vscode)

Download link:

    https://code.visualstudio.com/Download

2.2. Import profile "Mql5Proj.code-profile" into vscode

3. Clone git repository and start working on it !
