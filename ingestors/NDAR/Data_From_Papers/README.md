# Instructions:
  1. Install the "requests", "Beautiful Soup", and "Selenium" libraries:
      requests: http://docs.python-requests.org/en/master/user/install/#install
      beautiful soup: http://www.crummy.com/software/BeautifulSoup/#Download
      selenium: https://pypi.python.org/pypi/selenium
  
  2. Run the "Run_All.py" script.
    This script does the following:
      Runs GetDataFromPapersHTML, which downloads the HTML for the page: http://ndar.nih.gov/data_from_labs.html
      Runs GetAllIndividualPaperHTML, which downloads each individual entry's HTML to be scraped into a folder called "Data From Labs HTML"
      Runs GetAllIndividualPaperJSON, which scrapes info from each HTML file and creates a JSON file with that information into a folder called "Data From Labs JSON"
      
  3. Use the files in "Data_From_Papers_JSON" for transformation scripts