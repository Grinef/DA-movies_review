Project Overview
The goal of this project is to analyze the Russian film distribution market and identify current trends, with a specific focus on films that received state support. 
The project is commissioned by the Ministry of Culture of the Russian Federation. 
The analysis will be performed using data published on the open data portal of the Ministry of Culture, which includes information on film distribution certificates, box office revenues, and state support for films, as well as data from the KinoPoisk website.

Data Description
mkrf_movies Table
Contains information from the registry of film distribution certificates. A film may have several distribution certificates.

title - Film title
puNumber - Distribution certificate number
show_start_date - Film premiere date
type - Film type
film_studio - Production studio
production_country - Production country
director - Director
producer - Producer
age_restriction - Age category
refundable_support - Amount of refundable state support
nonrefundable_support - Amount of non-refundable state support
financing_source - Source of state funding
budget - Total film budget
ratings - Film rating on KinoPoisk
genres - Film genre
Note: The budget column includes the total amount of state support. Data in this column is provided only for films that received state support.

mkrf_shows Table
Contains information about film screenings in Russian cinemas.

puNumber - Distribution certificate number
box_office - Box office revenue in rubles