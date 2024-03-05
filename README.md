### Project Description: **Crypto Price Tracker Web App**

#### Overview
Develop a Flutter web application that fetches and displays real-time cryptocurrency prices using the Kraken WebSockets API. The app should dynamically display data based on the cryptocurrency specified in the URL route (e.g., `/crypto?btc` for Bitcoin). The application must follow the Model-View-ViewModel (MVVM) architecture and use the BLoC pattern for state management.

#### Core Features
1. **Dynamic Routing**: Implement routing in the Flutter web app that allows users to navigate to a specific cryptocurrency's page using URL parameters (e.g., `/crypto?btc` for Bitcoin).
2. **WebSockets Integration**: Use the web socket channel to establish a connection to the Kraken WebSockets API and subscribe to ticker information for cryptocurrencies dynamically based on the URL parameter.
3. **Real-Time Data Display**: On the cryptocurrency's page, display the real-time price information, including the current price, high, low, and percentage changes. Update these prices in real time as new data comes in.
4. **MVVM Architecture**: Structure the app using the MVVM architecture pattern. Define models for cryptocurrency data, views for user interfaces, and view models to act as an intermediary between the model and the view.
5. **State Management with BLoC**: Implement the BLoC pattern for managing the app's state, particularly for handling real-time data updates and navigation based on URL parameters.

#### Technologies
- **Flutter for Web** to create the web application.
- **Dart** for programming the application logic.
- **BLoC pattern** for state management, using packages like `flutter_bloc`.
- 
#### Evaluation Criteria
- **Functionality**: The web app must dynamically display cryptocurrency information based on URL parameters and update that information in real time.
- **Architecture and Code Quality**: The application should correctly implement the MVVM architecture and BLoC pattern, with clean, well-organized, and documented code.
- **UI/UX Design**: Despite being a simple web app, the interface should be user-friendly and responsive, ensuring a good user experience on various devices.
- **Deployment**: The app should be deployed and accessible online, demonstrating the applicant's ability to deliver a fully functional web application from development to production.

#### Deliverables
- A live URL where the web app is hosted and accessible.
- A Git repository link containing all the source code, with a clear commit history and a README file detailing setup instructions, architecture decisions, and any assumptions made during development.

### Deployment Platforms
For deploying the web application, consider using platforms that offer free hosting for static sites and support Flutter for Web, such as Firebase Hosting, Netlify, or GitHub Pages. Ensure the deployment process is documented, including any necessary configurations for routing and serving the Flutter web app.
