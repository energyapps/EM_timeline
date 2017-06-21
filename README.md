## The Office of Environmental Management (EM) Timeline

This is a timeline of the Department of Energy's Office of Environmental Management

This is a timeline based on [Knight Lab's Timeline.js feature](https://github.com/NUKnightLab/TimelineJS). NOTE that this library is no longer actively updated. We may consider updating these to the [actively updated library, v3](https://github.com/NUKnightLab/TimelineJS3). 

### Important Directories

* **index.html** is the index and references several dependencies (listed below), links to css/js, etc. Additionally, there is custom code added by EM developers that provides for the filtering of the timeline. 
* **Images/** is the folder that contains all of the images and PDFs. Please be aware that Images is capitalized. 
* **Timeline/data.json** is where the data is held for each timeline entry. 

### Timeline Update Process (for EM timeline)

1. Have EM timeline repository cloned and updated locally.
2. Receive download of full EM timeline folder from EM staff.
3. Unzip
4. From the newly received folder, copy the `Images/` folder and the `Timeline/data.json` file and replace those things in the local repository. 
5. Add, commit, and push these updates to the remote github repository. 
6. On the web, navigate to the added items and ensure that they're appearing as intended, troubleshoot as needed. 
7. Let the EM folks know that it is updated. 

### Known Issues and Concerns

* Occassionally they will include PDFs that are much too large. It may be adventageous to have a max file size.
* Some of the css styles appear to be working poorly, causing some of the icons to not show up on the lefthand side of the timeline ("return to title","expand timeline", "contract timeline")


### All non-DOEdrupal Timelines

* EM timeline (_[github](https://github.com/energyapps/EM_timeline)_,_[energy.gov link](https://energy.gov/em/em-historical-timeline))
* Paducah Site Historical Timeline (_[github](https://github.com/energyapps/PPPO_timeline)_,_[energy.gov link](https://energy.gov/pppo/paducah-site-historical-timeline))
* History of the Lightbulb  (_github coming soon_,_[energy.gov link](https://energy.gov/articles/history-light-bulb))