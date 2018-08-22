### Google Two Factor Authentication Django Login
Live link=> [Two Factor Authentication](http://djauthenticator.pythonanywhere.com/)<=

## Usage

Simple django login app that extends django's user model and also adds an extra layer of security to your django web app. After signing up and confirming your email address, click on 'Two Factor Authentication Settings' button and follow the steps to enable two factor authentication. You will need to have The Google Authenticator app installed on your phone to scan the QRcode and enter the code generated

After successful completion, every time you log in, you will need to provide the 6-digit code generated on your Google Authenticator app to login. Pretty cool, huh!!

## Installation

Git clone this repo, create a virtual environment and run the command:

		pip install -r requirements.txt

After that makemigrations and migrate using the following comands:

		python manage.py makemigrations

and

		python manage.py migrate

respectively.

Finally launch your app using the following command:
		
		python manage.py runserver

## Licence

MIT



