# CarDekho Used Car Price Prediction

# Problem Statement:
The primary objective of this project is to create a data science solution for predicting used car prices accurately by analyzing a diverse dataset. The dataset includes various features such as car model, number of owners, age, mileage, fuel type, kilometers driven, additional features, and location. The goal is to build a machine learning model that provides users with accurate predictions for the current valuations of used cars.

# Dataset Overview:
The dataset is organized into multiple Excel files, with each file representing a specific city. Each Excel file provides a comprehensive overview of cars, including details, specifications, and available features. Below is a guide on how to handle and analyze these files:

## Excel File Structure

Each Excel file follows a similar structure with columns providing information about different aspects of the cars. Here's an overview of the typical structure:

1. **Car Details Sheet:**
   - Overview details about the cars, including ignition type, fuel type, body type, kilometers driven, transmission type, number of previous owners, ownership details, original equipment manufacturer (OEM), car model, year of manufacture, central variant ID, variant name, price, actual price (if available), price saving information (if available), fixed price details, and trending car information.

2. **Car Overview Sheet:**
   - Provides an overview of the cars, including headings, top details such as registration year, insurance validity, fuel type, etc., and additional bottom data (if available).

3. **Car Feature Sheet:**
   - Contains information about the features of the cars, including headings, top features, and detailed feature information categorized by comfort, interior, exterior, safety, etc.

4. **Car Specs Sheet:**
   - Presents specifications of the cars, including headings, top specifications like mileage, engine, max power, torque, etc., and detailed engine and transmission information, dimensions, capacity, and miscellaneous details.

### Data Extraction:
 1. New Car Detail:
    To extract specific features from the 'new_car_detail' column in the dataset,  create new columns for 'Fuel_Type,' 'Body_Type,' 'Mileage_km,' 'Transmission type,' 'Number owner,' 'OEM,' 'Car model,' 'modelYear,' 'centralVariantId,' 'variantName,' and 'price'
 3. New Car Specs 


