## American Printing House for the Blind: Indoor Explorer


### Statement of Problem
The blind and visually impaired population have difficulty utilizing amenities, locating points of interest and navigating areas designed for sighted individuals. A city’s built environment is difficult to access and navigate for any individual that does not possess the same sensory inputs as the majority population. Accomplishing tasks that are trivial for a sighted individual become formidable, when visual and directional cues such as signage or terrain information are unavailable to the citizen.

Our cities and building interiors are not as technically developed as the tools that we use for communications, but these tools can mitigate this imbalance in environmental access, through the usage of pervasive, cheap and mature electronics.

### Point of View Use Cases

Here are a few example point of view use cases that illustrate the difficulties that a visually impaired or blind citizen will encounter when attempting to maneuver an environment that is primarily used by sighted individuals.


|User|Need|Insight|
|---	|---	|---	|
|A visually impaired adult who lives on the edge of Jefferson County.|To go to a downtown government office to file paperwork.|The user would have difficulty locating the appropriate schedule, bus and location of a bus stop, to travel downtown, and navigate the the streets required to locate the government office to file their paperwork. GPS can assist with a portion of this activity, but fails when the user is in an area that has tall buildings, or when the user transitions to an indoor setting.|
|A visually impaired adult who is at the airport.|To check-in for their airline flight, and find the appropriate gate.|The process of navigating the check-in process, the security gate, and finding the proper terminal is hard when the environment is dictated by a variety of human defined processes. Locating the ticket counter, navigating security and finding other points of interest such as the departure gate are problematic without visual aides. GPS is unable to assist for navigation due to the indoor setting.|
|A visually impaired user who is at a public event indoors.|To utilize amenities such as concessions or public bathrooms.|Locating points of interest in a multi floor environment is confusing without visual aides such as signage.|

### Subject Matter Summary
Indoor navigation deals with navigation within buildings. Because GPS reception is normally non-existent inside buildings, other positioning technologies are used when automatic positioning is desired. Bluetooth beacons (Bluetooth Low Energy, BLE) are often used in this case to create a so-called "indoor GPS". Indoor navigation using beacons is widespread because Bluetooth transmitters function across platforms and have an accuracy of 1-3 meters. The most well-known types are called iBeacon (from Apple) and Eddystone (from Google). Both operate using the BLE standard (Bluetooth Low Energy) and thus are very energy efficient.

One popular indoor navigation has been developed for people who are blind or have low vision. It is used in more than 130 countries by more than 10.000 people. It announces public locations to users within a building like washrooms and elevators when they approached by a user equipped with a mobile device. It works in conjunction with a set of beacons that are small, low energy Bluetooth devices. These devices broadcast a unique ID that can be received by smartphones and sends messages to the user.

Louisville Metro Government has partnered with the American Printing House for the Blind to install these bluetooth beacons in publicly accessible buildings, and map these indoor spaces for accessibility and public usage, with all data generated contributed to OpenStreetMap. It is an exciting and innovative opportunity to improve public buildings for all in our community through their Indoor Explorer platform.

The Indoor Explorer program, which is operated by the American Printing House for the Blind and created in partnership with the city’s Office for Civic Innovation, places low-power Bluetooth beacons in public buildings that feed information about  points of interest such as stairs, exits, bathrooms and other amenities to a mobile application called Nearby Explorer.

Nearby Explorer is an application that is developed and maintained within the American Printing House for the Blind, by their technical application development staff. When used outdoors, this application receives location data from GPS signals via radio, and when it loses connectivity to these satellites, it switches to an indoor mode, which polls for bluetooth beacons in the area.  This application converts geodata from OpenStreetMaps to contextual audio triggers, which describe the users environment based on their location, whether that location is indoors or outdoors.

The combination of mapping and surfacing indoor geo-enriched data, empowers visually impaired citizens with the ability to navigate their environment with greatly improved utility, leveraging a robust smart city technology for a compassionate solution.

In December 2017, the Louisville International Airport (SDF) became the first fully accessible airport to travelers who are blind or visually impaired and in January 2018, the Kentucky Center for the Arts became the first fully accessible performing arts venue to patrons who are blind or visually impaired.

### Project Timeline of Events

02/13 - Nearby Explorer deployed to visually impaired community  

02/15 - Louisville Metro releases open data for event, consisting of address & building data. APH and community volunteers process and import data into OpenStreetMaps.  

09/16 - Louisville Mayor Greg Fischer writes letter supporting Louie Braille’s 1829 book  

08/17 - Louisville Metro Government was approached by APH to support project.  

06/17 - Louisville Mayor Greg Fischer writes letter supporting project  

07/17 - APH began grant application process for James Graham Brown Foundation  

09/17 - Grant awarded  

09/17 - First location deployed, LouieLab & Office of Performance Improvement & Innovation  

10/17 - Subsequent locations identified & prioritized over the next year.   - LouieLab, Office of Performance Improvement & Innovation
  - Louisville International Airport  
  - Kentucky Center for the Arts  
  - Frazier Museum  
  - JB Speed Art Museum  
  - Kentucky Derby Museum  
  - 21c Hotel  
  - Louisville Metro Hall  
  - City Hall  
  - Hyatt Regency Downtown  
  - Louisville Visitor Information Center  
  - Louisville Free Public Library - Main Branch  
  - Louisville Free Public Library - Crescent Hill  
  - American Printing House for the Blind  
  - Visually Impaired Preschool Services (VIPS)
  - Walgreens

09/18 - Ongoing deployment of locations as identified  

### Steps for implementation

This project relies on several key stages for implementation.  

  - Problem identification & requirements  
  The blind and visually impaired population have difficulty utilizing amenities, locating points of interest and navigating areas designed for sighted individuals. Users require a cost effective and pervasive method to navigate and access their environment.

  - Community partner  
  American Printing House for the Blind (APH) is the world’s largest nonprofit organization creating educational, workplace, and independent living products and services for people who are blind and visually impaired.

  APH received a federal mandate in 1879 when the Congress of the United States passed the Act to Promote the Education of the Blind. This act designates APH as the official supplier of educational materials to all students in the U.S. who meet the definition of blindness and are working at less than college level.

  As they are the official supplier of these materials and services, they are a key stakeholder in implementation and deployment of this technology. To work with APH to deploy bluetooth beacons for the visually impaired in your city, please contact Bob Belknap, the Vice President of Development with APH.

  There are other implementations of assistive technology for the visually impaired that can be used as a template or guidelines for implementation of a similar project, such as the Massachusetts Bay Transportation Authority partnership with the Perkins School for the Blind in Watertown, Massachusetts. Their implementation however, only extends to public transportation and does not cover the use case of indoor navigation.

  https://www.raizlabs.com/work/mbta-beacon-technology/

  - Project scope & definition  
The scope of this project covers public areas in buildings that are frequently accessed by the general public. It does not include private or sensitive areas, and these are identified during the mapping process, before they are uploaded to OpenStreetMaps.

  - Grant funding source  
The James Graham Brown Foundation offers a grant for enabling exponential change and promoting the image of Louisville and improving the quality of life and well-being of our community. This grant was instrumental in creating revenue to purchase the beacons required for deployment, and was pursued by our community partner, American Printing House for the Blind. The labor of mapping, development and deployment are all absorbed by the community partner.

  - Data integration requirements  
**Open Data**  
  Building Outlines (https://wiki.openstreetmap.org/wiki/Louisville,_Kentucky/Building_Outlines_Import)  

  Right of way data (example:  https://data.louisvilleky.gov/dataset/louisville-streets-%E2%80%93-right-way)  
  Street network data (example: https://data.louisvilleky.gov/dataset/street-centerline)  
  Public signage such as traffic signs (example: https://data.louisvilleky.gov/dataset/traffic-signs)

  **OpenStreetMaps** (https://openstreetmap.org)  
  Familiarity and expertise with OpenStreetMaps  
  Storage of beacon location on OpenStreetMaps  

  - Technology selection & fit
APH has selected a variety of beacons based that are utilized. Depending on the use case and requirements of a location, whether it is a historic property, highly trafficked, or aesthetic considerations will determine the type of beacon used. The most recognizable, and frequently used beacon is manufactured by the company Estimote. These beacons operate on a small coin cell battery with an estimated environmental life span of 2-3 years. For deployment coordination, maintenance and upkeep of these beacons, we work with our internal Facilities team.

![alt text](Supporting Documents/beacon_section_no_logo.png)


  - Team identification, role/work assignments

  **American Printing House for the Blind**  
  Responsibilities:
  - Beacon acquisition  
  - OpenStreetMap data input  
  - Beacon installation (non-governmental properties)  
  - Application development, maintenance and operation

  **Louisville Metro Government**  
  Responsibilities:  
  - Citizen awareness  
  - Public/private partnership program coordination  
  - Business networking  
  - Target location identification  
  - Beacon installation (Louisville Metro properties only)  

### Key Findings, Summary
  - #### Business highlights  
A critical component of this project was the Mayoral Letter of Support for the American Printing House for the Blind's grant application to the James Graham Brown Foundation. This letter is a key document, illustrating Louisville Metro Government's commitment to partnership with American Printing House for the Blind, in addition to the community effort to build a smarter Louisville.

  - #### Size/Scale  
The goal for this project is to deploy bluetooth beacons to all publicly accessible properties in the Louisville Metro / Jefferson County area.

  - #### Supporting documents  

  **Program Support**
  - Mayoral Letter of Support (see included example)  
  - Memorandum of Understanding (see included example)  
  - Previous Supporting Government/Organizational Letter  (see included example)

  **Operational Support**
  - Architectural Floor Plans for deployment location  (see included example)  
  - Deployment Complexity Evaluation & Criteria  (see included example)

  **Deployment Locations**
  ![alt text](Supporting Documents/Miscellaneous Documents/deployment_locations.png)
  View Online: http://overpass-turbo.eu/s/BCP  
  - LouieLab, Office of Performance Improvement & Innovation
  - Louisville International Airport  
  - Kentucky Center for the Arts  
  - Frazier Museum  
  - JB Speed Art Museum  
  - Kentucky Derby Museum  
  - 21c Hotel  
  - Louisville Metro Hall  
  - City Hall  
  - Hyatt Regency Downtown  
  - Louisville Visitor Information Center  
  - Louisville Free Public Library - Main Branch  
  - Louisville Free Public Library - Crescent Hill  
  - American Printing House for the Blind  
  - Visually Impaired Preschool Services (VIPS)
  - Walgreens  


  - #### Media Coverage  
    - https://louisvilleky.gov/news/city-partners-american-printing-house-blind-expand-sensor-program
    - https://www.aph.org/pr/indoor-explorer-pilot-project-in-use-at-louisville-international-airport/
    - https://insiderlouisville.com/economy/wayfinding-system-for-visually-impaired-installed-at-louisville-airport/
    - https://www.whas11.com/article/news/local/american-printing-house-for-the-blind-leads-with-technology/417-516020931
    - https://alicenter.org/the-ali-center-teams-up-with-aph-to-expand-accessibility/

### Future State
This assistive technology is a powerful method to improve the experience of our citizens in their built environment. As it adds an element of "digitization" to that environment, this technology can also be leveraged in new and unexpected ways. These methods can include environmental sensing technology such as physical mapping & wayfinding, presence authentication, asset tracking, robotics applications or personalized information delivery.

### Implementation team  

**Program Team**  
Matthew Gotth-Olsen  (Innovation Project Manager)  
Larry Skutchan (Director of Technology Product Research)
Jeremiah Rose   (Technical & Mapping Coordinator)  
APH Implementation & Application Team   

**Executive Team**  
Greg Fischer  (Mayor, Louisville Metro)  
Grace Simrall  (Chief of Innovation & Technology)  
Bob Belknap  (Vice President of Development)  
