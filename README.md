
# Personalised Wedding Invitation (Virtual Influencer)

This project automates the creation of personalized wedding invitation videos (which can be used to create Virtual Influencers too) using audio generation, image hosting, and video synthesis APIs. The process is interactive and executed in Google Colab.


## Features

- Allows user to upload any audio of his/her voice followed by uploading of a clear image (the user should be focused and should be facing the camera)
- Allows user to input the comma seperated names of people he/she wants to generate the videos for
- Generates personalized audio messages using Play.ht.
- Create videos dynamically with D-ID.
- Preview videos within Google Colab and download it for sharing it to friends and relatives.


## Setup
- Clone or upload the code in the Google Colab.
- ### API Credentials
    Although the credentials for api keys are in the file itself for convenience of the panel, it may be noted that the Apis being used are paid and free version is only for certain credit. If the credit gets exhausted, the user might have to Generate New Api keys and replace it in the file at the location mentioned in the file.
    
- ### How to use
    After uploading the file in the Google Collab, run the cell and follow the instructions. After all the inputs, the final personalised videos will be generated for the different names being given as input by the user.

- The video is playable in the Google Colab which can also be downloaded via the link generated for downloading the video.
## Technologies Used
- ### Play.ht
    For the cloning of the voice the user inputs
- ### Cloudinary
    For hoisting the input image on cloud/server
- ### D-ID
    For generating the final personalised video from the audio generated via Play.ht
- ### Google Colab
    Used because of it's preinstalled python libraries, giving access to Google Hardwares, storage in Google Drive and  free access to computing resources, and integration with other tools.Colab notebooks allows us to combine executable code and rich text in a single document, along with images, HTML, LaTeX and more
- ### Language Used 
    Python-3 (via Google Colab)


    
## Demo

Link to the videos generated for a groom image generated from GPT -

 -  https://infoedge-my.sharepoint.com/:v:/p/sarvagya_prateek/EZbFqxrqTjNDlLHXS6xurXIBvxw47eYyJ8u-5txjmAbPKQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=c3w7oL

 - https://infoedge-my.sharepoint.com/:v:/p/sarvagya_prateek/EWJPObSUu-JGq4LO0Y3p1KkBTvVhmcN0I467jk_v1LNFHA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=egBM8M



## Future Potential
- The apis are available for Node.js as well which can be utilised to create an end to end product which can be fed with a prompt as well and the video will get generated. 

- Tweaking the usecase of the generated video might help in other business verticals too (interviewing in case of Naukri and Virtual Chatbot in case of 99acres).

- The excel sheet containing list of names and text (generated from gpt api) can be fed to the overall model which can generated different videos for different persons.

- Can be used by Marketing team to generate Topical Videos or Greetings.

- Monetise the service as a premium feature in whichever business it is required.
## Collaborators
    TEAM ID - 115
 - Sarvagya Prateek (sarvagya.prateek@jeevansathi.com) [Team Captain]
 - Sandesh Dudhabaware 