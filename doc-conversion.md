 <a href="./index.html">Return to index</a>

 
 
 ## Eclectic notes on Doc Conversion
 
 
 ### LaTeX to html and epub3 
 
 texstudio run htlatex to get html file
 
 Use script to strip out the weird extra empty images and get clean htm
 
 Import to htm to calibre
 
 * Change cover image
 * Make distinct name
 * meta: add author sort
 * look: text: justify, smarten punctuation,
 * page: ipad3
 
 \d is equivalent to [0-9]
 \w is equivalent to [a-zA-Z0-9_]
 \s is equivalent to any whitespace
 
 “?” matches 0 or 1 of the preceding element, 
 “*” matches 0 or more of the preceding element and 
 “+” matches 1 or more of the preceding element
 ```
 remove this eroneous output from html
 
 ```
 <img[\s]+src="ElecticTales[0-9]+x.png"[\s]+alt="PICT"[\s]?>
 <img[\s]+src="ElecticTales[0-9]+x.png"[\s]+alt="PICT"[\s]+class="calibre1"[\s]?/>
 <img[\s]+src="taleChineseEmbers[0-9]+x.png"[\s]+alt="PICT"[\s]+class="calibre1"[\s]?/>
 ```
 images, use eps or
 
 <a href="https://tug.org/tex4ht/">  __www__ Tug</a>

 ```
 command                output    comment
 --------------------------------------------
 htlatex  abc abc.html  HTML,     bitmap math
 xhlatex  abc abc.html XHTML,     bitmap math
 mzlatex  abc abc.xml  XHTML,     MathML math
 oolatex  abc abc.sxw  OpenOffice XML
   (uses MathML math)
 dbmlatex abc abc.xml  DocBook,   MathML math
 ```
 ``
 htlatex tale.tex "xhtml,html5,charset=utf-8" " -cunihtf -utf8"
 ```
 
 <a href="https://www.lode.de/blog/converting-latex-to-html/</a>

 
 If you are experiencing problems after switching a XeLaTeX project to pdfLaTeX in the project settings, an adaption of the LaTeX code is necessary. As we do not want to make the original XeLaTeX code unusable, we need to add conditional statements. For this, you need to include the ifxetex package:
 
 ``` 
 \usepackage{ifxetex}
 ```
 
 Then, simply surround XeLaTeX-specific code (or simply code that produces an error) with a “\ifxetex …\else …\fi” construction. Having this compatibility allows you to generate PDF files with XeLaTeX, and also produce HTML documents with pdfLaTeX when you switch compiler settings.
 
 For example, when generating an HTML file, you cannot include PDF files or vector graphics. Instead, you have to rely on JPG and PNG image files. Another application would be if you want to minimize the size of an existing image file for an e-book. A code might look like this:
 
 ```
 \begin{figure}[H]\centering 
 \ifxetex 
 \adjustbox{max width=.95\columnwidth, max height=.4\textheight}{ 
 \input{images/philosophy-hierarchy} 
 } 
 \else 
 \includegraphics{images/philosophy-hierarchy.png} 
 \fi 
 \label{c1_ontology-epistemology:fig} 
 \end{figure}
 ```
 
 
