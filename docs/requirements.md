# Requirements

## User Needs

### User stories
* as a citizen, I want to search for parks so that I can go to a specific park
* as a citizen, I want to filter parks by distance so that I know which parks are walking distance
* as a citizen, I want to use a map to so that I can go to a park close to me
* as a citizen, I want to find a park with disability options so that I can go to a park with mobility support
* as a citizen, I want to find a park with sporting equipment so that I can exercise
* as a citizen, I want to find a park with apparatus so that my children can go outside
* as a citizen, I want to look at park opening times so that I can plan my trip
* as a citizen, I want to look at photos of a park so I know which park I can go to

* as a city council worker, I want to use manage park information so that citizens can be updated with new information
* as a organisation, I want to see what parks are available so that I can use it as a venue for my event

### Actors
* Citizen  (local residents, visitor/tourists, parents, pet owners, athletes)
* City council
* Organisations

### Use Cases

| UC1 | Search for nearby parks around an area| 
| -------------------------------------- | ------------------- |
| **Description** | As a citizen, I want to find nearby parks by a given postcode/address |
| **Actors** | Citizen |
| **Assumptions** | The citizen knows their location
| **Steps** | 1. Opt to search for nearby green space 2. Request the user for permission to use their location, or ask them to input an address manually 3. Show parks, sorted from lowest to highest distance, based on the users address/location|
| **Variations** |1. Shows a map instead of a list 2. Shows time to get to destination with recommended modes of transport  3. Be able to recommend areas beyond than the users address (e.g expand to more areas)
| **Non-functional** | 1. Should be able to get the users location 2. Able to work on mobile devices 3. Suggest user to expand their radius or choose a different location 3. It should load results fairly quickly |
| **Issues** |1. The system is unable to locate parks nearby 2. Will it work if the user denies location permission |


| UC2 | View a map of nearby parks| 
| -------------------------------------- | ------------------- |
| **Description** | As a citizen, I want to find nearby parks by a given postcode/address |
| **Actors** | Citizen |
| **Assumptions** | The system has access to park location data 
| **Steps** | 1. The user opens the map 2. System displays map 3. The user is able to interact with the map (zoom in, zoom out) 4. The system is able to display park information |
| **Variations** |1. User can zoom in and out 2. The map should be easy to navigate
| **Non-functional** | 1. Map should load quickly and smoothly 2. Map markers should be visible 3. The map should provide accessible alternatives to visual maps |

| UC3 | Filter parks by facilities| 
| -------------------------------------- | ------------------- |
| **Description** | Find parks that have specifc capabilities or features |
| **Actors** | Citizen |
| **Assumptions** | There is information about the park
| **Steps** | 1. The user opens the filter menu 2. System displays avaiable filters 3. User selects desired facilities 4. System applies the filters 5. System returns results matching the facilities |
| **Variations** |1. User can select multiple facilities at once. 2. User can remove filters
| **Non-functional** | 1. Results accurately match filters 2. Users can select multiple filters |


| UC4 | View park information| 
| -------------------------------------- | ------------------- |
| **Description** | Learn more about a selected park |
| **Actors** | Citizen |
| **Assumptions** | User has selected a park
| **Steps** | 1. User selects a park 2. The system returns the park's name and description 3. The system displays photos, opening hours and facilities 4. The user can review the information|
| **Variations** |1. User wants additional accessibility information
| **Non-functional** | 1. Information should be easy to read and understand 2. Photos should load 3. Information should disability-friendly 4. Park information should be accurate |


TODO: Your Use-Case diagram should include all use-cases.

![Insert your Use-Case Diagram Here](images/usecasediagram.png)

## Software Requirements Specification
### Functional requirements
TODO: create a list of functional requirements. 
    e.g. "The system shall ..."
    Give each functional requirement a unique ID. e.g. FR1, FR2, ...
    Indicate which UC the requirement comes from.



### Non-Functional Requirements
TODO: Consider one or more [quality attributes](https://en.wikipedia.org/wiki/ISO/IEC_9126) to suggest a small number of non-functional requirements.
Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

