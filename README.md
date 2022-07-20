# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into three parts:
1. [The Simple Frontend](https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-frontend)
A basic Ionic client web application which consumes the RestAPI Backend. [Covered in the course]
2. [The RestAPI Backend](https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-restapi), a Node-Express server which can be deployed to a cloud service. [Covered in the course]
3. [The Image Filtering Microservice](https://github.com/udacity/cloud-developer/tree/master/course-02/project/image-filter-starter-code), the final project for the course. It is a Node-Express application which runs a simple script to process images. [Your assignment]

## Tasks

### Setup Locally

You can setup the app locally following the below steps.

Fork or Clone the repo to your local machine.

Open the folder in your machine and install the necessary dependencies as follows


1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`
3. The app should start on the localhost

### A live version of this app is running on AWS

Visit the URL below to check the app

```
http://udacity-udagram-shuchou-dev.us-east-2.elasticbeanstalk.com/
```

You can filter an image using the following endpoint

```
/filteredimage?image_url=<URL>
```

For e.g. you can try to give the below image URL and see the results

/filteredimage?image_url=https://cdn.pixabay.com/photo/2022/04/29/17/48/lofoten-7164179_960_720.jpg

The app should return the filtered image if all goes well, else you will recieve an error







