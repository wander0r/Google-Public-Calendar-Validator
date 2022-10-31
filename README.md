# Google-Public-Calendar-Validator

Overview: 

As part of penetration testing, reconaisasance is very pivotal part of your testing.  Information Gathering is key to a successful penetration test.  

This simple bash script will take a list of google calendars based off email address (url-list.txt) and will output another text file (results_output.txt) of whether any corporate google calendar is made public and may contain sensitive information.\

Usage:

1. Download the shell script and corresponding files.
2. Edit your url-list.txt
3. Chmod +x ./google-public-calendar-validator.sh
4. Run the shell script - ./google-public-calendar-validator.sh
5. Review the results for any 200 HTTP Response email accounts for further validation of potential sensitive information exposure.
