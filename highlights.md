

- Recently, I built a web app and had a lot of challenges while building the app.
One of the challenging part was verifying phone numbers of users. As always, there were many options but I needed an option that is easy and does the job the way I wanted.
- Basically, I wanted to be able to verify phone numbers through SMS. Users signup with their phone number, I would then verify that it is really their phone number through SMS.
- Twilio has a phone verification service but it uses Authy app which means I would have to instruct my users to install authy if I wanted to use the service. I didn’t want such. I wanted users to be done with verification in a jiffy and that’s better done with SMS since every phone has an SMS system.
- f I was to go with SMS, then I needed a way to be generating random codes that expires and that I can trust. I didn’t want to build such service from ground up because I want to have 2FA some day in the app. It’s better i go with an already established package for such service. There comes `pyotp` to the rescue.
- f I was to go with SMS, then I needed a way to be generating random codes that expires and that I can trust. I didn’t want to build such service from ground up because I want to have 2FA some day in the app. It’s better i go with an already established package for such service. There comes `pyotp` to the rescue.
