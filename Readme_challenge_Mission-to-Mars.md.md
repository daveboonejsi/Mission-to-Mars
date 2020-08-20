##challenge Readme file

Mission to Mars Challenge (Module 10)

Scrape the NASA websites to create an app that updates on command

Using MongoDB, python, flask, splinter, and BeautifulSoup.

Run Mongod, then Mongo from within the shell

Run the file app_challenge.py from the Anaconda shell.

Enter the local web address into a browser, then after receiving the message "Scraping Successful", review the local URL to see the index_challenge.html stored in the Templates subdirectory.

The page displays the image of the day from NASA, a table of facts from Mars, and the article of the day with description.

Then there are four image files of the four hemisperes of Mars.

I wrote a python program (app_challenge.py) which uses flask to create a web app, that calls another program called scraping_challenge.py that scrapes the NASA websites for the relevant data using html tags to identify elements of a website and import them over the web.  The program makes a python dictory of text, titles, images, and tables, calls a html template to display the elements.  The app is dynamic such that if you click on a preformatted button on the webpage it will refresh the data.

Had a little trouble whereby the pictures wouldn't load.


