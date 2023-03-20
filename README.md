# New York Times Crossword Scrape 

### Some notes: 
  - This script is still under construction. Both NYT and Google Chrome has updated their security measures making it more difficult to access their webpages using a script. Because of this, I haven't yet found a way to bypass CAPTCHA authentication - this script requires that you pause and manually complete the CAPTCHA verification on the webdriver's window before running the PDF scrape section. 
  - Because of updated NYT website security measures, we're no longer able to download the pdf webpage directly from the URL or even interact with the page. Therefore, the strategy is to take screenshots of the page which we will then crop and save. However, as of Mar 2023, this is not yet complete - as the script cannot interact with the PDF page - I have not yet figured out how to zoom out, or how to take a scrolling screenshot to capture the entire page. 

### Next Steps: 
  - Explore more options to bypass CAPTCHA authentication or explore more ways to open chrome with saved cookies so login information is preserved. 
  - Explore options to zoom out of PDF URL, save and crop picture before saving it to respective folder.
  - Create a requirements.txt file for scripts
  - Create .py files for script. Step 1 and Step 2 would need their own .py files. 
