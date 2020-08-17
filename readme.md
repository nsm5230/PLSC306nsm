Steps:
------
0. [Have R and RStudio installed.](https://kevinreuning.com/resources/install_r/)
1. Open RStudio. On the leftside there will be a box called "R Console" you will type everything I tell you to in there.
2. In the console type the below line and hit enter. This will install a package called `remotes`
~~~~ R
install.packages("remotes")
~~~~
3. Some text should popup that ends with 'The downloaded binary packages are in'  followed by a long file path. If there is any red text you might have an error, contact me.
4. Now type the below line and hit enter to install `POL306` which has all the tutorials in it
~~~~ R
remotes::install_github("PLSC309nsm/PLSC309")
~~~~
5. You will see more text again, although this time there will be a lot more. Generally, as long as there is no red text it should be fine. It might ask your permission to install things from source, if so tell it yes. 
6. Run one last line to check to make sure everything worked. You should see a message welcoming you to the tutorial, if you see "Error in library(POL306) : there is no package called ‘kevin’" then contact me.
~~~~ R
library(PLSC309)
~~~~
