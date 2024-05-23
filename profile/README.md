# MangBeli App

The **MangBeli App** is an innovative mobile application designed to improve the experience of customers who frequently purchase from street vendors. The app provides accurate arrival time estimates and real-time notifications for street vendors based on their location. This helps to enhance users' productivity and quality of life by minimizing waiting time and reducing uncertainty.

## Table of Contents
- [Key Features](#key-features)
- [Screenshots](#screenshots)
- [Technology Stack](#technology-stack)
- [Design Pattern](#design-pattern)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Team Member](#team-member)
- [Contact](#contact)

## Key Features
1. **Estimated Time of Arrival (ETA):**
   - Provides accurate arrival time estimates based on the street vendor's current location.
2. **Real-Time Location Tracking:**
   - Utilizes advanced location tracking technology to update the street vendor's position in real-time.
3. **Proximity Notifications:**
   - Sends timely notifications to users when a vendor is within a certain distance from their location, ensuring they never miss a vendor.
4. **Route Direction:**
   - Optimizing direction routes, improving productivity and efficiency.
5. **User-Friendly Interface:**
   - Offers an easy-to-use interface for seamless interaction and a pleasant user experience.

## Screenshots
User Screen :
<br />
<img width="200" alt="0  SplashScreen" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/b573e00e-9ec2-4367-bc36-ece20cc277bb">
<img width="200" alt="4  Menu Activity" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/d1fbaa1c-e333-4ef4-8e8a-9f251f735cd3">
<img width="200" alt="5  Register" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/4bdb1a94-d679-484d-9bea-9dca4f82f0ed">
<img width="200" alt="6  Login" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/7956f07b-4012-4799-81ae-2901913df4bf">
<img width="200" alt="10  homePage" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/476252e3-25cb-4bf0-a485-aa6a7850ce88">
<img width="200" alt="11  detail" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/9faf0570-f345-449d-9517-284e5f1defa7">
<img width="200" alt="12  maps buyer(1)" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/8b03a336-9b40-4c1f-bfd5-7df454d6c0d4">
<img width="200" alt="13  maps buyer(2)" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/34ebf5c9-a921-4069-a1e5-f8c54cad3e16">
<img width="200" alt="14  profile" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/0c8b1165-eb98-44fb-8724-f51ebedf6adb">
<img width="20" alt="15  settings" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/190dc2c9-8fe4-4cfc-9d27-4a38e27415c2">
<br />
Vendor Screen :
<br />
<img width="200" alt="9  homePage Vendor" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/e240d38c-e91c-4ca2-ab8a-bb5741b2f33a">
<img width="200" alt="10  maps vendor" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/7a9c2f8f-c274-4c46-8ad3-2e9fbc27e851">
<img width="200" alt="11  profile vendor" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/c6f5ed3a-c0d2-41a2-90a1-c14dc6d0323b">
<img width="200" alt="13  notification" src="https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli/assets/69000583/99aa20db-7341-4541-b785-e111f0e8233f">

## Technology Stack
The MangBeli App is built using the following technologies:
- **Android (Kotlin):**
  - The primary programming language for building the app, offering robust performance and a smooth user experience.
- **Google Maps API:**
  - Used for location tracking, route estimation, and providing map functionalities.
- **Firebase:**
  - Utilized for real-time notifications, user authentication, and database management.
- **Custom Backend API:**
  - The backend system manages vendor data, user interactions, and provides necessary endpoints for the app's functionalities.

## Design Pattern
The app follows the MVVM (Model-View-ViewModel) architecture pattern, ensuring a clean separation of concerns and facilitating easier testing and maintenance of the codebase.

## Libraries and Dependencies
- **Retrofit:** Used for making HTTP requests to the backend API.
- **Glide:** Employed for efficient image loading and caching.
- **ViewModel and LiveData:** Utilized for managing UI-related data and lifecycle-aware observation.
- **Google Play Services:** Integrated for accessing Google Maps and location services.
- **Material Components:** Employed to maintain a consistent Material Design theme across the app.

## Usage
1. Run the application on your Android device or emulator.
2. Register or log in to the application.
3. Allow location permissions for the application to track your current location.
4. View nearby street vendors and their estimated arrival times.
5. Receive notifications when vendors are approaching your location.
6. Provide feedback and view transaction history through the application.

## API Integration
The application integrates with Google Maps Directions API to provide route and ETA information. It also uses a custom backend API for managing vendor data and user interactions. Ensure you have a valid API key and have enabled the necessary APIs in your Google Cloud Console.

For more details on the backend API, refer to the [MangBeli API Repository](https://github.com/Bangkit-Capstone-CH2-PS124-Team/mangbeli-api) and the [API Documentation](https://bangkit-capstone-ch2-ps124-team.github.io/mangbeli-api-doc/#/).

## Team Member
CH2-PS124 team from Bangkit Academy 2023 Batch 2.
Name | Bangkit ID | Learning Path | Github Profile
:---|:---:|:---:|---:
Abib Raifmuaffah Ihwan | M323BSY0169 | Machine Learning | [Profile](https://github.com/AbibRaifmuaffahIhwan)
Rifando Adeyansa Purba| M387BSY0100 | Machine Learning | [Profile](https://github.com/rfadeyansa)
Hijra S. Otji | M323BSX1176 | Machine Learning | [Profile](https://github.com/hijraotji)
Raafi Hilmi |  A193BSY2404 | Mobile Development | [Profile](https://github.com/raafihilmi)
Fadly Ramdhani | A012BSY2415 | Mobile Development | [Profile](https://github.com/FadlyRamdhani23)
Faiz Aditya Kurniawan | C193BSY3573 | Cloud Computing | [Profile](https://github.com/overdoshit)
Asep Permadi | C323BSY3388 | Cloud Computing | [Profile](https://github.com/Aseppermadi)

## Acknowledgements

We would like to thank the Bangkit program for providing us with this opportunity and the resources to complete this project. Special thanks to our mentors and peers for their support and guidance.

## Contact
For any inquiries or issues, please contact us at [Raafi Hilmi](mailto:raafihilmi90.com).

