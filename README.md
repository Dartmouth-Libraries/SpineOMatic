# SpineOMatic

Files in support of the Library's installation of SpineOMatic, "a Windows application that prints spine labels, flag slips or other custom labels for items in Ex Libris' Alma system" developed by Boston College.

## `aboveLabel.txt`

Label prefixes file, as described by the SpineOMatic documentation (p. 42):

> The combination of <library_name> and <library_location> specify where a book is shelved.  Items that are not shelved in the general stacks area may require a Label Prefix to appear above the spine label to indicate the collection name or shelving location.
>
> The Label Prefix table allows SpineOMatic to tell when an item in Alma requires additional text above the call number to identify the item as being shelved in Reference, Media, Oversize or other special location.
>
> A master table may be kept on your server to ensure that all workstations are using the same table.  This is useful when changes need to be made, and all workstations need to obtain an up-to-date copy of the file.  If you choose to do so, you can provide a URL to your own directory (such as "http://myserver.xxx.edu/somefolder") in the “Use system file, URL:” box below.  When SpineOMatic starts, the server is contacted and the "aboveLabel.txt" file in that directory is downloaded to the workstation.  You can also download the file at any time by clicking the “Download” button.
