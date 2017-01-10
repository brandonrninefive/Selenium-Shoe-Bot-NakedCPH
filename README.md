# Selenium Shoe Bot
This is a simple Python bot which uses Selenium to navigate the website [http://www.nakedcph.com/](http://www.nakedcph.com/)  and quickly checkout shoe orders. Although the script was written with the specific intention of making shoe orders, there is nothing stopping users from checking out other items on the site through the script. Users can configure how many orders they want to make, including the credit card info to use and various items to checkout within each order by editing the included checkout.conf JSON file. The script is configured to use Selenium's Chromedriver, which is included as a dependency, however, the Pip repo for this dependency currently only works for Linux. On other systems, Chromedriver may have to be installed manually.
