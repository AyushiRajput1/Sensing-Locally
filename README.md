# Sensing Locally

## Abstract

Government in India is facing difficulties in managing urban development sustainability.
Sensing Local Volunteers are dropping off due to hustle being employed and there is lack of streamlined data
collection(Photos and videos).Also the existing solution requires more time to cover less distance.
As a result, walkability audits exhibit reduced effectiveness and limited scalability.

So We developed a user-friendly and accessible mobile application for citizens to document walkable areas as they
traverse the streets. By simply opening the application, Users can effortlessly enable the camera and capture walkable
areas with a single click of a button. This streamlined process will contribute to produce reliable evidence based data
along with Geo-location.

## Requirements

1. Flask API
2. Flutter
3. Node.js
4. Keras
5. MongoDB

## Steps of building this project

1. Firstly, We worked on developing the Frontend UI using Flutter, where the user can interact and capture the image of the walkable areas.

2. Then this image is being sent for classification to the CNN model. Here we are using Node.js to interact between the UI and receiving the predicted label from Flask API.

3. Further, this label along with geo-location and image is being saved to the database.

## Solution Screenshots
![1](https://github.com/AyushiRajput1/Sensing-Locally/assets/104836701/1e13cf82-0b2b-4fa6-a801-f871afa8dcbb)


