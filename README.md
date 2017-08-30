# GmailContactGroupLabels
add labels to gmail threads if members of a contacts group participate

## Installation: 

- goto script.google.com
- paste the contents of the GmailContactGroupLabels file into the empty Code.gs window
- replace ContactsGroupName with the contact group of contacts.google.com 
- replace GmailGroupName with the gmail label of your choice (create the label in gmail first!) 
- review the code if you want
- save the file via the menu file+save (in your google drive)
- click "run" and authenticate the script to access gmail and your contacts
- make it autorun if you want by creating a timed-trigger (for the function applyGroupLabels), according to http://www.johneday.com/422/time-based-gmail-filters-with-google-apps-script
- note that the trigger probably can't be more frequent than 15min on gmail's non-business version (you'll get an email reading "service gmail called too often by function applyGroupLabels" or something like that)

Done.
