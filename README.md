# Privacy Policy for Enchanted Labyrinth

**Last updated November 4, 2026**

Artem Rapota develops Enchanted Labyrinth for Android (package `enchanted.labyrinth`). This policy explains what information the game processes when you play and how to contact the developer about it. The advertising and age-choice sections apply to versions of the game that include ads.

## Playing without registration

You can play without giving your name, email address, phone number, or date of birth. Google Firebase Authentication automatically assigns your guest account a unique identifier (UID) and manages the credentials for that session. The UID allows game records from the same account to be linked. Firebase services also process technical information, such as installation identifiers and IP addresses, to provide and secure their services.

## Levels, attempts, and game statistics

The game sends gameplay records to Google Cloud Firestore under the guest UID. These records include level starts and completions, losses, and restarts. The developer uses them to understand how far players get, how often they retry, and which levels are difficult. The game does not use these server records to restore your level.

The Android game also includes the Google Analytics for Firebase library. When automatic collection is enabled, it can send usage events such as first opens and sessions, along with an app-instance identifier and information about the app and device, to Google. The developer records the level and attempt statistics described above separately in Firestore.

## Age choice and advertising

The ad-supported game asks “Are you 18 or older?” and saves your Yes or No answer on your device so you do not have to answer each time you play. The developer does not send the answer to Firestore, attach it to your guest account, or use it for age statistics.

Your answer determines the advertising setting sent to Google AdMob:

- **No.** The game requests Google's child treatment for ads. This disables personalized ads and remarketing, and Google does not transmit the Android advertising ID with those requests.
- **Yes.** The game requests the default advertising treatment. Answering Yes identifies the selected age group only. It does not give consent to personalized advertising.
- **Before you answer.** The game waits while the age question is open. If the age screen is unavailable and there is no saved answer, the game uses child treatment.

These settings apply to advertising. The anonymous session and game records described above are processed separately.

## Ads and rewards

The game uses Google AdMob to show two kinds of ads. You can choose to watch a rewarded ad for an easier attempt. The game grants that benefit when AdMob reports that the reward was earned. An interstitial ad may also appear during a break between attempts. The developer uses AdMob directly without adding other ad networks through mediation.

Depending on the advertising settings and available identifiers, Google's Mobile Ads SDK may collect and share IP addresses (used to estimate approximate location), app and ad interactions, diagnostic information, and device identifiers such as the advertising ID. Google uses this information to deliver and measure ads, analyze performance, and detect fraud. Non-personalized ads can still involve these activities.

## Storage and retention

The developer has no fixed retention period or automatic deletion schedule for the anonymous accounts and the gameplay records stored under their UIDs. These records can remain indefinitely until the developer deletes them manually. Uninstalling the game does not erase records already stored in Firebase.

The age answer remains in the game's local settings. Clearing the game's Android app storage removes local settings and may also erase local progress. Google applies its own retention practices to the technical and advertising data it processes. Firebase and AdMob encrypt data in transit. Google's services may process information outside the country where you play.

## Privacy questions and requests

Email **rapotausa@gmail.com** to ask about your information or exercise applicable rights, including access, correction, deletion, or objection to processing. A parent or guardian can use the same address about a child's information. If you email, the developer receives your address and the information you choose to include and uses them to respond.

There is currently no in-game deletion button. The developer cannot locate a particular guest's Firestore records from an email address alone because the game does not associate email addresses with guest UIDs. Please do not send passwords or authentication tokens.

## Further information and updates

For details about Google's services, see [Firebase privacy and security](https://firebase.google.com/support/privacy), [how Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites), and [Google's data retention practices](https://policies.google.com/technologies/retention).

Changes to this policy will be posted on this page with a revised date. The privacy contact for Enchanted Labyrinth is Artem Rapota at **rapotausa@gmail.com**.
