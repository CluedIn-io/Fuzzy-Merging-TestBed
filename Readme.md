#Setup

To run this you will need POSTMan installed.
You will need to load this JSON file into POSTMAN. 

You will need to create an Environment File with 2 values.

url
authUrl

url needs to be the server Url
authUrl needs to be the authentication server Url

e.g. 

url = https://app.nightly.cluedin-test.online/api
authUrl = https://app.nightly.cluedin-test.online/auth

#Run the Tests

In Postman, click the "Runner" which will open the Test Runner. 

Highlight the Folder called Fuzzy Merging Test Bed and select the Environment you created from the Drop Down. 

Then Click "Start Run".

If all go Green it means that all your tests passed, if some have turned Red it means that you changes have caused some expectations to fail. 
