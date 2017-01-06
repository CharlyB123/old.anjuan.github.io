## **SUPPORT (URGENT)**

### [Customer model fails to load 50% of the time... Geometry Instancing for the win?](https://trello.com/c/4WjQ9tYv/83-customer-model-fails-to-load-50-of-the-time-geometry-instancing-for-the-win)
* We're still waiting on getting the `communicator` branch set up to convert from the Assemble format to the HOOPS format. This should be ready in the next couple of days.
* If HOOPS doesn't help, then we may retry changing the Viewer to consume the instanced format.
* Ashlee is working on getting the model from Whiting Turner.


### [Customer model fails to load... aw snap!](https://trello.com/c/pMwcffz2/33-customer-model-fails-to-load-aw-snap)
* We're still waiting on getting the `communicator` branch set up to convert from the Assemble format to the HOOPS format. This should be ready in the next couple of days.
* If HOOPS doesn't help, then we may retry changing the Viewer to consume the instanced format.

## **Retro Action(s)**

### Amount of time needed for an automation run
* Hala deleted log files from *asm-builder* and was able to create 80 GB of free space out of 199 GB (previously free space was at 20 GB). She will next work on *asm-fit*.
* Mike created a list of things he plans to delete on *asm-ci* and *asm-data* and shared it with the team. He will start deleting items this afternoon.
* Mike suggested rebuilding the machines since they run on outdated Hyper V from Rackspace. This will be explored at a later date.
* Charles will ask David about investigating the performance history of the servers.
* The clean up is still expected to finish before the end of this week.
* The plan is still to observe the performance impact of the newly cleaned servers and then do an analysis of five days of test runs to gather data. The team will then assess if buffing the servers needs to be done.
* Items we'll measure:
 * Performance counters (CPU, Memory, Disk I/O) [David]
 * Test duration [Charles]
 * Transiant failures [Charles]

## **PROJECTS**

### PCL Projects Approval (Tech Preview)
* **Status:** <font color="green">**Green**</font>
* **Personnel:** 
 * **Dev:** Scott, Hala
 * **QA:** Dave
 * **Ops:** Mark Ingalls
*  **Current Hours Remaining:**
 * **Dev:** 10
 * **QA:** 10
 * **Ops:** 28 (this is the remaining Automation work)
 * **Total:** 48
* **Notes:**
 * Scott continues to work on features and bug fixes.
 * Scott created security-related cards on the PCL Product Backlog that we reviewed during the Mid-Sprint Grooming session. A PCL user may be able to construct URLs that get around the Project Approval feature, and these cards are to prevent that from being a workaround. The estimate for doing the security work is 26 hours.
 * Dave continues creating bug cards and testing fixes and features as they come to QA Doing. He's moved a few cards to Ready for Product Owner on the PCL Project Approvals Trello board.
 * Mark Ingalls tagged the cards that need automation with a label and added his time to them. These cards will move to the "Done - Needs Automation" lane before being moved to "Done".
 * This project is now green since we have quantified the automation work. 
* **Current Delivery Date:** Early November

### Redundant Central Services (GA)
* **Status:** <font color="green">**Green**</font>
* **Personnel:** 
 * **Dev:** Jon
 * **QA:** TBD
 * **Ops:** Mark Ingalls
* **Current Hours Remaining:**
  * **Dev:** 19
  * **Ops:** 24
  * **Total:** 43
* **Notes:** 
  * Jon has finished all necessary active development to deploy Redundant Central Services (RCS).
  * There are 8 hours of cards in the QA Doing lane that need to be completed prior to deployment.
  * During the R&D Mid-Sprint Grooming meeting, the cards for the deployment were updated. There is an estimated 32 hours of work to deploy RCS.
  * The deployment of RCS still needs to be officially scheduled, and the team will continue to track progress during the daily standups.
  * Doing this before the end of October would be ideal to avoid colliding with a release.
*  **Current Delivery Date:** ~~Early October~~ ~~Mid-October~~ Late October

### Procore (Tech Preview)
* **Status:** <font color="green">**Green**</font>
* **Personnel:** 
  * **Dev:** Jon
  * **QA:** Charles
  * **Ops:** Mark Ingalls
* **Current Hours Remaining:**
  * **DEV:** 0
  *  **QA:** 1
  * **Ops:** 1
  * **Total:** 2
* **Notes:**

  * Jon has finished development on Procore for Fall BIMForum. He will do Automated Publisher work for a couple of days before starting the Procore GA work.
  * Mark will roll Procore out tonight to ProcoreDemo.tryassemble.com. He will take a ZIP file from the `overshare` branch and deploy it.
  * The team groomed the Procore Product Backlog and estimated 48 hours of work.
  * Tim, Will, and John M. will have Thursday-Friday this week to verify that the Procore integration works as needed.
* **Current Delivery Date:** Mid-October

### 2D Sheets (Tech Preview)  
*  **Status:** <font color="green">**Green**</font>
* **Personnel:**  
    * **Dev:** Quentin, TechSoft 
    * **QA:** Johnny Ops: Mark Ingalls
* **Notes:** 
     * Quentin made tweaks to the UI and fixed bus. 
     * Quentin is working on the ID mapping that Guido sent and had an issue. He emailed Guido, and, in response, TechSoft sent an updated executable. This now maps per sheet. He's working on the backend and will do front end later today.
     * Quentin will also add the progress indicator code.
     * Guido is still working on the font issue. There seems to be a corrupt font. They currently show a placeholder image, but they are working on a fallback font to display.
     * Johnny began building out the test rail coverage. 
     * The team met with Tim to review the items on the 2D Sheets Product Backlog that were in scope for AU.
     * David already has a laptop that can be used at Autodesk University.
* **Current Target Delivery Date:** Early November

### HOOPS 3D Viewer (Prototype)
  * **Status:** <font color="#EBD518">**Yellow**</font>
  * **Personnel:** 
   * **Dev:** Steve
   * **QA:** Eduardo
   * **Ops:** David
  * **Notes:** 
   * Steve thinks that he's close to converting to Communicator 3D on publish. He will try importing the instance format and loading into HOOPS.
   * Steve worked with Guido on the camera operators.
   * The ghosting, x-ray, and windows selection are not implemented yet. Steve thinks that windows selection may not be ready in time AU.
   * Steve implemented the progress bar, and it works well.
   * Eduardo is continuing his testing.
  *  **Current Delivery Date:** Early November


## **Risks and Issues**

| Type     | Description                | Mitigation Plan   | Owner |
| ---------|:---------------------------| :-----------------| :----:
| Risk     | Lack of Product Management Role | Cabinet to assist in Product Management tasks           | Hala
| Risk     | Team Morale                | Continued monitoring         | Hala
