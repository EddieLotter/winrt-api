---
-api-id: T:Windows.ApplicationModel.UserActivities.UserActivity
-api-type: winrt class
---

<!-- Class syntax.
public class UserActivity
-->

# Windows.ApplicationModel.UserActivities.UserActivity

## -description

A **UserActivity** is created by an app during its execution to notify the system of a user work stream that can be continued on another device, or at another time on the same device. It provides information about a task the user is engaged in.

## -remarks

A **UserActivity** encapsulates a user's task that can be continued at a later time, and potentially on a different device. Creating a **User Activity** causes that activity to appear in Windows Timeline and in Cortana's Pick up where I left off feature. Timeline is a rich task view that shows a chronological view of what you’ve been working on. It can also include what you were working on across devices. For example, a mail app could create a **UserActivity** when the user starts creating a new email message. The user could pause working on the email and then work on it later on the same machine, or even another device.

## -see-also

[User activities](https://docs.microsoft.com/windows/uwp/launch-resume/useractivities), [UserActivity sample](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/UserActivity)

## -examples
