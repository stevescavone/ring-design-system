# Feedback

## Butterbar {#butterbar}

![](/assets/molecules/feedback/butterbar/Butterbar.png)

A **Butterbar** is the most common method of delivering feedback to users in the Ring app.

* A butterbar may have **one primary button** OR **a set of primary button and secondary button** in form of text.
* If the function of the primary button doesn't dismiss \(e.g. "GOT IT"\), but rather invoke an action \(e.g. "GO TO SETTINGS"\),  include the **dismiss X button** to the top right inside the butterbar.
* A butterbar may have an **overlay** OR **not**, depending on the priority level: **high** OR **low**.

**Examples**

* Poor Wi-Fi signal alert.
* Low battery level alert.
* System permission disabled alert.

**Zeplin**

* [iOS App](zpl://screen?sid=5a61ac02ba218e7607f9377a&pid=5a395997e8354b6a0e3b9c73) / [iOS Web](/zpl.io/aNBkrYd)
* Android App / Android Web

---

## Snackbar {#snackbar}

![](/assets/molecules/feedback/snackbar/Snackbar.png)

A **Snackbar** is the simplest method of delivering feedback to users in the Ring app.

* A snackbar may have **one primary button** in form of text OR **none**.
* A snackbar will dismiss automatically after **3 seconds**.

**Examples**

* Event deleted.
* Link copied.
* Lights On: 15 minutes.

**Zeplin**

* [iOS App](zpl://screen?sid=5a61ac02b2c4d1db09718deb&pid=5a395997e8354b6a0e3b9c73) / [iOS Web](/zpl.io/bzy5Nl8)
* Android App / Android Web

## Skybar

![](/assets/molecules/feedback/skybar/Skybar.png)

A **Skybar** is a method of delivering push notification alerts in the Ring app.

* A skybar may have **one** OR **two lines**.
* A skybar may can be dismissed by the **dismiss X button** OR **swiping up the skybar**.
* A skybar will dismiss automatically after **30 seconds**.

**Examples**

* There is motion at your Front Door.
* There is someone at your Front Door.

**Zeplin**

* [iOS App](zpl://screen?sid=5a61ac03c1c899a85f798417&pid=5a395997e8354b6a0e3b9c73) / [iOS Web](/zpl.io/bLBkPg6)
* Android App / Android Web

## Dialog

![](/assets/molecules/feedback/dialog/Dialog.png)

A **Dialog** is a method of delivering "yes/no" OR "are you sure?" type of alerts that takes a high priority in the Ring app.

* A dialog always has an overlay behind.
* The color scheme may be **blue** if the action is **positive** OR **red** if the action is **negative** \(e.g. Delete this event? Cancel/Delete\).

**Examples**

* Delete this event? Cancel/Delete.
* Leave and discard the changes? Keep Editing/Leave

**Zeplin**

* [iOS App](zpl://screen?sid=5a6f8021f1faef20afc74abd&pid=5a395997e8354b6a0e3b9c73) / [iOS Web](/zpl.io/a3xY5B8)
* Android App / Android Web



