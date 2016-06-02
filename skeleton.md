What happens to the layout when you resize the screen to less than 550 px. How do you think that works?


The text changes from taking up half the screen size to filling the entire width.


There's a media query that takes effect at a screen width less than 550px.

Additionally, the text is wrapped in a div with the 'one-half column' class (linked to that media query).

They work together to achieve the effect.

For a screen width less than 550px, only the default styles would apply to the text. (I don't believe there are any that are taking effect besides the h4 and p defaults)

Once the screen is more than 550px, the text can follow the 'one-half column' css declaration which only takes effect at that point.