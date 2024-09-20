Input Example File --> lista-urls-INPUT.txt
Ouput Example File --> output.csv   (copy the data in a new csv file with out the comments)

You need to modify the next variables to match your environment before running urlcat2.py


outputFilename = './yourdir/output.csv'  # This the logFile/csv name in relation to the script, i'm not making the output directory make sure it exists.
urlsToCategorize = './yourdir/lista-urls-INPUT.txt'  # This is the file we're processing, one url per line, no quotes or commas adjust path as necessary

username = 'yourusername@yourdomain.com'  # Admin username with API privileges
password = 'yourpassword'    # password for the above account
apikey = 'yourapikey'      # instance API key
seed = 'yourapikey'        # also the API Key
cloudName = "zscaler"     # this is the customer


   
