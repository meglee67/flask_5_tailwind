# flask_5_tailwind
* HHA 504 HW 5
* Due 11/5
* OG Instructions below
<br>

# Video Procurement
* I screencaptured a clip from this [Persona 5 Rainy Mood 10 Hours](https://youtu.be/Uq7kyf1T_lk?si=SrG_0MLiR0i3l0bb) video. I chose this because this is what I listen to when I need to sit down and get through alot of work.

# Cloud CDN & Video Hosting
* This was fairly simple, I chose to use GCP and followed their guide of setting up [Media CDN](https://cloud.google.com/media-cdn/docs/quickstart)
* I hit the guide me button and it led me through step by step within the Google Cloud Console, though I was unable to proceed past the step where you begin to set up a "Create an origin to connect Media CDN to your bucket". I was unable to do this as I didn't have permissions for accessing Media CDN, and it wouldn't show up as an option in my menu.
* I was still able to generate cloud storage link from where others could access my video and it worked for the flask deployment.

# Flask App with Tailwind CSS
* I just copied and modified the code from [Week 5 templates](https://github.com/hantswilliams/HHA_504_2023/blob/main/WK5/example_app/templates/index_tailwind.html)

# Cloud Deployment
* I was able to get the flask app to run locally within cloud shell, but I ran into issues when trying to deploy to Google Cloud Run. I attempted to follow this [deployment quickstart guide](https://cloud.google.com/run/docs/quickstarts/build-and-deploy/deploy-python-service) but was unsuccessful

# Screenshots
![image](https://github.com/meglee67/flask_5_tailwind/assets/123908362/57225c94-c4f1-4b62-aaa1-386fb3bae5da)
![image](https://github.com/meglee67/flask_5_tailwind/assets/123908362/1f560748-9715-43e1-a72d-13025e0b0f48)


<br>

# **Week 5 Homework Assignment: Video Hosting, Flask App & Cloud Deployment**

## **Objective**:
This assignment will give you hands-on experience in video hosting, creating a Flask app styled with Tailwind CSS, and deploying it to a cloud platform. You'll leverage CDN services in Google Cloud or Azure to optimize video delivery, ensuring a seamless user experience for viewers worldwide.

## **Instructions**:

### **1. Video Creation or Procurement**:
- Find a relevant video or create one using Zoom that resonates with a theme of your choice.
  - If you're creating a video, make sure it is clear, concise, and of reasonable length (< 60 seconds).

### **2. Cloud CDN & Video Hosting**:
- Host your video on a CDN, either Google Cloud's Cloud CDN or Azure's Content Delivery Network (CDN).
  - For Google Cloud, refer to their official [documentation](https://cloud.google.com/cdn) on setting up and using Cloud CDN.
  - For Azure, refer to their official [documentation](https://docs.microsoft.com/en-us/azure/cdn/cdn-overview) on setting up and using Azure CDN.

### **3. Flask App with Tailwind CSS**:
- Create a Flask app and use Tailwind CSS to style a video player interface that embeds your hosted video.
  - Ensure your design is clean, intuitive, and responsive across various device sizes.
  - If you're new to Tailwind CSS, explore their [documentation](https://tailwindcss.com/docs) for guidance.

### **4. Cloud Deployment**:
- Deploy your Flask app to a cloud platform, either Google Cloud Platform (GCP) or Microsoft Azure.
  - For GCP, you can use Google App Engine or Google Kubernetes Engine.
  - For Azure, you can use Azure App Service or Azure Kubernetes Service.
  - Provide screenshots of your deployed app running on the chosen cloud platform.

### **5. Validate Asset Delivery** *(Optional)*:
- Confirm and validate that your video and other assets (like CSS, JS) are indeed being served from the CDN.
  - This can be checked using browser developer tools or services like GTmetrix.
  - Provide screenshots or other evidence showcasing the CDN's URL and the faster load times as a result of using the CDN.

## **Submission**:
- Create a new GitHub repository named `flask_5_tailwind` in your GitHub account.
- Prepare your GitHub repository:
  - Your Flask application with integrated Tailwind CSS design and embedded video player.
  - Screenshots or videos showcasing the responsive design across different device sizes.
  - Screenshots confirming assets are being served from the CDN.
  - Screenshots of your deployed app running on the chosen cloud platform.
  - Any optional task documentation, especially regarding CDN configurations and asset delivery validation.
  - A detailed README.md file, outlining:
    - Your design rationale and principles followed.
    - Steps for setting up and using the CDN with your Flask app.
    - Steps for deploying your Flask app to the chosen cloud platform.
    - Your observations and benefits of using a CDN and cloud deployment.
    - Any challenges encountered and how you addressed them.
- Share the link to your repository as your assignment submission.
- Ensure your repository is public so that it's accessible for review.

**Tip**: Performance matters! The more optimized your assets are and the better they're served (e.g., via CDN), the better the user experience.
