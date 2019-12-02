# media_cleaner
This script will go through all watched videos and delete any for a specific user that is older then a defined cutt off.

# Config file 
The first time you run the script it will attempt to create the config file for you by asking a few questions

filename: media_cleaner_config.py

* server_url='http://server:8096' - Server url for Emby server
* admin_username='UserName'  - Username for Admin user with access to delete files
* access_token='ZZZZZZZZZZZZZ' - Token used to verify admin user actions
* user_key='YYYYYYYYYYYYY'  - UserID of the user that script check watched status for
* DEBUG=0 - Display extra info to screen for debuging
* not_played_age_movie=100  - How many days to keep a watched movie before deleting
* not_played_age_episode=100  - How many days to keep a watched episode before deleting
* not_played_age_video=100  - How many days to keep a watched video before deleting
* not_played_age_trailer=100  - How many days to keep a watched trailer before deleting
* remove_files=0  - 0 means trial run, no delete.  1 means remove files
* ignore_favorites_movie=1 - Ignore movies that have been marked as favorite
* ignore_favorites_episode=1 - Ignore episodes that have been marked as favorite
* ignore_favorites_video=1 - Ignore videos that have been marked as favorite
* ignore_favorites_trailer=1 - Ignore trailers that have been marked as favorite


# Usage
Make media_cleaner.py executable and run ./media_cleaner.py.  If no conifg file is found it will prompt you to create one.  Once done you can run the script again to view files that will be deleted

# Requirements
* python3

# Donation
If you find this useful and you would like to support please the use option below.
