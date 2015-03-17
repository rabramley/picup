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

