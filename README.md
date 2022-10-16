# Med For The Win Application
The Med For The Win application is a healthcare application that gives patients an easy way of checking their health-realted data in a quick, reliable, an easy way that is all centralized to one place. To make our application function as intended, it implements Intersystem's API that includes an extensive database with healthcare patients and a gargantuan amount of attributes associated with each patient. The application fetches all the releevant data for a specific patient when the user inputs a valid patient ID at startup. Once a user gets into their personalized homepage, they will be able to access their allergy restrictions if any exist, personalized practitioners, immunizations, medical records and care plans. Additionally, the user will be able to locate all the hospitals around their location. This is made possible through the Keyhole Markup Language (KML), which is a XML annotation that expresses geographic coordinates within three-dimensional Earth browser applications, Liquid Galaxy, which is a open source service that elevates an Erth browser and makes it an immersive exprience, and editing drivers.ini files, which connect parent and chile computers using an IP address or some sort of communication key. The allergy restrictions are displayed in such a way where all the user's allergies will be displayed indivually on their own line. If the user does not have any allergies, "No Allergies" is displayed on the screen. The personalized practitioners function finds the closest practitioner to the user's current location based on all the practitioner's locations and reccommends the closest practitioner to the user, including a display with the practitioner's name, email, and the precise distance away, in miles, they are from the user. Finding the nearest practitioner makes use of cross triangulation methods, Vincente's Distance Calculator, an Ellipsoidal model, and the GeoPy Python library. The immunizations, medical records, and care plans function in a similar fashion to allergies, where all the elements are listed on their respective pages in as much detail as possible. This program was written using Flutter to develop the mobile app, Dart, and Python. Flask and Heroku were used to deploy the server to communicate the backend Python working with Intersystem's API with the mobile app.

Warm Regards,
Shreyes, Andres, Rushil, Ronit
