# Digital Publishing

**About**

This project was conducted as part of the Digital Publishing course at the University of Lausanne under the direction of Mr. Isaac Pante (SLI, Faculty of Arts, UNIL). In order to carry out this project, I developed a classification tool for the films of movie director Quentin Tarantino.

![alt text](https://raw.githubusercontent.com/fpham1/Publication-num-rique/master/Screenshot.png)
Figure 1 - Screenshot of the page

**Functions**

Broadly speaking, this tool allows the user to (1) filter and (2) sort Tarantino's films. But he can also select criteria that will refine the sorting.

Indeed, with the filter function, the user can, as the name suggests, filter the films according to genre. When a particular genre is selected, the films of other genres disappear, leaving only the films of the selected genre.

With the sorting function, for the "Name" and "Genre" criteria, the user sorts the movies in the alphabetical order of the selected criterion. For the criteria "Year" and "Duration", the films will, of course, be sorted in numerical order.

In addition, the functions can be combined. The sorting will only be done on the remaining films after the user has filtered the selection.
![alt text](https://raw.githubusercontent.com/fpham1/Publication-num-rique/master/Screenshot_01.png)
Figure 2 - Result after filtering the genre "Crime" and sorting alphabetically

**Library**

This project is composed of only a few files: an "index.html" page that contains the page content, a "script.js" page that allows filtering and sorting of the inserted data, a "style.css" page that allows visual rendering, and, finally, image files.

This project was possible thanks to the "Isotope" library, imported in the "script.js" file.

As far as the images are concerned, I basically wanted to take the original covers available on IMDB. However, due to copyright infringement problems, I had to create fake covers.

**Possible improvements**

One of the first ideas that comes to my mind would be to be able to do "web scraping" in order to be able to select a producer of our choice directly from the platform.