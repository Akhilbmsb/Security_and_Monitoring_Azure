## Security_and_Monitoring_Azure

# Clone the Backend Repository:
```
git clone https://github.com/UnpredictablePrashant/ResumeAI backend

```

# Create a .env File:
# Create a .env file in the backend directory with the following fields:

```

JWT_SECRET_KEY=""
MONGO_URL="mongodb://MONGO_URL"
OPENAI_KEY=""
GMAIL_USER=""
GMAIL_PASS=""
FRONT_END=""

```
# Containerize the Backend Application:
# Navigate to the backend directory and run the following command to containerize the application:
```
docker build -t backend .
```
# Clone the Frontend Repository:

```
git clone https://github.com/UnpredictablePrashant/ResumeAI frontend
```
# Containerize the Frontend Application:
# Navigate to the frontend directory and run the following command to containerize the application:

```
docker build -t frontend .
```

![image (4)](https://github.com/Akhilbmsb/Security_and_Monitoring_Azure/assets/54345937/7d445397-f671-4ded-a523-9efbe6ebcade)


