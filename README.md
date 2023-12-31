## Setting up the environment for Firestore
- Use python env with following commands:
```
cd Firebase

<!-- in windows -->
virtualenv venv
venv\Scripts\activate
pip install -r requirements.txt

<!-- in linux -->
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```
- [Create a service account](https://clemfournier.medium.com/how-to-get-my-firebase-service-account-key-file-f0ec97a21620) in Firebase console and download the json file. Rename it to `serviceAccountKey.json` and place it in the root directory of the project.

- go to [Google Cloud Console APIs](https://console.cloud.google.com/apis/library/firestore.googleapis.com?project=nosql-playground-522cd) Library and enable Firestore API for your project created on Firebase. Don't forget to create a database on firestore.
- Now you can run the Firestore demo code with `python Demo.py` command. Don't forget to go inside Firebase folder and activate the virtual environment as mentioned above.