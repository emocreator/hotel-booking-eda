
# Hotel Booking EDA Analysis

This project involves exploratory data analysis (EDA) of a hotel booking dataset using Python. The dataset contains information about hotel bookings, and the analysis aims to derive insights from the data.

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/hotel-booking-eda.git
   ```

2. Install the required Python packages using `pip`:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the `hotel_booking_eda.ipynb` notebook using Jupyter Notebook or any other compatible environment.

4. Execute the code cells in the notebook to perform the analysis and visualize the results.

## Project Structure

The project contains the following files:

- `hotel_booking_eda.ipynb`: Jupyter Notebook containing the Python code for EDA analysis.
- `hotel_bookings.csv`: Dataset file containing hotel booking information.

## Analysis Tasks

### 1. How many bookings were cancelled?

To determine the total number of bookings that were cancelled, we count the rows where `is_canceled` is equal to 1.

### 2. Which month has the highest number of cancellations?

We group the data by the `arrival_date_month` and count the cancellations for each month to find the month with the highest number of cancellations.

## Results

The analysis provides answers to the two questions mentioned above, helping to gain insights into the dataset.

## Libraries Used

- pandas: Data manipulation and analysis.
- numpy: Numerical operations.
- matplotlib and seaborn: Data visualization.
- plotly: Interactive data visualization.
- folium: Creating interactive maps.
- sort-dataframeby-monthorweek: Sorting data by month.
- sorted-months-weekdays: Sorting months and weekdays.

## Author

- [Rabbit](https://github.com/emocreator)

## Acknowledgments

This project is based on the Hotel Booking dataset and is meant for educational purposes. The dataset source and more information can be found [here](https://github.com/emocreator/hotel-booking-eda/blob/main/Hotel_booking.ipynb).
