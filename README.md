# csp-interview-schedule-display
Content Scheduling and Planning React Interview Test

## Scenario 
Sky wants to modernise their existing back-office systems, moving away from stand-alone monoliths and into Web based applications. The first thing we want to do is to provide a new way of creating, visualising and interacting with TV schedules.

## Test Description 
The first phase of this project consists in being able to visualize the schedule information for a given date and channel. To finish the first phase, we have to complete two stages. If you need to add more libraries, please state why on this README file.

**We advise that you read some of the notes, further down on this document, in order to get to know which libraries were used and the commands that starts the ui and services** 

### First Stage – Adding Form Validation
----
Currently with the UI, a user is able to try visualize a schedule, without providing all the fields that are mandatory:
* Channel
* Schedule Date

It is part of the requirements, that upon clicking on "View Schedule" without having all the mandatory fields filled, it should render the message "Please provide all fields before submitting" and stop any further action.

**We expect to see the use of TDD.**

### Second Stage – Fetching and display the Schedule
----
The API that returns the schedule is available available on the following endpoint:
http://localhost:3001/schedule-repo/api/v1/schedule?channel={channel_input}&date={channel_input}

The requirement that was given to us was to fetch the data, and display it as table, with the following columns:
* Start Time
* End Time
* Title Name

**Please ensure you use TDD.** 

## Notes
Libraries used:
* create-react-app - used to create the skeleton of the app
* semantic-ui-css - the css framework that gives the styling
* semantic-ui-react - provides react components for the styling components from semantic-ui
* react-datepicker - a date picker component
* moment - library to handle dates and times
* react-input-mask - library that provides

To start the application:
* npm install / yarn install 
* npm start / yarn start
