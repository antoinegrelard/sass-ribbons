# Sass Ribbons

This repo will show you the different usages you can have with the scss ribbon I created.

[http://ikoshowa.github.io](http://ikoshowa.github.io)


## Usage

You can add the ribbon to any class you want.

The only limit is that you have to be semantic : you'll have a div on which you apply the class you want, and then you'll have span inside, and another one inside the first span.

Then, In your scss file, you can simply add a ribbon by using the @include ribbon() property to your class.

Leaving the brackets empty will display a default ribbon, but you can give 4 arguments to your ribbon : Background-color, text color, size and his direction (top or bottom, default to bottom).