# iOS Production Deployment
---
### Prerequisites
##### 1) Apple Developer Account
- You need an Apple Developer Program membership ($99/year).
- Sign up at: https://developer.apple.com/programs/

##### 2) Mac Computer
- Deployment must be done on macOS (physical Mac or Mac in the Cloud).

##### 3) Xcode Installed
- Use the latest version of Xcode from the Mac App Store.
- Includes tools for building, testing, archiving, and submitting apps.

##### 4) App Content Requirements
- Proper App Name, Description, Screenshots, and Privacy Policy URL.
- App must comply with App Store Review Guidelines: https://developer.apple.com/app-store/review/guidelines/

##### 5) Provisioning Profile & Certificates
- Use Apple Developer Portal or Xcode to set up:
    - App ID (Bundle Identifier)
    - Distribution Certificate
    - Provisioning Profile (App Store)

---

### Steps for Production Deployment
##### 1. Prepare Your App for Release
- Set the app version and build number.
- Change build scheme to Release mode.
- Test thoroughly using TestFlight (Apple’s beta testing platform).

##### 2. Archive the App
- Open your project in Xcode.
- Choose Product → Archive.
- After the archive is created, open Organizer to manage it.

##### 3. Validate and Upload the Build
- In Organizer, validate your build.
- Then upload it to App Store Connect.

##### 4. Configure App Store Connect
- Go to https://appstoreconnect.apple.com
- Create a new app record with:
    - App Name
    - Bundle ID
    - SKU
    - App Category
    - App Privacy details
    - Age Rating, etc.

##### 5. Submit for Review
- Attach your uploaded build to the App Store listing.
- Complete all required information.
- Submit the app for review.

##### 6. Wait for Review
- Apple usually takes 1–3 days for app review.
- You may receive rejection feedback—fix issues and resubmit if necessary.

##### 7. Release the App
- Once approved, you can release it immediately, manually, or schedule a release date.
