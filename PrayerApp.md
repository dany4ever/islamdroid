# Prayer Application Summary #

This project objective is to develop a prayer application that can be used - but not limited - to:

  * Generate the prayer times according to the geographical x,y,z.
  * Generate the prayer times according to the city/location database.
  * Automatically manage the prayer times within the calendar and add/remove the prayer appointments.
  * Alert the user of the prayer time with a designated voice ( e.g. Azan voice ).
  * Mute the mobile during the prayer time.
  * Calculate the direction of the qibla.
  * Map the closest mosque within a certain range (20 miles for example).

# Prayer Application Backlog / Wish list #

_Add here a a functional/non-functional feature that the Prayer Application needs to have:_
_Note: There is no specific format - feel free to add whatever you think is related_

## _1. Prayer Times_ ##
  * 1.1 The application shall be able to calculate 5 prayer times a day (Fajr (and Sunrise), Zuhur, Asr, Maghrib, Isha) and Jom'aa prayer (Friday prayer) timings from the inputs of longitude and latitude.
  * 1.2 The application shall be able to give the user prayer times according to the closest city to him/her.

## _2. Alarms and Utilities_ ##
  * 2.1 The Prayer alarms shall be placed in the user calendar automatically for the next period of time whenever the current period is over (week/month/etc..)
  * 2.2 The alarms shall consist of any alarm voice the user chooses, and by default it should be Azan voice.
  * 2.3 The application shall offer muting the device in the prayer time or setting it to a prayer setting that will prevent the mobile from producing loud noises during the prayer time.

## _3. Qibla Direction_ ##
  * 3.1 The application shall be able to give the user the Qibla direction as in the city the user is in or as a response to a GPS location
  * 3.2 The Qibla direction representation shall be in Angles from the real north.

## _4. Mosques_ ##
  * 4.1 The application shall also be able to locate the nearest mosque from a given location(could be from gps).
  * 4.2 The application shall also be able to give the iqama times for each mosque returned.

## _10. Non-Functional_ ##
  * 10.1 [_Internationalization_] The GUI developed shall use strings that are not embedded in the code, where the language of the user identifies the alternative string set like Ar/En/Fr etc.