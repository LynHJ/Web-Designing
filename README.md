# Web Visualization Dashboard(Latitude)


## Background

![alt text](https://github.com/LynHJ/Web-Designing/blob/3842146701d6eacbb528ae81a07e6ac842cc9fe5/Images/landingResize.png)

This Project is using HTML and CSS to create a dashboard featuring the analysis that I have done.This website contains 7 pages. The topic of this project is about the impact of different latitudes on an area of the max temperature,the humidity,the cloudiness,and the wind speed.

The analysis has 3 steps, collecting data, plotting data, and analysing the plots. 

Firstly, I collected the data from OpenWeatherMap API. To make sure the dataset is unbiased when I analyse how latitude changes change climate, I called over 500 cities to cover lattitude from -90º to 90º and longitude from -180º to 180º.  

Then using Matplotlib to plot the dataset I have received from step1. 

Thirdly, I arranged my analyses in "Plots" pages.

### Source

The data set comes from OpenWeatherMap API. Database has over 500 cities' weather data.

![alt text](https://github.com/LynHJ/Web-Designing/blob/3842146701d6eacbb528ae81a07e6ac842cc9fe5/Images/data-lg.png)

## Content:
```
Project  
├── Images
│   ├── comparison-lg.png
│   ├── comparison-sm.png
│   ├── data-lg.png
│   ├── data-sm.png
│   ├── landing-sm.png
│   ├── landingResize.png
│   ├── nav-lg.png
│   ├── nav-sm.png
│   ├── visualise-lg.png
│   └── visualise-sm.png
├── README.md
├── Resources
│   ├── CityData.csv
│   └── CityData.html
├── assets
│   ├── css
│   │   └── style.css
│   └── images
│       ├── LatCloud.png
│       ├── LatHumi.png
│       ├── LatMaxt.png
│       └── LatWindSd.png
├── index.html
└── visulisations
    ├── Cloudiness.html
    ├── Comparisons.html
    ├── Humidity.html
    ├── Max Temperature.html
    └── Wind Speed.html

```
## Website Link:  https://lynhj.github.io/Web-Designing/




