# complex_number_multiplication
As we know,complex number have one real part and one imaginary part.When we multiply two complex numbers,it takes four multipliers to compute the multiplication(Two multipliers for real part and other two for imaginary part).Let's take two complex numbers (Xre+Xim),(Are+Aim) then their product is (Yre+Yim).
   Where,
                           real part:            Yre = XreAre-XimAim
                           Imaginary part:       Yim = XreAim+XimAre
So, it takes four multipliers to compute XreAre,XimAim,XreAim,XimAre.If we use DA,OBC techniques here to compute these multiplications,Adders and Shift Registers are enough for the calculation.And it is only necessary to store two words in the look up table(LUT) i.e (Are-Aim) and (Are+Aim). 
So the area is less and speed is high.
