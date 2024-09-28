# Scoober

Scoober is a ride-sharing application built using Expo and React Native. The app allows users to request rides, track their trips, and manage their bookings through a simple and intuitive interface.

## 🛠️ Features

- **Ride Booking**: Request a ride with ease.
- **Trip Tracking**: View real-time trip updates.
- **Responsive Design**: Optimized for mobile devices.
- **User Management**: Secure sign-in and profile handling.

## 📸 Screenshots
Screenshots coming soon!

## 🛠️ Technologies Used

- **Expo**: Framework for building React Native apps.
- **TypeScript**: Typed JavaScript for scalability.
- **React Native**: Mobile app framework.
- **Tailwind CSS**: For styling components.
- **PostgreSQL**: Database used for storing user and ride-related data.
- **Stripe**: Integrated for handling payment processing.

## 📂 Project Structure
<details><pre><code>app
  (api)
    (stripe)
      create-api.ts
      pay-api.ts
    ride
      [id]+api.ts
      create-api.ts
    driver-api.ts
    user-api.ts
  (auth)
    _layout.tsx
    sign-in.tsx
    sign-up.tsx
    welcome.tsx
  (root)
    (tabs)
      _layout.tsx
      chat.tsx
      home.tsx
      profile.tsx
      rides.tsx
    _layout.tsx
    book-ride.tsx
    confirm-ride.tsx
    find-ride.tsx
  _layout.tsx
  +html.tsx
  +not-found.tsx
assets
  fonts
  icons
  images
components
  CustomButton.tsx
  DriverCard.tsx
  GoogleTextInput.tsx
  InputField.tsx
  Map.tsx
  OAuth.tsx
  Payment.tsx
  RideCard.tsx
  RideLayout.tsx
constants
  index.ts
lib
  auth.ts
  fetch.ts
  map.ts
  utils.ts
store
  index.ts
types
  image.d.ts
  type.d.ts
</code></pre></details>

- **app/(api)**: Contains API routes for Stripe payments and ride-related functionalities (booking, driver, user).
- **app/(auth)**: Manages user authentication, including sign-in, sign-up, and welcome pages.
- **app/(root)**: Handles the core pages like home, profile, chat, and rides, with additional tabs and booking pages.
- **assets**: Stores fonts, icons, and images.
- **components**: Reusable UI components such as `CustomButton`, `DriverCard`, and `RideLayout`.
- **constants**: Stores constant values and configurations.
- **lib**: Utility functions like authentication, fetching data, and map handling.
- **store**: Centralized state management.
- **types**: TypeScript definition files.
