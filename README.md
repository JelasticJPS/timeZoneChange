# Jelastic timeZoneChange Add-on

This repository provides [timeZoneChange](http://jelastic.com/) add-on for Jelastic Platform.


**timeZoneChange** is a TimeZone change tool. add-on to set the needed Time Zone settings.

**Type of nodes this add-on can be applied to**:
- All node types

### What it can be used for?
timeZoneChange is an add-on to set the needed Time Zone settings.
<br />
To set the needed Time Zone settings find it at TZ column and past it to TimeZone Name field.
<br />
Example: America/Fortaleza = UTC-3
<br />
List of tz database time zones: <a href='https://www.google.com/fusiontables/DataSource?docid=1qJ-l1_iImMjq0pQvVquN8j5pSo7HhwAxd5NfwQc'><font color=\"LimeGreen\">Time Zones</a>


### What Jelastic add-on is?

Jelastic add-on represents a package with a kind of a patch, that can be applied to an environment in order to improve and complement its functionality. The full list of the available at a platform add-ons can be seen at the corresponding same-named section of [Jelastic Marketplace](https://docs.jelastic.com/marketplace#add-ons].

### How to install an add-on?
###### For Developers

In case you can’t find the desired package within the list of available ones, copy and save the content of add-on’s manifest as a *.json* file and [import](https://docs.jelastic.com/environment-export-import#import) it to the dashboard. Herewith, you can apply any necessary adjustments to an add-on through this file (if such are required) and install its customized version in the similar way.

###### For Cluster Admins

In order to add the desired add-on to your platform and make it available for users, perform the following:
- copy content of its manifest 
- switch to the [Marketplace](http://ops-docs.jelastic.com/marketplace-46) section of your JCA panel and choose **Add > Add-on** menu option
- paste the copied strings into the appeared frame and **Save** the template
- choose your newly added add-on within the list and click on **Publish** above

Also, you are able to adjust the given add-on template according to your needs and provide its customized version.