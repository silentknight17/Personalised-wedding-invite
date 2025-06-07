
# Personalised Wedding Invitation (Virtual Influencer)

This project automates the creation of personalized wedding invitation videos (which can be used to create Virtual Influencers too) using audio generation, image hosting, and video synthesis APIs. The process is interactive and executed in Google Colab.


## Features

- Allows user to upload any audio of his/her voice followed by uploading of a clear image (the user should be focused and should be facing the camera)
- Allows user to input the comma seperated names of people he/she wants to generate the videos for
- Generates personalized audio messages using Play.ht.
- Create videos dynamically with D-ID.
- Generate the final wedding invitation video with Json2Video.
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
- ### Json2Video
    For generating the final wedding invitation video.
    
- ### Google Colab
    Used because of it's preinstalled python libraries, giving access to Google Hardwares, storage in Google Drive and  free access to computing resources, and integration with other tools.Colab notebooks allows us to combine executable code and rich text in a single document, along with images, HTML, LaTeX and more
- ### Language Used 
    Python-3 (via Google Colab)


    
## Demo

Link to the videos generated -

 -  Final Customised Video - Links cannot be shared as it contains influencer images for which permission is required. 
 -  Intermediate Generated Video - https://drive.google.com/file/d/1MbnelReTcV9Yrxyz72w6R0AJ2q2TaHwX/view?usp=sharing




## Future Potential
- The apis are available for Node.js as well which can be utilised to create an end to end product which can be fed with a prompt as well and the video will get generated. 

- Tweaking the usecase of the generated video might help in other business verticals too (interviewing in case of Naukri and Virtual Chatbot in case of 99acres).

- The excel sheet containing list of names and text (generated from gpt api) can be fed to the overall model which can generated different videos for different persons.

- Can be used by Marketing team to generate Topical Videos or Greetings.

- Monetise the service as a premium feature in whichever business it is required.
## Collaborators
 - Sarvagya Prateek

## Note
1) The code contains certain keys which are unique for accessing the different features. In the code, the keys used are exposed since they were available for free, but it has to be hidden incase this product is deployed.
