**NOT MAINTAINED ANYMORE**

# Covid 19 India Flutter App**

This Flutter application, focused on Covid-19 in India, is no longer actively maintained.

**Inspiration from Covid19India.org:**
The idea for this app was inspired by the [Covid19India.org](https://www.covid19india.org/) website, which is an open-source React application available on GitHub ([covid19india/covid19india-react](https://github.com/covid19india/covid19india-react)). 

**Contributions Welcome:**
While the project is no longer under active development, contributions from interested developers are still welcome. If you would like to contribute, feel free to initiate a discussion by commenting on existing issues or by opening new ones.

**Technical Documentation:**
For those interested in the technical aspects of the app, you can find detailed technical information, including architecture, libraries used, SVG map generation, and more, in the [`docs`](docs/) folder.

**Screenshots:**
A recorded GIF showcasing the home screen is available above. However, please note that the GIF quality might not be the best. For a higher quality recording in WEBM format on YouTube, you can watch it [here](https://youtu.be/h3p9_ntxgd4).

**Running the App:**
To run the app, execute the following command:
```bash
flutter packages pub run build_runner build
```
If this command fails, make sure to run:
```bash
flutter packages pub upgrade
```

**Downloading the App:**
The app is not intended to be published on any app stores. However, the possibility of providing downloadable APKs in the future is under consideration.

**Credits:**
The app draws inspiration, design elements, and data (backend API) from the [Covid19India.org](https://www.covid19india.org/) website. The website's source code, built with React, and the TopoJSON-format maps of India are valuable contributions to this project.

Additionally, the GraphQL wrapper around the covid19india API from [covidstat.info](https://covidstat.info/graphql) provides a more convenient API for this Flutter app.

Special thanks to the [Flutter Clickable Regions GitHub Repository](https://github.com/gi097/flutter_clickable_regions) for demonstrating how to implement clickable SVG regions in Flutter, allowing the app to convert TopoJSON data to SVG.

The app icon, depicting a virus, is based on an SVG icon freely downloaded from [FlatIcon](https://www.flaticon.com/free-icon/virus_2659970). Credit for this icon design goes to Freepik from www.flaticon.com.
