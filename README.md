DLP Demo

Steps to run
1. Clone this repo
2. Change into folder
3. run npm install
4. To run the app:
	node redact.js image x-ray.png x-ray-redacted.png -t PERSON_NAME 
	node redact.js image x-ray.png x-ray-redacted.png -t DATE 
or try multiple info types:
	node redact.js image x-ray.png x-ray-redacted.png -t PERSON_NAME DATE GENDER
5. Try different info types: see https://cloud.google.com/dlp/docs/infotypes-reference
6. You can even try it on hand writing:
	node redact.js image steveemail2.jpg steve-email-redacted.jpg -t EMAIL_ADDRESS	

