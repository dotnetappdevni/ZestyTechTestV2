
ALL five tasks have been completed as requested.

David Buckley Notes

1. If there's no image uploaded on a new article, it shows a broken image (e.g. Article 3) - resolve that issue.

DB This is fixed as requested

2. On the news listing page, the date format isnt ideal. Change it to display like 1 January 2024.

DB This is fixed as requested

3. Also on the news listing page, there could be some performance problems when there's a lot of news articles. Implement one or more solutions for that.

DB: This is fixed as requested I added paginiation to the code so that it pass page=1 to set the default page.
And added pagination logic to the news listing pages.


4. The client wants a weather report on the homepage. Integrate a free weather API (e.g. https://open-meteo.com/) and the display the current temperature and weather conditions in Belfast.
DB: I added the weather information that was requested from the free api
With the current temp humidity and wind direction.

5. Create a Staff listing page and add some test data for the staff members. Create a simple detail view for each staff member.
DB Staff section created as requesed with sample data

DB The database is in the folder DatabaseBackup
Credentials are the same but please note the email address required is

techtest@simplyzesty.com and the password in appsettings.
Please dont forget to change your sql server instance back to local host
after restoring the new database
