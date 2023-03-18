
## BOX MODEL
### Everything displayed by CSS is a box.Understanding how the CSS Box Model works is therefore a core foundation of CSS.

Extrinsic sizing vs intrinsic sizing

Extrinsic sizing is when we set the dimesion of box extrernally or set its dimersions on the parent

Instrinsinc sizing is the size of the content or children present in the box,or we can say the actual size of the children

When content is too big for the box it is in, we call this overflow. You can manage how an element handles overflow content, using the overflow property.

 By default, all elements have the following user agent style: box-sizing: content-box;.

 Having content-box as the value of box-sizing means that when you set dimensions, such as a width and height, they will be applied to the content box. If you then set padding and border, these values will be added to the content box's size.


 Box Sizing 

 Content Box and Border Box

 Content Box: The box sizing will add up marging + padding +border +contetn widt (Extrinsix sizing)


 Box Sizing : content+padding+border== extrinsic sizing
 padding and border will try to push the content width to adjust