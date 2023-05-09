# Hotel Reservations
Para este proyecto se utilizara el siguiente dataset: https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset, el cual contiene datos sobre los distintos tipos de reservas de un hotel y si sus huéspedes asistieron a la misma o la cancelaron.


### Objetivos:
- Analizar cada variable de manera individual para **describir y visualizar** las frecuencias de las mismas.
- Hacer un análisis **explorando** la relación entre la variable 'bookig_status' (el estado de la reserva) y el resto de variables.
- Hacer un **escalado de datos y un balanceo de clases** para normalizar y equilibrar los valores de algunas variables.
- Intentar **predecir** si futuros clientes cancelaran o no su reserva, a partir del entrenamiento de un modelo de Machine Learning.

<br>

**Variables del dataset:**

1. "Booking_ID": unique identifier of each booking <br>
2. "no_of_adults": Number of adults <br>
3. "no_of_children": Number of Children <br>
4. "no_of_weekend_nights": Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel <br>
5. "no_of_week_nights": Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel <br>
6. "type_of_meal_plan": Type of meal plan booked by the customer <br>
7. "required_car_parking_space": Does the customer require a car parking space? (0 - No, 1- Yes) <br>
8. "room_type_reserved": Type of room reserved by the customer. The values are ciphered (encoded) by INN Hotels. <br>
9. "lead_time": Number of days between the date of booking and the arrival date <br>
10. "arrival_year": Year of arrival date <br>
11. "arrival_month": Month of arrival date
12. "arrival_date": Date of the month <br>
13. "market_segment_type": Market segment designation. <br>
14. "repeated_guest": Is the customer a repeated guest? (0 - No, 1- Yes) <br>
15. "no_of_previous_cancellations": Number of previous bookings that were canceled by the customer prior to the current booking <br>
16. "no_of_previous_bookings_not_canceled": Number of previous bookings not canceled by the customer prior to the current booking <br>
17. "avg_price_per_room": Average price per day of the reservation; prices of the rooms are dynamic. (in euros) <br>
18. "no_of_special_requests": Total number of special requests made by the customer (e.g. high floor, view from the room, etc) <br>
19. "booking_status": Flag indicating if the booking was canceled or not. <br>

