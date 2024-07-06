# College Group Project: StayWave Website

This project is a MERN Stack (MongoDB, Express.js, React, Node.js) application inspired by the Airbnb website. It was developed as a college group project. 

## Features

### Navbar
- **Logo**: The navbar contains the project logo.
- **Filters**: Users can filter by selecting an Indian region, date, and the number of guests.
- **Authentication**: Options for logging in and signing up are available for non-authenticated users and authenticate users can logout, and see their whislist.

### Sub Navbar
- **Category Slider**: A slider for categories is included.
- **Filter Button**: Opens a modal with options for price, number of rooms, beds and bathrooms, and amenities. Stays are shown according to these filters.

### Stays Display
- **Lazy Loading**: Initially, the first 20 stays are loaded, and then another 20 are loaded upon scrolling.
- **Stay Cards**: Each card includes:
  - Image slider
  - Area name
  - Category
  - Hosted by whom
  - Price
  - Reviews
  - Wishlist button (only for logged-in users)

### Stay Description Page
- **Navbar**: The navbar on this page is same as home page but, does not include the filter option or sub-category.
- **Stay Information**: Displays the stay name (like hotel name, villa name, etc.), reviews, and an image grid showing 5 images initially.
- **Image Modal**: To view all images, a modal can be opened.
- **Host Information**: Shows the host's name, number of guests, bedrooms, beds, and baths available.
- **Description**: Detailed description about the stay.
- **Reservation Card**: On the right side, there's a card to select date and number of guests and reserve the stay (only for logged-in users).

## Screenshots
Below is a screenshot of the website's user interface:
![image](https://github.com/VirtiShah247/StayWave-Website/assets/102175129/0bfcbb19-9c5c-4825-917f-1e37956cb75e)
![image](https://github.com/VirtiShah247/StayWave-Website/assets/102175129/9ecf7304-b3f7-468b-a6ef-68c72e9d8a1e)
![image](https://github.com/VirtiShah247/StayWave-Website/assets/102175129/404143d7-d10c-43c0-93f0-95777205ad2d)

![image](https://github.com/VirtiShah247/StayWave-Website/assets/102175129/bb6575b8-a9cb-4e87-b084-85db22d75ea5)
![image](https://github.com/VirtiShah247/StayWave-Website/assets/102175129/ab7148a8-8ffc-469e-a3d2-f094101f7c66)
![image](https://github.com/VirtiShah247/StayWave-Website/assets/102175129/25edb063-2196-412c-84a2-4d6d43179437)



## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2. Install dependencies for both server and client:
    ```bash
    cd your-repo-name
    npm install
    cd client
    npm install
    ```
3. Start the development server:
    ```bash
    cd ..
    npm run dev
    ```
