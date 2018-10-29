# ZikFreak
Manage bookings of studio for musician or teacher

This Website was created out of the need to manage bookings for studio available to students, musicians or teacher.

Anonymous website visitors get an overview of studio and occupation in a
specific period of time, etc ..

Logged in users additionally can book timeslots of studio according to the defined
maximum of bookings per hour and location.

## Requirements
* Nothing

//We have not tested it with higher versions but the codebase should be sufficient.//

## Usage
Admin can also manage the reservation

### Create a reservation
Go to *Your profil->add reservation->confirm*.
And wait for **validation of admin**.

#### Configuration
After switching back to the Tab *reservation page* you have several options to specify:

* **Maximum bookings per hour and user**
 Defines how many bookings a user can place per hour
* **Count of weeks available for booking in advance**
 Defines how many weeks users will be able to book in advance.
 Current week plus what you define here. Default is 2 weeks if nothing specified.
* **Count of weeks available for looking back**
 Defines how many weeks one can go back to see the occupation.
 Defaults to 1 week if nothing is specified.
* **Administrative accounts**
 Defines the frontend user accounts that are treated as admins. they are not limited by
 all prior settings.

### define Closing Days
Closing days are useful for bank holidays for example.

You have to provide at least a *Closing day name* and a *Date*. The days are shown
as non-bookable in week overview and its not possible to create bookings from the frontend
on these days. However there is no validation on bookings one creates from backend but they are not
shown in frontend either.

### define Opening Hours
By default all hours of all days a week are bookable. With opening hours one can define
the opening hours of a day.

Select the day of week you want to specify he opening hours for and then select the hours
of duty.

If you select no hours at all the day is closed for bookings entirely. Like this one
 can create weekly closed days in exemple sunday.
