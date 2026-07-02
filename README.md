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

## Screenshots

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/25fcae33-85c6-4f47-8a57-799458514c6d" />

Unfortunately, the backend database has been lost to time, which breaks all the protected routes. I will revisit this project and likely reinstate a static database for display purposes.
