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



![Insert your Use-Case Diagram Here](images/usecasediagram.png)

## Software Requirements Specification
### Functional requirements
* FR1: The system must be able to locate parks relative to an area (UC1).
* FR2: The system must be able to return a list of parks relative to an area (UC1).
* FR3: The system must be able to get the users location (UC1).
* FR4  The system must be able to display a graphical map (UC2).
* FR5: The system must allow users to interact with the map (UC2).
* FR6: The system must be able to accept search inputs (UC3).
* FR7: The system must be able to return results based on a search (UC3).
* FR8: The system must be to able to return search results with a filter (UC3).
* FR9: The system must be able to display information about a park (UC4).
* FR10: The system must be able to take the user to the park's website (UC4).


### Non-Functional Requirements
* NFR1: The system be able to retrieve the users location.
* NFR2: The system should suggest the user to expand their radius or choose a different location.
* NFR3: The system should load park results fairly quickly. 
* NFR4: The system should be able to make map markers or icons visible on the graphical map.
* NFR5: The system should should provide accessible alternatives to visual maps.
* NFR6: The system should return results accurately match chosen filters.
* NFR7:The system should be able to returnmatching Users can select multiple filters or remove.
* NFR8: The system should provide information should be easy to read and understand.
* NFR9: Park information should be accurate.