# traversey-sass-sandbox
Udemy | Traversey Media | Sass Sandbox

# Monday 12-23-19
@ 10:50am
In this sandbox I will be going over how to use sass again to sharpen my sass skills and knowledge. I have used it in a previous project but I expext to learn how to use it better in this course. So far I have learned how to use NPM to install a sass compiler - as apposed to using the VS code extension live sass compiler (incase I am ever using a differant text editor). 

@10:59am
We went over basic nesting and stylesheet partials. I learned to use an underscore as the first charactor for partial stylesheet names to prevent sass from creating a new compiled css file. 

@11:08am
//Inheritance and Contrast
I learned that in sass you can use the % syntax to create styling that can be extended upon in other areas using the @extend syntax. For example the core styleing of a button can be done with %btn-shared, and then for the differant versions of the button you can use @extend %btn-shared to add on the specific styles for each one.

@11:27am
//Functions, Mixins, and more
I learned a coupple practical uses for functions and mixins in this section. I can create a handy function that will look at the color of an elements background and choose a font color that will contrast well with it

@function set-text-color($color) {
  @if(lightness($color) > 50) {
    @return #000;
  } @else {
    @return #fff;
  }
}

I also learned I can use a mixin to prevent myself from having to wirte multiple lines of code over and over agin in differant areas, for example webkit prefixes or such, by using a mixin. 

