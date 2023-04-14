---
layout: post
title: My iOS Notification Wish List
description: Reduce digital distractions on iOS with these notification improvements. The wish list includes showing notifications only on the active device, syncing notification status, and providing an archived notification section. Other proposals are snoozing notifications, categorizations for notifications, and using notifications as shortcuts triggers.
summary: Reduce digital distractions on iOS with these notification improvements. The wish list includes showing notifications only on the active device, syncing notification status, and providing an archived notification section. Other proposals are snoozing notifications, categorizations for notifications, and using notifications as shortcuts triggers.
tags: ios apple wishlist
---
I was recently listening to [Mac Power Users #685: Fighting Digital Distractions](https://www.relay.fm/mpu/685) and it got me thinking about the things I would like to see Apple change to address the issue of “Digital Distractions.” For the purposes of this post, I will focus on the Notifications, as improvements there go a long way toward reducing distractions overall.

## Proposals

I’ve divided my proposals into categories based on the need for improvement. Some are needed more than others and some are more selfish as they would help me with my preferred workloads. This list is not comprehensive and does not preclude other, better ideas.

### Bare minimum

Items in this list are long overdue and would provide for several “quality of life” improvements.

#### Show notifications **ONLY** on the active device

* Currently, notifications will be displayed—and sounded—on all devices regardless of which one is being used.
* Some apps handle this separately and Apple does seem to do some very limited filtering [^1]

#### Sync notification status

* Notifications dismissed on one device should dismiss on all devices.
* The user doesn’t want to be a “notifications janitor.”

#### Provide an "Archived Notifications" section

* Notifications, once tapped; are gone forever.
* A location which listed all notifications with sorting and search options to find previously dismissed notifications.

#### Unified notification settings management

* The ability to choose to have notification settings:
  * Follow other devices (per app or global)
    * This would be the default and would mean a change on one device would affect all others.
  * This device
    * This would be the current behavior and would override the "global" settings (eg. [Overcast](https://apps.apple.com/us/app/overcast/id888422857) "Per Podcast" options).

### Nice to have

Aside from the items listed above, these are things that would help me based on my use cases but may be of limited utility for others.

#### The ability to "snooze" a notification

* The ability to have a notification be dismissed and re-fire later at a time specified by the user would allow users to make notifications more actionable by deferring them to a time that is more convenient.

#### Temporary overrides

* The ability to allow an app to temporarily send (block) notifications based on a time picked by the user.

### Will probably not happen but I really wish it would

These items would be very helpful but differing incentives [^2] and organizational inertia appear to doom these from coming to pass.

#### Categorizations for notifications

* Allows the user to define different behaviors based on the type of notification.
  * I will grant that this would be a nightmare to enforce but I don't think it's an unsolvable one.
    * Apple has a lot of VERY smart people and if this was made a priority I have no doubt a solution could be achieved.
    * Apple controls apps access to the App Store. If apps abuse it; kick them out. It would only take a few examples before others got the picture. They could also use it as a competitive advantage against side-loading or alternative app stores as they would have the power to enforce those kind of rules.
* Categories:
  * **Transactional**
    * Notifications sent based on a specific action you've taken (eg. Made a purchase).
    * Similar to the concept of "Transactional Emails" in the [CAN-SPAM Act](https://www.ftc.gov/business-guidance/resources/can-spam-act-compliance-guide-business).
  * **Account Related**
    * Information regarding your account within the app.
  * **User-Selected Notifications**
    * Related to particular notifications that the user requested.
    * *Example*: MLB app could send you notifications about the Red Sox IF you choose but they could not send notifications concerning other teams.
  * **First-Party Advertising**
    * Notifications related to offers within the app
  * **Third-Party Advertising**
    * Notifications sent on behalf of a third-party OR related to user-generated content that YOU did not choose.

#### Trial-Period for app notifications

* The ability to grant conditional approval for a set period of time, after which the user would be asked again if they wish to grant said permission.

#### Expiring Notifications

* The ability to set a notification and have it auto-dismiss if not used in a particular period of time.
        **Example*: A notification about an event that has already passed or an offer that has already expired.

#### Notifications as Shortcuts triggers

* The ability to kick off a Shortcut and the Shortcut could access the contents of the notification.
  * I know this would be difficult from a security standpoint, but again, I'm confident it could be done safely.

As stated earlier, this is far from comprehensive but even a few of these changes could go a long way toward making our most personal devices work better for us, the owner of the device.

[^1]: “Com.apple.developer.usernotifications.filtering - Apple Developer Documentation.” *Apple Developer Documentation*, 2023, developer.apple.com/documentation/bundleresources/entitlements/com_apple_developer_usernotifications_filtering. Accessed 14 Apr. 2023.
[^2]: Khandelwal, Astha. “9 Best Push Notification Strategies for Marketing [2023].” *Blog*, VWO, 2 Aug. 2019, vwo.com/blog/push-notification-marketing-strategy/. Accessed 14 Apr. 2023.
