# msa_website
# Making Changes
To make changes to the website:

* Make a Github account if you don’t have one already
* Create a fork in the most recent version - [https://github.com/ramirocantu/msa_website](https://github.com/Denizhan-Yigitbas/msa_website) 
* Follow these instructions based on the changes needed (you should not need to change anything else about the website!)
    * Board headshots, names, and emails
        * Go to msa_website/images
        * Delete the files of the previous board headshots
            * Be sure to keep track of the name of the files as they are in the code!
        * Add files of the new board headshots labelled “**firstname-headshot.jpg**”
        * Replace the names of the files in the index.html file accordingly
            * There will be a section of code that looks like this and will repeat for each position of the board. Find the position you are looking for and replace the following in this order: file name, full name of person, position name, email address.
                                    
                    <!-- Slide -->
                    <div class="swiper-slide">
                        <div class="card">
                            <img class="card-image" src="images/summer-headshot.jpg" alt="alternative">
                            <div class="card-body">
                                <div class="testimonial-author">Summer Shabana</div>
                                <div class="testimonial-position">Co-President</div>
                                <div class="testimonial-text">ses12@rice.edu</div>
                            </div>
                        </div>        
                    </div> <!-- end of swiper-slide -->
                    <!-- end of slide -->
    * New Student Guide
        * Go to msa_website/pdfs/
        * Delete the file of the previous guide
        * Add file of the new guide labelled “new_student_guide.pdf”
        
# Updating Changes
* Publish requests by uploading the updated server to Rice server
    * Make sure you are connected to a Rice network or the VPN using this - [https://kb.rice.edu/82263](https://kb.rice.edu/82263)
    * If you don’t already have access, email IT Help at [helpdesk@help.rice.edu](mailto:helpdesk@help.rice.edu) and ask to add your NetID to the Active Directory File Security Group to edit the Rice MSA website
    * Follow the steps in this link for your device: [https://kb.rice.edu/search.php?q=mount+storage&cat=0](https://kb.rice.edu/search.php?q=mount+storage&cat=0)
    
        * When connecting to the server for Mac: smb://[storage.rice.edu/Student](http://storage.rice.edu/Student) Activities/Public/www/[msa.rice.edu](http://msa.rice.edu/) (there is a space between Student and Activities)
    
        * When connecting to the server for PC:

            \\[storage.rice.edu](http://storage.rice.edu/)\Student Activities\Public\www\[msa.rice.edu](http://msa.rice.edu/)
            (there is a space between Student and Activities)

    * Check the website and redo process for any additional changes
    * Disconnect from server
* Commit changes using git and push to your fork.
* Send a pull request to merge with master branch.