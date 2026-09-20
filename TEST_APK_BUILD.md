# Fico Test 2.1 — Build and install

This is a complete test project. It does not use production AdMob IDs, so it can be tested without connecting an AdMob account.

## Android Studio
1. Open the project folder in Android Studio.
2. Let Gradle sync.
3. Select **Build > Build APK(s)**.
4. Install `app/build/outputs/apk/debug/app-debug.apk` on your Android phone.

## Command line
From the project root:
`./gradlew assembleDebug`

The debug APK will be:
`app/build/outputs/apk/debug/app-debug.apk`

## Test checklist
- First launch onboarding
- Add income
- Add expense
- Edit transaction
- Delete transaction
- Search transactions
- Filter income/expense
- Budget amount and progress
- Category report
- Monthly totals
- AED/USD display switch
- Dark mode
- CSV share/export
- Data survives app restart
- Reset all data
