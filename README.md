# deskCaseExport
Python script to export desk.com cases

This is a simple script that will iterate through all your desk cases and export them to a directory defined by the dir_out variable.

It will export the case details, messages and replies as json.  the filename will be #.json where # is the case id.

It will limit itself to 1 API call a second to avoid API requests being rejected due to rate limiting.  Decrease sleep_time to make calls faster.
