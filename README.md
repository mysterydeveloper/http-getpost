# HTTP Get and Post
In this exercise we will look at the HTTP GET and POST request methods.

## Exercises
1. Download node.exe from [here](https://nodejs.org/dist/latest/win-x64/), and curl.exe from [here](http://www.paehl.com/open_source/?CURL_7.44.0). You can use the "Without SSL" download option for curl.

1. Download the files in this repository and place them in the same directory as curl.exe and node.exe.

1. Open the command prompt and change to the directory where you have downloaded the files in this repository. Run 'curl google.ie' to check that curl works. Then run 'node http.js'. Open your browser and go to the URL 'http://localhost:8000'. Check the output in the Command Prompt window.

1. Open a second command prompt to examine Use the command 'curl -v 127.0.0.1:8000'. Examine the request and response in plain text.

1. Create a HTML form in forms.html, that uses the GET method, and has action 'http://localhost:8000'. Give the form the following fields: a textbox with the label 'Name', a pair of radio buttons with the labels 'Male' and 'Female', a checkbox with label 'I accept the terms and conditions, and a Submit button.

1. Open forms.html in your browser, fill in values on the form, and click Submit. Check the output in the Command Prompt window.

1. Change your form's method from GET to POST. Re-open forms.html in your browser, fill in values on the form, and click Submit. Check the output in the Command Prompt window.

## Advanced exercises
1. By hand, write the URL for submitting your sample form values to the server using the GET method. Test that it works using curl and node.

1. Use curl to mimic the submission of your sample form values to the server using the POST method. You will need to look up the --data option for curl.

1. Edit http.js to only output the parts of the request and response that are relevant to your investigations. 

## Note
- An excellent tutorial about HTTP: [HTTP Made Really Easy](https://www.jmarshall.com/easy/http/).
