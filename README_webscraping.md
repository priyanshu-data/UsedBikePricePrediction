Skipping the introduction part :

Step One : WEB SCRAPING
                         Description
                         Here I have created empty lists with the name of the required data and then appended the data to the lists respectively.
                         The page contains "Load More" button therefore I have used session to scrape through all the pages.
                         Range in the for loop defines the number pages we want to scrape i.e. page 1 to page 1725. Calculation behind 1725 is 34530/20. Where 34530 is the total                            number of search results and 20 is the number of results on each link.

The terminology used are : After the loop
                           HOW TO FIND HEADER(useragent,referer,authority,method)
                           Open up the site where you want to find used bikes,in my case it is droom> inspect the page > navigate to network icon> then refresh the page and don't                            close the inspect page ,when u refresh the page and check the network menu you will see list of names and out of that search for used?page=.....
                           usually it is on the top of the list > click it >Navigate to Headers
                           
   SOURCE : HOW TO FIND SOURCE?
   for source you can copy the link in the main search it should be like this :                                                                                                        https://droom.in/bikes/used?page=1&tab=grid&display_category=All+Motorcycles&condition=used
                           
   location : price : distance : owner : How to find that?
   If you are familiar with the html and hovering then you should know how to see it, if not navigate to the button showing "select an element for                                    inspection" and manually drag and see the location : price : distance : owner : in the main page.
                           
                           
                         
                         
