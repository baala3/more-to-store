# MoreToStore

MoreToStore is an Android e-commerce app I built during my college days as a hands-on learning project. The goal was to dive deep into Android development, work with Firebase, and get comfortable with modern app architecture, while creating something practical and fully functional.

The app lets users to browse products, make purchases, and manage their accounts, all wrapped in a clean, modern UI. It features secure user authentication, real-time data updates through Firebase, and integrated payment processing. Even though it was built mainly for learning, it turned out to be a solid little e-commerce app.

Through the MoreToStore developement, I got to explore a wide range of development concepts, including:

- Firebase for real-time data and user authentication
- Material Design to create a polished, intuitive interface
- Payment gateway integration for handling transactions
- Efficient image loading and optimization
- Applying modern Android architecture patterns
- Focusing on solid UI/UX design principles

## Features

- **User Authentication**: Secure login and registration using Firebase Authentication
- **Product Management**: Browse and view product details
- **Shopping Cart**: Add and manage items in your cart
- **Payment Integration**: Secure payment processing through Paytm
- **User Profile**: Manage personal information and profile picture
- **Firebase Integration**: Real-time data synchronization using Firestore
- **Image Handling**: Efficient image loading and caching with Glide
- **Modern UI**: Material Design components and responsive layouts

## Technical Stack

- **Language**: Java
- **Minimum SDK**: 25
- **Target SDK**: 29
- **Architecture**: MVVM (Model-View-ViewModel)
- **Dependencies**:
  - Firebase (Authentication, Firestore, Storage)
  - AndroidX Libraries
  - Material Design Components
  - Navigation Component
  - Glide (Image Loading)
  - Paytm Payment Gateway
  - Volley (Networking)

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/baala3/more-to-store
   ```

2. Open the project in Android Studio

3. Add your Firebase configuration:

   - Replace the `google-services.json` file in the app directory with your Firebase project configuration

4. Configure Paytm:

   - Update the Paytm merchant credentials in the appropriate configuration files

5. Build and run the application

## Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/          # Source code
│   │   ├── res/           # Resources
│   │   └── AndroidManifest.xml
│   └── test/              # Test files
├── build.gradle           # App-level build configuration
└── google-services.json   # Firebase configuration
```

## Dependencies

The project uses the following major dependencies:

- Firebase Authentication (19.3.2)
- Firebase Firestore (21.5.0)
- Firebase Storage (17.0.0)
- AndroidX Libraries
- Material Design Components
- Paytm Payment Gateway (1.3.1)
- Glide (4.11.0)
- Volley (1.1.1)

### Demo

https://appetize.io/app/q1edkvrn3p9r3g13x8h0qx5904?device=nexus5&scale=75&orientation=portrait&osVersion=8.1
