# Instructions:
  1. Install the "requests" and "Beautiful Soup" libraries:
      requests: http://docs.python-requests.org/en/master/user/install/#install
      beautiful soup: http://www.crummy.com/software/BeautifulSoup/#Download
  
  2. Run the "Run_All.py" script.
    This script does the following:
      Runs GetDataFromLabsHTML, which downloads the HTML for the page: http://ndar.nih.gov/data_from_labs.html
      Runs GetAllIndividualLabHTML, which downloads each individual entry's HTML to be scraped into a folder called "Data From Labs HTML"
      Runs GetAllIndividualLabJSON, which scrapes info from each HTML file and creates a JSON file with that information into a folder called "Data From Labs JSON"
      
  3. Use the files in "Data_From_Labs_JSON" for transformation scripts
