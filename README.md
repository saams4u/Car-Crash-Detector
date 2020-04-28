## Getting the Dataset
You can scrape the dataset by using this notebook - it will download the dashcam video clips from YouTube: https://github.com/rwk506/CrashCatcher/blob/master/YouTube_scraping.ipynb

## Inspiration
After watching the Tesla Autonomy Conference, I felt quite inspired to build an AI system which actually detects crashes from a standard dashcam in a vehicle (car).

## What it does
It detects w/ high accuracy whether the frames captured by video feeds generated by a dashcam are predicted to be classified as 'accidents' or 'non-accidents', as to insure better safety measures for drivers.

## How I built it
I built the application using both the Pytorch Deep Learning framework and the Google Colab environment, entirely on notebook cells as opposed to an editor like Sublime or Visual Studio.

## Challenges I ran into
Honesty, gathering and wrangling the data was the most challenging aspect of this task, as the activity required me to find, download, and split the data into training and validation sets. Another challenge was leveraging all aspects of Google Colab and Google Drive together in order to store and manipulate the data for both training and testing.

## Accomplishments that I'm proud of
As a fairly new deep learning engineer, I'm proud that I managed to figure out how to build a production-ready model to be used to help provide better safety measures for drivers on roads and highways.

## What I learned
During this hackathon, I learned that a rigorous amount of trial and error is required in order to yield good results. At first, when the hackathon began, I jumped from project to project and didn't know what to build. But as I scored through code repositories looking for inspiration, I managed to find something I liked to develop and managed to bring the project to life.

## What's next for Car Crash Detector
So I might consider deploying my deep learning model to a web application, further improve the test accuracy, and maybe even design a point-cloud based detector of vehicle movements as well.
