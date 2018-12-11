# Bootstrap and responsive H5P embeds

I am trying to embed h5p content into a website made with bootstrap.

## What works
I included the linkd script from h5p.org with the js to resize the h5p embedded content and that is working well. When I resize the window, the content resizes, too.

## My problem
If I don't give the <div> element a static height (in this example 400 px), the iframe is only about "one line" high, so nearly nothing is actually shown.
Setting the hight to 100% also doesn't work as the div doesn't extend down far enough and the h5p content is also cut off at about half the height.

I could theoretically give the div a static height but then it wouldn't be responsive and content would get cut off at large display sizes where the height becomes larger than the specifid height.

