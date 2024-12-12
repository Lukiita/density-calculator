# Bamboo Density Calculator

This is a simple web-based calculator used to calculate the density of raw bamboo to measure the buoyancy force when submerged in water. This calculation is particularly useful for determining the suitability of bamboo for making oboe reeds.

## Features

- Calculates the bamboo density based on measurements before and after being submerged in water.
- Classifies the bamboo based on its density into categories ranging from "Too soft" to "Harder and harder, direct to the trash."

## How it Works

1. **Enter the initial measurement**: Input the mass of the bamboo before submerging it in water.
2. **Enter the submerged measurement**: Input the volume of the bamboo when submerged.
3. **Result**: The density is calculated using the formula:
   \[
   \text{Density} = \frac{\text{Mass}}{\text{Mass + Submerged Volume}}
   \]
4. **Classification**: Based on the density, the bamboo is classified into one of the following categories:
   - **Under 50**: Direct to the trash
   - **From 51 to 54**: Can be used maybe for beginners (too soft)
   - **From 55 to 62**: Flexible
   - **From 63 to 69**: Resistant
   - **From 70 to 75**: Hard
   - **More than 75**: Harder and harder, direct to the trash

## Usage

1. Open the webpage in your browser.
2. Enter the bamboo's measurements before and after submerging in the input fields.
3. The density will be calculated and classified based on the entered values.

## Technology Stack

- HTML
- CSS (with media queries for responsiveness)
- JavaScript

## Responsiveness

The page is responsive and adjusts the layout for different screen sizes, providing a good user experience across various devices.

## License

This project is licensed under the MIT License.
