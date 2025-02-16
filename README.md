# Mobile Legends Hero Battle

Welcome to the **Mobile Legends Hero Battle** game! This project allows users to upload a CSV file containing hero data and simulate battles between selected heroes. The battle prediction is based on a weighted scoring system that considers various attributes of the heroes.

## Features

- **Upload CSV File**: Upload a CSV file containing hero data.
- **Hero Selection**: Select heroes from a grid of thumbnails.
- **Battle Prediction**: View battle predictions based on hero attributes.
- **Responsive Design**: Optimized for all device sizes.

## Demo

[Demo Video](https://youtu.be/S4iWG92YWXc)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/mobile-legends-hero-battle.git
    cd mobile-legends-hero-battle
    ```

2. Download the compressed "ALL HEROES" folder from Google Drive.

   ```bash
   https://drive.google.com/file/d/1EFVcgaTamf1HvwsU63qek5e1c7ccGqMD/view?usp=sharing
    ```

4. Extract the contents of the compressed folder into the project directory. Ensure the extracted folder is named "ALL HEROES".

5. Open `index.html` in your web browser.

## Usage

1. **Upload CSV File**: Click on the "Upload CSV File" button and select your CSV file.
2. **Select Heroes**: Choose two heroes from the grid by clicking on their thumbnails.
3. **View Battle Prediction**: The battle prediction will be displayed based on the selected heroes' attributes.

## CSV File Format

The CSV file should have the following columns:

```csv
hero_name,hp,physical_atk,magic_defense,win_rate
Hero1,1000,150,50,60
Hero2,1200,130,70,55
