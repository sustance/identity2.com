 # Identity2
 
 ```language-ascii-art2
 ┬┌┬┐┌─┐┬ ┬┌┬┐┬┌┬┐┬ ┬┌─┐  ┬  ┌─┐┬ ┬┌─┐ ┌─┐┌─┐┌─╮┌┬┐ ┌┬┐┌─┐┬ ┬┌┬┐
 │ ││├┤ │╲│ │ │ │ └┬┘┌─┘  │  │ ││╲││┌┐│├┤ │ │├( │││  │ ├┤  ╳  │
 ┴ ┴┘└─┘┴ ┴ ┴ ┴ ┴  ┴ └──  └─┘└─┘┴ ┴└─┘ ┴  └─┘┴ ┴┴ ┴  ┴ └─┘┴ ┴ ┴
 ```
 
 ## Writing
 
 ### Tools
 
 You can write with anything you like as long as it understands unicode.
 
 It is best to use an editor that allows you to write plain text with as little clutter and distraction as possible, there are hundreds to choose from. I am  currently using Geany as I am using gemtext markup and it shows formatted view in a sidebar. 
 <a href="https://www.geany.org/download/releases/">     __www__ Geany. Win Linux Mac</a>

 To open the generated files from this site other than .gmi gemtext files and re-edit them you can use:
 <a href="https://overleaf.com">        __www__ [tex,pdf] Online Overleaf LaTeX editor</a>

 <a href="https://www.texstudio.org/">  __www__ [tex,pdf] Install Win/Mac/Linux Texstudio LaTeX editor</a>

 <a href="https://sigil-ebook.com/sigil/download/">__www__ [epub,mobi,etc.] Install Win/Mac/Linux Sigil eBook editor</a>

 <a href="https://www.gimp.org/downloads/">__www__ [jpg,png,etc.] Install Win/Mac/Linux Image editor</a>

 
 A particular issue with writing in unicode in gemtext with simple tools is that is easy to enter unicode character that you can not find to remove but creates hassles down stream, find them like this:
 ```
    find . -type f -exec grep -H '┌┬┐┌─┐┬ ┬' {} \;
 ```
 If you have no 'nix (That's MacOS, Windows subsystem for 'nix, Linux and & BSD) terminal for this or other commands there are many terminal choices online, including:
 <a href="https://linuxcontainers.org/lxd/try-it/">  __www__ Free/no registration terminal if u have no 'nix </a>

 <a href="https://copy.sh/v86/">                     __www__ another Free/no registration terminal</a>

 
 The tools above are what I use, partly because they are all free and supported by a community. Frankly it does not matter much what you use when you are aiming for smol and simple systems.
 
 A good text graphics grapics app would be handy but I have never found one. The good ones use only ascii characters which is too limiting and ugly and the unicode ones are immature.
 ```language-ascii-art2
   ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓  
   ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛  
 ```
 
 
 
 
 
