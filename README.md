笔记

[安装chrome](https://blog.csdn.net/qq_41159150/article/details/118527773#:~:text=1.ubuntu%20server%20%E7%89%88%E6%9C%AC%E5%91%BD%E4%BB%A4%E8%A1%8C%E5%AE%89%E8%A3%85chrome%20sudo%20apt-get%20install%20libxss1%20libappindicator1,apt-get%20install%20-f%20google-chrome%20--version%20%23%20%E6%9F%A5%E7%9C%8B%E7%89%88%E6%9C%AC%201)

[chrome drive](https://googlechromelabs.github.io/chrome-for-testing/)

[Selenium chrome drive executable path](https://stackoverflow.com/questions/76802588/python-selenium-unexpected-keyword-argument-executable-path#:~:text=TypeError%3A%20WebDriver.__init__%20%28%29%20got%20an%20unexpected%20keyword%20argument,s%20%3D%20Service%20%28r%27D%3Apathtogeckodriver.exe%27%29%20browser%20%3D%20Firefox%20%28service%3Ds%29)


---

No longer maintained. I no longer have GPU to run language models, someone else should fork and continue development.
# web_search
 Web search extension for [text-generation-webui](https://github.com/oobabooga/text-generation-webui)

 Thanks to [TheCyberViking](https://github.com/TheCyberViking) for the initial simple web search code. You can see it [here](https://github.com/oobabooga/text-generation-webui/discussions/932)

 | ![Screenshot from 2023-09-02 16-50-05](https://github.com/simbake/web_search/assets/6049383/513d9b46-5354-4970-a09c-4fbfd4bc61e4) | ![Screenshot from 2023-09-02 16-48-47](https://github.com/simbake/web_search/assets/6049383/f26caad6-d89e-43c8-b7e6-a6b35806c491) |
 |:---:|:---:|
| ![Screenshot from 2023-09-02 16-45-22](https://github.com/simbake/web_search/assets/6049383/36c52e5a-4146-444e-b254-ed7c48a0e946) |![Screenshot from 2023-09-02 16-43-01](https://github.com/simbake/web_search/assets/6049383/d09fa1f0-a1b1-4f45-adb3-9c9b1c517246) |

 
 This extension enables' a language model to receive google search data according to the users' input.[Currently supports google search only]


 How to use
 
 One needs to type search then what you want to search for, example:
 
 Type ```search the weather in Nairobi, Kenya today.```

 Requirements

 - Google chrome browser

 How to install

*** Make sure to run these commands in the cmd script that came with text-generation-webui. eg ```cmd_linux.sh```(Linux) ***

1. First clone the repo to ```text-generation-webui/extensions``` folder

2. Then ```cd web_search``` and run ```pip install -r requirements.txt```

3. Add ```web_search``` to launch commands of text-generation-webui
   like so ```--extension web_search```

4. Run text-gen-webui. There will be a checkbox with label ```Use Google Search``` in chat tab, this enables or disables the extension.

5. Done

!!!Have fun!!!
