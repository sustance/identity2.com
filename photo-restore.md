 <a href="./index.html">Return to index</a>

 ```
 ┌─────────┐         ┌─────────┐         ┌─────────┐         ┌─────────┐
 └─────────┴─────────┘         └─────────┘         └─────────┴─────────┘
 ```
 ## Old photo correction
 
 Although this sites foundation is text, images are essential as well people expect clear high resolution images but those in your family or royaalty free collections are often faded and grainy.
 
 Not only are powerful image editors like photoshop readily available but also very good open source editors like Gimp, Kritta etc.
 
 Even more exciting recently are powerful A.I. algorithm that can take your grandma's tiny low resolution collection and scale them up to less accurate but much more usable higher resolution.
 
 Two places to try up-scaling for free 
 
 <a href="https://www.myheritage.com/photo-enhancer">  __www__ myHeritage Photo Enhancer</a>

 
 These algorithms are often most suitable to run on an online service, not your PC.
 
 ### Services to explore
 
 <a href="https://demos.algorithmia.com/colorize-photos/">   __www__ algorithmia</a>

 
 <a href="https://www.colorizephoto.com/converter">           __www__ converter</a>

 
 <a href="https://blog.floydhub.com/colorizing-and-restoring-old-images-with-deep-learning/">   __www__ Restoring</a>

 
 
 <a href="https://colab.research.google.com/github/mc-robinson/DeOldify/blob/master/DeOldify_colab.ipynb">    __www__ Colab Research Depixelizer</a>

 DeOldify
 
 ### Notes
 
 <a href="https://colab.research.google.com/github/tg-bomze/Face-Depixelizer/blob/master/Face_Depixelizer_Eng.ipynb#scrollTo=fU0aGtD4Nl4W">  __www__ Colab Research Depixelizer</a>

 
 1. Crop
 2. Patch
 3. Levels
 4. mask/blur, correct bright or dark areas
 ```language-ascii-art2
   ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓  
   ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛  
 ```
 About histograms:
 
 <a href="http://www.marginalsoftware.com/HowtoScan/using_histograms_as_a_tool3.htm</a>

 
 * Open the combo box list and select a hypothetical source image to be scanned (e.g. Low-key - 2).
 
 * Adjust exposure until the maximum number of tones is reached. Usually this reached when the specular highlights (the right-most edge of the source histogram) nears the right margin.
 
 * Applying a black-white point setting displays any possible discontinuities of the tonal scale due to this function.
 ```language-ascii-art2
   ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓    ┏━━━━┓  
   ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛    ┗━━━━┛  
 ```
 * No matter how new or old your slide is, your scanner will scan the gloss that comes off a slide.
 
 This leaves you with flat, faded colours. Yes, time also fades colour. But the biggest issue is the scanning process itself -- it's not perfect.
 
 To get rid of this without touching any of the real colours of your image, do the following...
 
 * GIMP > Colors > Auto > White Balance
 * Once you got rid of the glare, you can begin to brighten the colours. Go...
 * GIMP > Colors > Hue and Saturation
 * It's very simple, go...
 * Colors > Levels
 * I know I'm telling you to use "Color Levels" to fix exposure. But in my experience, this does a far better job than the actual Exposure Levels tool.
 * Anyway, here's exactly what to do...
 
 Tips On How To Use The Levels Tool
 
 * Here's a few techniques to remember when using the Levels tool...
 
 * Do you see the "Input Levels"?
 * Take the middle arrow (the gray one), and move it to the right
 * In my scan I moved it to about 0.57-- toward the white arrow
 * Say your slide is too dark, then move the gray arrow left,toward the black arrow
 * That's all it takes!
