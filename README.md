# Project2023
# SIT Clubs Information System

This is a simple C++ program that allows users to learn more about various clubs at Symbiosis Institute of Technology (SIT).

## Features
- Displays information about different clubs.
- Access club-specific actions: media, documentation, photography, events, and links.
The Club superclass has attributes of name and description, and methods of displayClubInfo(), menu(), media(), documentation(), photography(), events(), and link(). The subclasses are DanceClub, DramaClub, CodingClub, ArtClub, SportsClub, and MusicClub, each with the same methods as the superclass. However, SportsClub does not have a link() method, and MusicClub does not have a photography() method.
## Getting Started
The program starts by presenting a menu for selecting a club to learn more about.
You can enter a number from 1 to 7 to choose a club or exit the program.
If you choose one of the clubs (e.g., "1. Music Club"), it will display information about the selected club, such as the name and description.
It will then present a submenu for actions related to that club:
Display Club Information
Media
Documentation
Photography
Events
Go back to the main menu
You can select an option from the submenu, and the program will execute the corresponding action, providing information about that aspect of the club (e.g., media activities, documentation tasks, etc.).
You can navigate through these actions, and at any point, you can choose to go back to the main menu by selecting option 6 in the submenu.
You can repeat this process for different clubs or exit the program by selecting option 7 in the main menu.

### Prerequisites

- C++ compiler (e.g., g++)
- Standard C++ library

### Installation

1. Clone the repository.
2. Compile the code using a C++ compiler:
   ```bash
   g++ -o sit_clubs_info main.cpp
