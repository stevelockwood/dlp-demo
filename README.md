DLP Demo

Steps to run
1. Clone this repo
2. Change into folder
3. run npm install
4. The app needs an ENV VAR of GOOGLE_CLOUD_PROJECT set to your Google Project ID. If running in cloud shell it is already set
5. To run the app:
	node redact.js image x-ray.png x-ray-redacted.png -t PERSON_NAME 
	node redact.js image x-ray.png x-ray-redacted.png -t DATE 
or try multiple info types:
	node redact.js image x-ray.png x-ray-redacted.png -t PERSON_NAME DATE GENDER
6. Try different info types: see https://cloud.google.com/dlp/docs/infotypes-reference
7. You can even try it on hand writing:
	node redact.js image contact-info.jpg contact-info-redacted.jpg -t EMAIL_ADDRESS	

