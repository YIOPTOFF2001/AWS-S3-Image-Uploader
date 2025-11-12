# AWS S3 Image Uploader - Full Stack Spring Boot + React App

![Project Diagram](Images/image.png)


This project is a full-stack web application built with Spring Boot and React.js that allows users( customers) to upload images to Amazon S3 with ease through a secure and scalable setup. It demonstrates how to integrate a modern frontend with a robust backend, while securely handling image uploads to cloud storage. It’s built with Spring Boot (backend) and React.js (frontend), showcasing how to integrate cloud storage with a modern web stack.

## How it works

The app uses a simple but powerful architecture:
The React.js frontend lets users select and upload customer image. That image is sent to the Spring Boot backend, which validates and prepares it for upload. The backend then communicates with AWS S3, either by streaming the image directly to the bucket or generating a pre-signed S3 URL for the frontend to upload securely without exposing credentials. The customer is able to update and delete images in their account.
Once the upload completes, the backend stores image metadata  in the database and returns the file link for display in the app.



## Features

Upload images and files directly to an AWS S3 bucket.

Retrieve and display uploaded files dynamically.

Handles file validation and error management.

Full-stack integration: Spring Boot backend + React.js frontend.

## Technologies Used


Backend: Java, Spring Boot, Spring Data JPA, Maven

Frontend: React.js

Cloud Storage: Amazon S3

IDE: IntelliJ IDEA

Database: PostgreSQL, MySQL

Infrastructure: Docker


## Project Structure

backend/ → Spring Boot backend with S3 service integration.

frontend/ → React.js frontend for file upload interface.

## Quick Start

Follow these steps to run the project locally:



