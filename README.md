# RealTime-Location-Fetching.
This class is used to start and stop picking up the location from the device at real time. 

You have to start fetching the Location by:
 
 LocationUtil locationUtil = new LocationUtil(activity, this);
 locationUtil.startLocationUpdates();
 
 Then you can stop when not required by:
 locationUtil.stopLocationUpdates();
 
 But remember to ask for the location permission dynamically at first then start the location listener. 
 The locationListener is called inside the the LocationUtilClass, you have to implement it in your fragment and activity wherever you want  to access the location. 
 
