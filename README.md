# UdyanSathi
:rocket: [Link to website][https://udyaansaathi.onrender.com/]

We've developed a web-based Environment Monitoring System that offers real-time Air Quality Index (AQI), Water Quality Index (WQI), and weather data for users to easily access. Here's how it works:

- Our approach involves creating a web-based solution for analyzing air and water quality data alongside weather predictions.
- We've implemented an SOS alert system in line with the GRAP (Graded Response Action Plan) system.
- Data is visualized through various graphical representations such as heat maps, pictorial displays, bar graphs, and line graphs for easy interpretation.
- Air quality forecasting is conducted using advanced AI/ML techniques with a remarkable accuracy rate of 98.984%.
- Our data strategy involves multiple layers, leveraging historical data to provide comprehensive insights into air and water quality.

![WhatsApp Image 2024-01-08 at 9 19 17 PM](https://github.com/NikhilSai5/SIH-UdyanSathi/assets/138366034/f3eee131-9fa7-45b2-ba8c-919565c0fa3c)
![WhatsApp Image 2024-01-08 at 9 19 56 PM](https://github.com/NikhilSai5/SIH-UdyanSathi/assets/138366034/5f427453-adbd-4138-88c1-e84a52bf1576)
![WhatsApp Image 2024-01-08 at 9 19 44 PM](https://github.com/NikhilSai5/SIH-UdyanSathi/assets/138366034/a52254cf-8054-4084-aa1c-0db46ad72907)



first load the the data in *Database* folder in the **MySQL**

to start the website in terminal cd to **UdyanSaathiAPI** then type the following command : -
- ``python manage.py makemigrations``
- ``python manage.py migrate``
- ``python manage.py runserver``

then cd to **UdyanSathi** then type the following command : -
- ``npm install``
- ``npm run dev``



# Environment Monitoring System Using AI/ML

:rocket: [Link to website][https://udyaansaathi.onrender.com/]

We have developed a web-based **Environment Monitoring System** that provides real-time **Air Quality Index (AQI)**, **Water Quality Index (WQI)**, and **weather data**, making it easy for users to access and interpret crucial environmental information.

## Key Features

### Real-Time Monitoring
- Offers real-time data for AQI, WQI, and weather conditions.

### Advanced Data Analysis
- Uses **AI/ML techniques** for air quality forecasting with an impressive accuracy rate of **98.984%**.
- Leverages historical data for comprehensive insights into air and water quality.

### Visualization
- Presents data through intuitive visualizations, including:
  - Heat maps
  - Pictorial displays
  - Bar graphs
  - Line graphs

### SOS Alert System
- Implements an SOS alert system based on the **Graded Response Action Plan (GRAP)** to ensure timely notifications during critical conditions.

## System Workflow

1. Load the data from the **Database** folder into **MySQL**.
2. Start the backend and frontend services:

### Backend Setup
1. Navigate to the **UdyanSaathiAPI** directory:
   ```bash
   cd UdyanSaathiAPI
   ```
2. Run the following commands:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver
   ```

### Frontend Setup
1. Navigate to the **UdyanSathi** directory:
   ```bash
   cd UdyanSathi
   ```
2. Install dependencies and start the development server:
   ```bash
   npm install
   npm run dev
   ```

## Visual Representation

### Screenshots

![AQI Dashboard](https://github.com/NikhilSai5/SIH-UdyanSathi/assets/138366034/f3eee131-9fa7-45b2-ba8c-919565c0fa3c)
![WQI Visualization](https://github.com/NikhilSai5/SIH-UdyanSathi/assets/138366034/5f427453-adbd-4138-88c1-e84a52bf1576)
![Weather Overview](https://github.com/NikhilSai5/SIH-UdyanSathi/assets/138366034/a52254cf-8054-4084-aa1c-0db46ad72907)

## Contributions
We welcome contributions to enhance the system further. Feel free to open issues or submit pull requests.

---

**Note:** Ensure that the required Python and Node.js versions are installed before proceeding with the setup.

