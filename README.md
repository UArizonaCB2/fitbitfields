# Fitbit Fields

[https://support.mydatahelps.org/hc/en-us/articles/360049163273-Fitbit-Profiles-Data-Export-Format](https://support.mydatahelps.org/hc/en-us/articles/360049163273-Fitbit-Profiles-Data-Export-Format)

Daily Data Summary

| Table | Field | Description |
| --- | --- | --- |
| fitbitdailydata | HeartRateIntradayCount | The number of intraday heart rate samples collected during the time period. |
| fitbitdailydata | HeartRateIntradayMinuteCount | The number of minutes throughout the day that have an intraday heart rate sample. This value approximates the time the device was worn. A value of 1439 or greater indicates a full day. |
| fitbitdailydata | HeartRateZoneCardioCaloriesOut
HeartRateZoneCardioMax
HeartRateZoneCardioMin
HeartRateZoneCardioMinutes | Fat burn, cardio, and peak are the three heart rate zones. They are personalized to each participant based on age and cardiovascular fitness level. To engage the cardio zone, participants may be running or biking.
Number of calories burned while in cardio zone.
A minimum and maximum heart rate that together define the cardio zone. For example: HeartRateZoneCardioMin of 94 and HeartRateZoneCardioMax of 132 mean that the cardio zone includes heart rates from 94-132.
Number of minutes spent in cardio zone. |
| fitbitdailydata | HeartRateZoneFatBurnCaloriesOut
HeartRateZoneFatBurnMax
HeartRateZoneFatBurnMin
HeartRateZoneFatBurnMinutes | Fat burn, cardio, and peak are the three heart rate zones. They are personalized to each participant based on age and cardiovascular fitness level. To engage the fat burn zone, participants may be lifting weights, taking a yoga class, or going on a fast walk.
Number of calories burned while in fat burn zone.
A minimum and maximum heart rate that together define the fat burn zone. For example: HeartRateZoneFatBurnMin of 94 and HeartRateZoneFatBurnMax of 132 mean that the fat burn zone includes heart rates from 94-132.
Number of minutes spent in fat burn zone. |
| fitbitdailydata | HeartRateZoneOutOfRangeCaloriesOut
HeartRateZoneOutOfRangeMax
HeartRateZoneOutOfRangeMin
HeartRateZoneOutOfRangeMinutes | Heart rate zones go in terms of intensity from peak to cardio to fat burn. Out of range zone means a participant fell below the threshold of fat burn zone. Zones are personalized to each participant based on age and cardiovascular fitness level.
Number of calories burned while out of range.
A minimum and maximum heart rate that together define the out of range zone. For example: HeartRateZoneOutofRangeMin of 94 and HeartRateZoneOutofRangeMax of 132 mean that the out of range zone includes heart rates from 94-132.
Number of minutes spent out of range. |
| fitbitdailydata | HeartRateZonePeakCaloriesOut
HeartRateZonePeakMin
HeartRateZonePeakMax
HeartRateZonePeakMinutes | Fat burn, cardio, and peak are the three heart rate zones. They are personalized to each participant based on age and cardiovascular fitness level. To engage the peak zone, participants may be sprinting or biking up a steep hill at a fast pace.
Number of calories burned while in peak zone.
A minimum and maximum heart rate that together define the peak zone. For example: HeartRateZonePeakMin of 94 and HeartRateZonePeakMax of 132 mean that the peak zone includes heart rates from 94-132.
Number of minutes spent in peak zone. |
| fitbitdailydata | HrvDailyRmssd | The Root Mean Square of Successive Differences (RMSSD) between heart beats. It measures short-term variability in the user’s daily heart rate in milliseconds (ms). |
| fitbitdailydata | HrvDeepRmssd | The Root Mean Square of Successive Differences (RMSSD) between heart beats. It measures short-term variability in the user’s heart rate while in deep sleep, in milliseconds (ms). |
| fitbitdailydata | RestingHeartRate | Average resting heart rate. |
| fitbitrestingheartrates | RestingHeartRate | The average resting heart rate for the day. |
| fitbitactivitylogs | AverageHeartRate | The user's average heart rate during the activity. |
| fitbitactivitylogs | HeartRateZoneCardioMax
HeartRateZoneCardioMin
HeartRateZoneCardioMinutes
HeartRateZoneFatBurnMax
HeartRateZoneFatBurnMin
HeartRateZoneFatBurnMinutes
HeartRateZoneOutOfRangeMax
HeartRateZoneOutOfRangeMin
HeartRateZoneOutOfRangeMinutes
HeartRateZonePeakMax
HeartRateZonePeakMin
HeartRateZonePeakMinutes | For an activity, Fitbit tracks various heart rate "zones", like "Fat Burn" or "Cardio". For each zone, it reports:
• The minimum and maximum heart rates that define the zone. For example: the "Fat Burn" zone might be between 93 and 130.
• The number of minutes the user spent in that zone during the activity. |

Activity

| Table | Field | Description |
| --- | --- | --- |
| fitbitdailydata | ActivityCalories | Calories burned from periods above sedentary level, from the Activity Time Series. |
| fitbitdailydata | BreathingRate | Average number of breaths taken per minute from the previous night's sleep. |
| fitbitdailydata | CardioScore | Score that shows how fit participants are for their age and sex. Estimate of VO2 max. Score is based on resting heart rate and user profile. The value can be either a single number (45) or a range (44-48). |
| fitbitdailydata | Distance | Distance traveled |
| fitbitdailydata | Elevation | Elevation traveled |
| fitbitdailydata | Floors | Floors climbed |
| fitbitdailydata | MinutesFairlyActive
MinutesLightlyActive
MinutesSedentary
MinutesVeryActive | Minutes spent at different activity levels |
| fitbitdailydata | TrackerDistance | Distance traveled; only includes tracker sources, not manually-entered data. |
| fitbitdailydata | TrackerElevation | Elevation traveled; only includes tracker sources, not manually-entered data. |
| fitbitdailydata | TrackerFloors | Floors climbed; only includes tracker sources, not manually-entered data. |
| fitbitdailydata | TrackerMinutesFairlyActive
TrackerMinutesLightlyActive
TrackerMinutesSedentary
TrackerMinutesVeryActive | Minutes spent at the different activity levels; only includes tracker sources, not manually-entered data. |
| fitbitdailydata | TrackerSteps | Steps taken; only includes tracker sources, not manually-entered data. |
| fitbitactivitylogs | ActiveDuration | The duration of the activity, in milliseconds. |
| fitbitactivitylogs | ActivityName | The name of the activity (e.g., Walk or Sport). |
| fitbitactivitylogs | ActivityTypeId | The internal Fitbit identifier for the activity (e.g., walking is 90013). |
| fitbitactivitylogs | FairlyMinutes | The number of minutes the user was "fairly active" during the activity. |
| fitbitactivitylogs | LightlyMinutes | The number of minutes the user was "lightly active" during the activity. |
| fitbitactivitylogs | ManualValueSpecifiedDistance | Manually-entered value for distance. |
| fitbitactivitylogs | ManualValueSpecifiedSteps | Manually-entered value for steps. |
| fitbitactivitylogs | OriginalDuration | The activity duration, excluding any manual user modifications. |
| fitbitactivitylogs | OriginalStartTime | The activity start time, excluding any manual user modifications. |
| fitbitactivitylogs | SedentaryMinutes | The number of minutes the user was "sedentary" during the activity. |
| fitbitactivitylogs | Steps | The number of steps during the activity. |
| fitbitactivitylogs | VeryMinutes | The number of minutes the user was "very active" during the activity. |

Sleep

| Table | Field | Description |
| --- | --- | --- |
| fitbitsleeplogdetails | type | Can be either ShortSleepLevel or SleepLevel. ShortSleepLevel ≤ 3 hours of sleep. And SleepLevel indicates sleep more than 3 hours. Sleep stages are only available when the user has slept for more than 3 hours.  |
| fitbitsleeplogdetails | startdate
enddate | Indicates when the user went to sleep and woke up. |
| fitbitsleeplogs  | startdate
enddate | Indicates when the user went to sleep and woke up. Each user can have multiple entries for the same day if they have multiple sleep sessions. |
|  | duration | The amount of time the user slept in milliseconds |
|  | efficiency | A score assigned by Fitbit that indicates how well the user slept. From [0-100] |
|  | infocode | Unknown |
|  | minutesafterwakeup | The total number of minutes after the user wokeup. |
|  | minutesasleep | Minutes user was asleep |
|  | minutesawake | Minutes user was awake |
|  | minutesofallsleep | The total number of minutes before the user falls asleep. This value is generally 0 for autosleep created sleep logs. |
|  | timeinbed | Total number of minutes the user was in bed. |
|  | type | classic | stages
If stages then it has sleep phase info - rem, deep, light, wake. Has to be more than 3hrs of sleep session.
If classic then only has restless, sleep, awake |
|  | sleeplevelawake
sleeplevelasleep
sleepleveldeep
sleeplevelrem
sleeplevelrestless
sleeplevelwake | Timestamp the user started in sleep level. |
|  | isMainSleep | Not Supported in MDH |

Heart 

Note - HRV metrics will be found inside `fitbitdailydata`

<aside>
👩🏽‍💻 There is usually one resting HR value per day given that the user has slept atleast more than 3 hours on that. And also wore the device at night during sleep.

</aside>

| Table | Field | Description |
| --- | --- | --- |
| fitbitrestingheartrates | date | Date of the recording. |
|  | restingheartrate | Resting HR for that day in BPM |
