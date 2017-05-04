
===============Following Documents Contains Instructions of Client GUI===============

1. "Message" Tab: Message tab contains text boxes displaying sent HTTP request and received HTTP response from server.
   1) "HttpMessage Request" TextBox: textbox locating at upper left, displaying all sent out HTTP request from user
   2) "HttpMessage Response" TextBox: textbox locating at upper right, displaying all received HTTP response from server
   3) "Clear Message List" Button: clicking this button will clear all messages of listboxes
   4) "Shutdown Client" Button: clicking this button will shut down the corresponding client

2. "Local File" Tab: Local File tab has functionalities to view local repository, files and choose files to upload
   1) "Select Directory" Button: clicking this button will open a window showing current directory contents
                                 selecting on a directory will display folders and source files in following list box
   2) ".h" and ".cpp" CheckBoxes: by checking these boxes, user can choose source file pattern to display in list box
                                  by default, both checkbuttons are checked
   3) "Upload Selected Files" Button: clicking this button will upload thye files selected in above listbox
                                      publishing will automatically begin once after each uploading operations
   4) "Show Selected Items" Button: clicking this button will only display selected items in listbox

3. "Repository" Tab: Repository tab provides users access to Repository contents, display webpages and delete Repository contents
   1) "Browse Repository" Button: clicking this button will display categories under Repository in left listbox
   2) "View Folder Contents" Button: after selecting one category of left listbox, user can click this button to view files under selected category
                                     in right listbox
   3) "Display Selected Files" Button: clicking this button will display selected files by browser
                                       source files can also be selected to display and will be displyed in corresponding HTML format
   4) "Delete Selected File" Button: clicking this button will delete selected file from Repository
                                     after deletion, please click "Browse Repository" button again for updated category contents
   5) "Lazy Download" and "IIS" RadioButton: choose one method out of two to display selected webpage
                                             by default, "Lazy Download" is checked