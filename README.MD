
## Purpose

Generated social media pictures for selected books

Creating promos in bulk require also that there would be an illustration. Here the illustration
is the name of the book imprinted on top of a chosen free-to-use nature photograph:


https://d672eyudr6aq1.cloudfront.net/csv/sprout_example_import.csv


## Generating the base images 


magick convert kukka.jpg -crop 400x300 +repage +adjoin kukka_%02d.png


... add texts and the tiny watermark ... 

