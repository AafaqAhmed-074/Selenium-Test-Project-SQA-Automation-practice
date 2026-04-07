This zip folder contains a simple website on which I tried to perform automation testing using selenium test scripts.
**First**, you need to have chrome driver installed on your computer that matches exactly with your chrome browser. Make sure to add the path of your chromedriver folder, in which chromerdriver.exe is downloaded or present, to environment variables.
**Second**, Install selenium in your system either directly or through requirements.txt.

**Running the Selenium Script**
    **Option A**:**Using Local Server** (**Recommended**)
     
      Open terminal in your website folder:
      
      cd "PATH_TO_YOUR_TESTWEBSITE"
      
      python -m http.server 3000      
     
**Run the Selenium script**:
      python test_script.py
      
**Option B**: Using Local File Path (No Server)

Use the full path to your index.html (or login.html) file:

driver.get(r"file:///PATH_TO_YOUR_WEBSITE_FOLDER"), **Example**: driver.get(r"file:///D:/SeleniumTestProject/SeleniumTest Website/login.html")

**Run the Selenium script**:

python test_script.py
