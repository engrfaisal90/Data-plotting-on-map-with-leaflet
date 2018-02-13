# Plotting and clustering coordinates on google map
 The data from one of the kaggle datset is plotted and clustered. It clusters with zoom and  
 The datset was downloaded from https://www.kaggle.com/mchirico/montcoalert.
 
 As the data is in .CSV file so first we converted it into Json data format and saved it as markers.js.
 The markers.js data format is below, where each block of {} represents a row of .CSV file.
  
  var markers =[
 {"e": "1", "addr": "REINDEER CT & DEAD END", "zip": "19525", "title": "EMS: BACK PAINS/INJURY", "timeStamp": "2015-12-10 17:40:00", "twp": "NEW HANOVER", "lat": "40.2978759", "lng": "-75.5812935", "desc": "REINDEER CT & DEAD END;  NEW HANOVER; Station 332; 2015-12-10 @ 17:10:52;"},
 {"e": "1", "addr": "BRIAR PATH & WHITEMARSH LN", "zip": "19446", "title": "EMS: DIABETIC EMERGENCY", "timeStamp": "2015-12-10 17:40:00", "twp": "HATFIELD TOWNSHIP", "lat": "40.2580614", "lng": "-75.2646799", "desc": "BRIAR PATH & WHITEMARSH LN;  HATFIELD TOWNSHIP; Station 345; 2015-12-10 @ 17:29:21;"}]
