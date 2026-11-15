# Recipe Box: App Store listing draft

## Basic info
- **Name:** Recipe Box
- **Subtitle (30 characters max):** Recipes for every diet
- **Category:** Food & Drink
- **Privacy policy URL:** https://robertlmcarthur-ai.github.io/Recipe-Box/privacy.html
- **Support URL:** https://github.com/robertlmcarthur-ai/Recipe-Box
- **Price:** Free

## Promotional text
Dinners, sides, and appetizers, each with Original, gluten-free, dairy- and nut-free, and keto versions.

## Description
Recipe Box keeps your family's favorite dinners, sides, and appetizers in one place. Every recipe comes in four versions: Original, Maddie's gluten-free, Molly's gluten-, dairy- and nut-free, and Keto. Switch versions with one tap and see the ingredients, steps, and shopping list for that version.

Use Recipe Box to:
- Get a random main, side, and appetizer suggestion each time you open the app
- Browse all 33 recipes by course (mains, sides, appetizers, bread), or search by name or ingredient
- See ingredients, step-by-step instructions, and a shopping list for every version
- Save favorites so they're easy to find later
- Copy a shopping list with one tap

Recipe Box works offline. All recipes are built in, and your favorites stay on your device. The only thing the app ever sends is a recipe video suggestion, and only if you choose to submit one.

Note: recipes are written from general cooking knowledge. Check ingredient labels, especially for allergies and dietary needs, before you cook.

## Keywords (100 characters max, comma separated)
recipes,dinner,sides,appetizers,gluten free,dairy free,nut free,keto,meal planning,shopping list

## Age rating
Answer "None" to every content question. The app has no objectionable content.

## Privacy nutrition label
- Contact info (email address): collected only if a user chooses to enter it in the recipe submission form. Not linked to identity, not used for tracking. Used for app functionality.
- Other user content (video link, dish name, note): collected only from the submission form. Used for app functionality.
- Tracking: No.

## Screenshots needed
- 6.9-inch iPhone (1290 x 2796 or 1320 x 2868): home with Recommended, the All recipes list, a recipe in the Original version, the same recipe in Keto, favorites
- 13-inch iPad (2064 x 2752): the same screens. Required because the Xcode project targets iPad as well as iPhone. To skip these, set the target to iPhone only in Xcode (General > Supported Destinations).
- Check the current size list before capturing: https://developer.apple.com/help/app-store-connect/reference/screenshot-specifications

## Needs review before release
Every recipe below is marked "Drafted — verify" and needs a person to check the ingredients, steps, and dietary versions before public release:
RB-001, RB-002, RB-003, RB-004, RB-005, RB-006, RB-007, RB-008, RB-009, RB-010, RB-011, RB-012, RB-013, RB-014, RB-015, RB-016, RB-017, RB-018, RB-019, RB-020, RB-021, RB-022, RB-023, RB-024, RB-025, RB-026, RB-027, RB-028, RB-029, RB-030, RB-031, RB-032, RB-033

## Still to do (Mac)
- Apple Developer enrollment
- App icon and launch image are now in the project (simple "RB" recipe-card mark); replace with final artwork if wanted
- Run `npm install` then `npm run sync` so the updated www/index.html is copied into the iOS app
- In Xcode, confirm PrivacyInfo.xcprivacy shows under the App target (Build Phases > Copy Bundle Resources)
- Test on a real iPhone: copy shopping list, favorites surviving a relaunch, and one form submission
- Turn on GitHub Pages for this repo so the privacy policy URL above is live
- iPhone is locked to portrait; iPad still rotates
- Screenshots
- Archive and upload through Xcode
