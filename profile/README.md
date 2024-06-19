# kuSaku: Atur Saku, Pakai kuSaku 📊💸

## Background

Current budgeting apps struggle to categorize user expenses accurately, leading to frustration and hindering effective financial management. Additionally, generic budgeting advice often fails to consider individual goals, discouraging users from reaching their savings targets. 😕

We believe everyone deserves the tools to achieve financial security. By creating a user-friendly platform that leverages advanced machine learning for accurate expense categorization and offers personalized budgeting guidance, we aim to empower individuals to take control of their finances and reach their savings goals. This will not only alleviate the stress of financial management but also contribute to greater financial well-being. 💪✨

## Machine Learning

Implement a model that categorizes user expenses using NLP with transfer learning from Pre Trained LLM (RoBERTa and DistilBERT). Preprocess the data with augmentation and balancing. Save the model in h5 and tf.js formats for deployment. RoBERTa's accuracy is slightly better, but DistilBERT has a smaller inference time. Next, add an advice feature for user reminders using data from BPS, extracted into CSV. Augment the data and build a machine learning model with Keras Sequential architecture, saving it in h5 format. The model's MAE on training data is stable at around 0.86. 🤖📈

## Mobile Development

We've designed an app to meet user needs and ensure it is user-friendly. We chose green as the primary color because it has a calming effect and represents money. To present expense data clearly, we use a friendly format like pie charts, making it easy for users to interpret the information. We implemented a schema for access tokens and refresh tokens to allow users to use the app smoothly without frequently needing to re-authenticate. Our UI design is minimalist, giving the app a sleek and premium feel. 📱💚

## Cloud Computing

We developed the backend as a service that can receive requests and provide responses to users, ensuring the application operates according to its functionality and requirements. We built the backend services using JavaScript with the Node.js and Express.js frameworks. Additionally, we integrated a pre-built machine learning model into the application using Python with the Flask framework. The database was designed using a NoSQL schema with Firestore. We ensured that the API was built to meet the application's needs and functions properly. We deployed the backend service through Cloud Run and Google Compute Engine. Moreover, we leveraged Cloud Functions and Cloud Scheduler to manage services triggered by specific time schedules. ☁️🖥️

