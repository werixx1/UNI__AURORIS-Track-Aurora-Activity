<div align="center">
   
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![CustomTkinter](https://img.shields.io/badge/CustomTkinter-2B2B2B?style=for-the-badge&logo=python&logoColor=white)
![WebView](https://img.shields.io/badge/WebView-0078D4?style=for-the-badge&logo=googlechrome&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-2CA5E0?style=for-the-badge&logo=python&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-8CAAE6?style=for-the-badge&logo=python&logoColor=white)

</div>

# UNI__AURORIS-Track-Aurora-Activity
Auroris is an interactive application that helps users track aurora activity and view live aurora transmissions from various locations. The app allows users to check if aurora is visible in their area based on their location (IP) and provides information about the KP index (auroral activity) and whenether it's high enough to see aurora. It also provides live streaming of auroras from popular locations worldwide.
> Compsci course: Second year, first semester [python programming course]

<img src="https://github.com/user-attachments/assets/d83299de-fe1e-486c-8655-446e156b6744">

## Features
- Current Location Detection: Automatically retrieves the user's geographic location (latitude and longitude) using the IP address.
- Aurora Forecast: Fetches the current KP index for auroral activity at the user's location to indicate whether auroras are visible.
- Live Viewing: Provides links to live aurora streams from various locations around the world.
- Resources: Includes links to relevant APIs and libraries used in the app.

## How it Works
   - Get User Location: The app uses the IP address to determine the user's current geographical location (latitude and longitude).
   - Aurora Data: The app uses the Auroras Live API to fetch the KP index data, which represents auroral activity.
   - Distance Calculation: The app calculates the distance between the user's location and other popular aurora viewing spots using the Haversine formula.
   - Live Streams: Based on the aurora visibility, users can view live streams of the aurora from different parts of the world.

## Project Structure

```
auroris/
├── src/                    # Application source code
│   └── images/             # Images used in the GUI
├── docs/                   # Additional documentation
└── README.md
```
## Figma elements used to design GUI
- [Stars Pack](https://www.figma.com/community/file/1020701317322253884)
- [Borealis Themed Editable Gradients](https://www.figma.com/community/file/1101849114331939744)
- [Noise Plugin](https://www.figma.com/community/plugin/752558325552095625/noise)

## License
This project is distributed under the MIT license.

