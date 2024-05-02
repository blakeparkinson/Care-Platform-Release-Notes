# 🚀 April 2024 Release Notes 🚀

## 🎉 New Features

- **Integrated Looker into the Care Platform for Clinicical Managers:** In a continuous effort to make the Care Platform a one stop shop, we've added Looker to the care platform. Clinical Managers will now be directed to the new "manager-dashboard" page on login, where they can interact with looker.


## 🌟 Enhancements

- **Added 30 minute buffer window so no client surveys go left behind:** Sometimes clinicians need to schedule last minute appoinments, this change ensures that clients will still receive surveys even if they are scheduled last minute.

- **Ported the Utilization page to Roofdog (the new Care Platform):** With the Utilization page now living in the new Care Platform, we updated made updates that allow for an overall better and more accessible user experience.

## 🔧 Improvements

- **Centralized API Layer:** Rather than the Care Platform relying on the browser to make API calls to multiple servies and perform heavy computational logic, we've moved these calls to a dedicated API layer which allows the browser to do its primary job(rendering the page.) This also puts us in a place to begin building Role Based Access.

- **Introduced smart caching:** We're now caching data which skips trips to the server, and makes the care platform feel incredibly snappy overall.

To infinity and beyond,
Clinician Enablement Team
