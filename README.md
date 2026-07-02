# Feature 6

Students: John Kapustka and Zach Vincent

Project Overview:
Website for easily uploading and sharing neural networks.

## Setup

Download and install the repository:

```
git clone git@github.com:zachvin/testify.git
cd testify
npm install
npm audit fix
npm run dev
```

The backend will run but will not function properly on another system because the Google Cloud and Kubernetes APIs require authentication, so model uploading/deleting will not work. However, the frontend is still functional, including submitting to neural networks. To verify that the backend at least runs, install the dependencies and run it:

```
cd backend
npm install
node server.js
```

> Note: I have replaced the original hosted backend with a simple sqlite storage server for demonstration purposes.

## Screenshots

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/25fcae33-85c6-4f47-8a57-799458514c6d" />

<img width="1918" height="1076" alt="image" src="https://github.com/user-attachments/assets/9d52beee-3abd-4f73-aaec-b99b5818c620" />

Note that submitting to the selected model errors out because I didn't have the foresight to save my demo recording on my University YouTube account before it was deactivated:

<img width="1918" height="1076" alt="image" src="https://github.com/user-attachments/assets/e75b4932-5d9b-47f8-9a02-5f6116981b8f" />

Here is where you could very easily submit a `.tar` file of your neural network with a `/predict` endpoint, fill out some basic information, then click 'Submit'. Your model would automatically host and become available for querying in the 'Marketplace' tab.

<img width="1918" height="1076" alt="image" src="https://github.com/user-attachments/assets/085ec78b-61b6-42fe-9e95-39ba8615d5ed" />




