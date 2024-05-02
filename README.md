# 🚀 April 2024 Release Notes 🚀

## 🎉 New Features

- **Integrated Looker into the Care Platform for Clinicical Managers:** In a continuous effort to make the Care Platform a one stop shop, we've added Looker to the care platform. Clinical Managers will now be directed to the new "manager-dashboard" page on login, where they can interact with looker.

![image](https://github.com/blakeparkinson/Care-Platform-Release-Notes/assets/1864277/373ef7c1-55d9-4e57-9154-6ae283042516)


## 🌟 Enhancements

- **Added 30 minute buffer window so no client surveys go left behind:** Sometimes clinicians need to schedule last minute appoinments, this change ensures that clients will still receive surveys even if they are scheduled last minute.

- **Ported the Utilization page to Roofdog (the new Care Platform):** With the Utilization page now living in the new Care Platform, we updated made updates that allow for an overall better and more accessible user experience.

## 🔧 Improvements

- **Centralized API Layer:** Rather than the Care Platform relying on the browser to make API calls to multiple servies and perform heavy computational logic, we've moved these calls to a dedicated API layer which allows the browser to do its primary job(rendering the page.) This also puts us in a place to begin building Role Based Access.

- **Introduced smart caching:** We're now caching data which skips trips to the server, and makes the care platform feel incredibly snappy overall.

![Alt Text](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGx1dDhwZDRwenBvZzYyZHpveHZvbGowMWU0cmd4aHJ3N2Vka3R6byZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/a7Y6lravckuKA/giphy.gif)

To infinity and beyond,
Clinician Enablement Team
