# week02-assignment

## What is Digital compositing

Digital compositing is the process of digitally assembling multiple images to make a final image, typically for print, motion pictures or screen display. It is the digital analogue of optical film compositing.

![캡처_2020_09_21_08_36_04_339](https://user-images.githubusercontent.com/71207918/93724984-90e1fa00-fbe6-11ea-9aef-eb728575ad2a.png)_  
![캡처_2020_09_21_08_35_59_489](https://user-images.githubusercontent.com/71207918/93724990-94758100-fbe6-11ea-877c-98a966daa98b.png)

## Application of digital compositing

 ### Bluescreen Compositing 
 
 The talent is filmed in front of a solid blue background to make it easier for the computer to isolate then composite them into the actual background like the example
 
 ![캡처_2020_09_21_08_50_00_114](https://user-images.githubusercontent.com/71207918/93725102-73f9f680-fbe7-11ea-8ce2-6029da351936.png)
 
 
 ### Motion tracking
 
 Motion tracking match move the CGI artist is tracking hundreds, sometime thousands, of points in a scene and using that data to build 3D models and a matching 3D camera move.    
 Motion tracking usually only tracks a few points and its data is used to track one two-dimensional image onto another two-dimensional image. 
 
 ![캡처_2020_09_21_08_51_43_287](https://user-images.githubusercontent.com/71207918/93725165-d81cba80-fbe7-11ea-9d84-f3ab36b8a659.png)

### Warping and Morphing 

Warping is one of those magical things that only a computer can do. Imagine it as
attaching an image to a sheet of rubber, then pulling and stretching only those parts
of the rubber sheet that you want to deform. This especially allows you to push and
pull on the interior parts of the image to deform it any way you want. When is this
used? Any time you want to fi t one image over another but you can’t make it fi t just
by pulling on its corners. These warps can also be animated over time to maintain
their warped shape over a moving surface. 

![캡처_2020_09_21_08_54_30_615](https://user-images.githubusercontent.com/71207918/93725201-1619de80-fbe8-11ea-8df5-0f454d5554a9.png)




## What is alpha and color\

### Alpha

The alpha channel is a color component that represents the degree of transparency (or opacity) of a color (i.e., the red, green and blue channels). It is used to determine how a pixel is rendered when blended with another.

![캡처_2020_09_21_08_59_03_236](https://user-images.githubusercontent.com/71207918/93725267-b7089980-fbe8-11ea-9835-64bef772b8f2.png)

### RGB Color

By mixing three "primary" colors, any color could be generated. Swirling all colors together resulted in a muddy brown. The more paint you added, the darker it got. Digital colors are also constructed by mixing three primary colors, but it works differently from paint. First, the primaries are diff erent: red, green, and blue (i.e., "RGB" color). And with color on the screen, you are mixing light, not paint, so the mixing rules are different as well.

![캡처_2020_09_21_09_00_25_208](https://user-images.githubusercontent.com/71207918/93725298-11a1f580-fbe9-11ea-9910-bb84e6f45ffb.png)

This assumes that the colors are all as bright as possible, but of course, you have a range of color available, so some red plus some green plus some blue equals gray, and a bit of red plus a bit of blue equals dark purple. While this may take some getting used to, the more you program and experiment with RGB color, the more it will become instinctive, much like swirling colors with your fi ngers. And of course you can't say "Mix some red with a bit of blue," you have to provide an exact amount. As with grayscale, the individual color elements are expressed as ranges from 0 (none of that color) to 255 (as much as possible), and they are listed in the order R, G, and B. You will get the hang of RGB color mixing through experimentation, but next we will cover some code using some common colors.




https://booksite.elsevier.com/samplechapters/9780240817811/9780240817811.pdf
https://processing.org/tutorials/color/
https://www.quora.com/What-exactly-is-an-alpha-channel-in-an-image
https://en.wikipedia.org/wiki/Alpha_compositing
