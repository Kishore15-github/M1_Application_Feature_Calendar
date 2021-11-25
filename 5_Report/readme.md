## Calendar
## The Abstract of the Project is to develop a a application without graphics in C language  

A calendar is a system where it keeps our days orgainzed ,the organized schedule is done by specific time at a particualar day, month in a  
year . A calendar is to be informed about or to agree on a future event and to record an event that has happened. Days may be significant for agricultural, civil, religious, or social reasons. Calendars play an important role in our daily work to help us stay on task as well as be productive and prioritize. By using them to schedule our daily work we can avoid distractions and get back on track when interrupted.

# Features
Easy to access 
Low memory storage

## SWOT ANALYSIS
### STRENGTH
It keeps us oraganized
Helps to be accountable

### WEAKNESS
Data corruption

### OPPURTUNITIES
Easy to access
Low memory storage

### THREATS
Similar Applications with advanced features.

## 4W'S AND 1'H
### Who
A calendar is a system of organizing days. This is done by giving names to periods of time, typically days, weeks, months and years. A date is the designation of a single, specific day within such a system

### When
Calendars are also used to help people manage their personal schedules, time, and activities, particularly when individuals have numerous work, school, and family commitments.

### Where
The Calendar application  is accessable at Phone,Laptops,smart watches etc.

### How
Giving the input of the year which we want ,the outoput will be displayed.

## Requirements 
## High level requirements
| Plugin | README | Status (Implemented/Future) |
|----------|--------|-------------------------|
|Iot |Upating calender with connecting aut mated devices  with iot and schedule the work with iot devices |Future |

## Low level requirements
|Plugin | README | Status (Implemented/Future)  |
|-----------|----------|--------------------|
|Weather forecast |Updaing next 10 days weather forecast |Future |
| Addings Reminder/Events|Adding important notes and get notified |Future |
|Better UI design |Updating the application with beter UI design |Future |

## Design
## The design of this project is implemented by the input provided  from the  user
### First after getting the input,it start to find the starting index of the year ,then the month and check all the months in year will with appropriate dates will be given to the user then find the no of days then the output is displayed

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       |Checking whether the days are correct in every month |Year|Success|Success|Requirement based|
|  H_02       |Checking the calendar format is correct year/month/days.|-|Success|Success|Scenario based|
|  H_03        |Checking whether the user can edit the year which they want|-|Success|Success|Boundary based|

## Table no: Low level test plan

| **Test ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01      |Program running without bugs|-|Success|Success|Requirement Based|
|  L_02      |Program excecuting in all platforms|-|Success|Success|Scenario Based|
|  L_03      |Offline application |-|Success|Sucesss|Boundary based|
