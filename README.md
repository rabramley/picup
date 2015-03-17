# Picup - Picasa Uploader

## Intro

This is a little utility to upload all images in a directory into Picasa (Google Photos).  It is intended to be run as a cron job to gradually upload the contents of a directory and then upload any new files as they are added.

## How it Works

Well, it doesn't yet.  But the idea is that you will run it from cron with parameters like this:

    picup.py -u username -p password --maxupload number_of_files directory

## Pre-requisites

This should probably install itself and all its dependencies, but for now you have to install them manually like this:

- gdata-python-client, downloaded and installed

    pip install gdata

## Google Account Settings

**WARNING**: This application requires you to allow less secure applications to access your Google+ account.  Therefore make sure you have a good, strong password.

To give access to less secure applications:

1. Got to [Google Account Settings](https://myaccount.google.com/)
2. Click on the setting `Access for less secure apps`
3. Change the setting to `Allowed`.

Obviously I'll change the application to not require this as soon as I work out how.
