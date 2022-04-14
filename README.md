# UFOs

## Overview of Project

In this project, I will utilize JavaScript, HTML ,D3 and CSS to create an interactive and responsive website/app with BootStrap for anyone who likes to find out more about UFOs. 

## Purpose 

As we know, there are a lot of data regarding UFOs in our databases and people who likes to know more about them. By using this app, they will be able to filter the data by Date, City, State, Shape as well as Year of appearance and retrieve desired information quickly.  

## Results 

#### The following is a simple user guide for our users :

1. Once a user run the app, at the top of our app a button to reset the page and name of our app will be top of the page as <code>jumbotron</code> will be displayed. 

<img width="1280" alt="Screen Shot 2022-04-14 at 9 23 51 AM" src="https://user-images.githubusercontent.com/98676400/163410908-cae5000a-8f55-41cc-9af9-c7ac20246722.png">

2. As scrolling down through the page there is a section that provide with a brief statament from a sciencest Dr. Ursula F. Olivier and CEO/vocal anti-alien activist. That indicates there are different approaches for UFOs from different people. 

<img width="1269" alt="Screen Shot 2022-04-14 at 10 05 27 AM" src="https://user-images.githubusercontent.com/98676400/163418988-fefce912-841c-4a62-977d-48f79c11b131.png">

3. Next part and main part of the app is the filter. Wihout user input below is how the filter constructed with placeholders that guide user how to make their search .

<img width="1277" alt="Screen Shot 2022-04-14 at 9 28 22 AM" src="https://user-images.githubusercontent.com/98676400/163411742-da522757-b710-45e0-a181-ee56ca307bbb.png">

* As soon as a date is entered inside <code> Enter Date </code> by user in mm/dd/yyyy format, our app will shrink the data and display desired information for the date was entered. 

<img width="1269" alt="Screen Shot 2022-04-14 at 9 31 02 AM" src="https://user-images.githubusercontent.com/98676400/163412232-64ef84ae-e698-4b39-b450-055af61b6742.png">

* Next feature of our filter is City. This part will capture the data from the city where the user likes to have information about UFOs. Notice that <code>Enter a City </code> does not require to a date in  <code> Enter Date </code> field. 

<img width="1266" alt="Screen Shot 2022-04-14 at 9 37 08 AM" src="https://user-images.githubusercontent.com/98676400/163413465-d134de10-4233-4a49-b9d3-1066e37dc5f4.png">

* Another feature of our filter is State and Country. This part will capture the data from the State where the user likes to have information about UFOs after entering state and Country name in <code> Enter a State </code> and <code> Enter a Country </code> field. 

<img width="1270" alt="Screen Shot 2022-04-14 at 9 42 00 AM" src="https://user-images.githubusercontent.com/98676400/163414358-78132160-1629-4701-b69f-92a49423add4.png">

* Last feature of the filter is the Shape. his part will filter the data for Shape of the object has seen nd display to the user after entering shape in <code> Enter a Shape </code> field .

<img width="1263" alt="Screen Shot 2022-04-14 at 9 59 53 AM" src="https://user-images.githubusercontent.com/98676400/163417844-be8885b2-d35e-4db1-a2fb-73ebfa27ac19.png">

#### So far we have seen how each filter operate independently. Below shows that our filter can oparate with all fields being filled by user. 
<img width="1269" alt="Screen Shot 2022-04-14 at 10 02 56 AM" src="https://user-images.githubusercontent.com/98676400/163418439-45b668eb-48b2-40d5-8699-f5c30338c44f.png">

## Summary 
### Drawbacks
Our app is a good start for now, however there are few Cons that we can be improved with few lines of code such as follwing :

1. Entire data is being displaed everytime the app is run or refresh, that makes the app slower and longer to load up. 
2. Case sensivitiy is a major problem because if a user use upper case charatesr then our filter wont respond to this request and return to a blank table. 

### Recommadations for imprving the App:

1- Inserting a date selection box would help user to filter dates faster.
2- Our app responds as soon as a change is made in any field. Rather than that inserting a "Search" button will make it more user friendly.
3- UFO Sightings button is too far from the filter field, we can insert it in the same area wilth filter field. 

## Resources :

* Data :JavaScript Data <a href = "https://github.com/aktugchelekche/UFOs/tree/main/static/js" > data.js </a>
* Languages: JavaScript, HTML, CSS and Bootstrap 3
* Dependencies: D3

Aktug Cilekci . 
