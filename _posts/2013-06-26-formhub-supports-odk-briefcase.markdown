# Formhub supports ODK Briefcase
ODK Briefcase is used to gather and export data from an ODK Aggregate server e.g [formhub.org](https://formhub.org) or from ODK Collect when you are offline.
posts/2011-12-09-staying-even-how-to-use-formhub-and-odk-collect-to-track-your-travel-expenses.markdown
1.  Export forms with submissions from formhub (ODK Aggregate) - PULL 

*   Make bulk submission to formhub (ODK Aggregate) - PUSH

*  CSV exports of submission data

*  Pull forms and submissions collected by ODK Collect from a mobile phone

*  Supports encrypted forms: it can make encrypted submissions to formhub as well
    as decrypt encrypted submissions from formhub when exporting the data to csv.
     
     
If you have encrypted forms and making submissions to formhub, you’ll realise 
that you do not have the ability to browse the submitted data on the site.
Formhub stores the submissions in encrypted form, using your private key and 
ODK Briefcase you can be able to pull your data from formhub and export it 
to a csv  file.

## How to setup ODK Briefcase to work with formhub

1. Install Java 6 or higher on your computer.

*  Download ODK briefcase from [http://code.google.com/p/opendatakit/](http://code.google.com/p/opendatakit/)

*  Specify the location of the ODK storage area on your computer this will 
   create the ODK Briefcase Storage folder which will hold all the blank
   forms and finalized forms(submissions).
   
*  Open ODK Briefcase.

*  On the tab "Pull," click on the bar to the right of "Pull data from:" 
   (top left) and choose "Aggregate 1.0".
   
*   Click on "Connect" to pull data from aggregate.


![Pull data](/http://www.flickr.com/photos/97973954@N06/9140785103/in/set-72157634333942883)
















