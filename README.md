# luas-archive-data-flat
Historic luas data fetched by the luas-archiving-service at https://luas-archiving-service.azurewebsites.net/

## Directory structure
-data

--historic

---YYYY-MM-DD-HH

    files: luas-TIMESTAMP.json
    
That is, a directory is created for every hour of the day and readings taken every minute are each saved to a file, named with a timestamp. The data in each file is flat.
