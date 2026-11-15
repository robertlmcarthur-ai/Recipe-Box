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

## Recipe review status
All 33 recipes (RB-001 to RB-033) and their four versions were reviewed on November 15, 2026. This was a desk review by Claude (AI) against general cooking, food-safety and allergen knowledge. No recipe was cooked or tested, and it is not a professional dietitian or allergist review. The in-app "check every label" warnings stay in place.

Fixed in this review:
- Molly's versions: every dairy substitute (cheese, cream cheese, sour cream, feta, buttery spread, ranch, Caesar) now says nut-free, because many are almond- or cashew-based
- RB-016 Molly: oat milk now must be certified gluten-free (or use soy milk)
- RB-031 Molly: puff pastry now gluten-free as well as dairy-free
- RB-025 Maddie: blue cheese marked "check label"
- RB-010 Keto: sausage was at risk of undercooking ("about 20 min total"); now full time to 160°F
- RB-005 Keto: xanthan gum no longer used to coat the beef; amount cut to 1/4 tsp for the sauce
- RB-013 Keto: black beans replaced with avocado
- RB-018 Keto: corn replaced with zucchini
- RB-003: all three dietary versions now have full ingredient lists, steps and shopping lists instead of swap notes
- RB-001, RB-002, RB-005, RB-010, RB-012, RB-023, RB-033: versions no longer say "as in base"; steps are written out

Owner sign-off still needed:
- RB-003 Molly uses coconut cream. Confirm coconut is acceptable for a nut-free version.
- RB-004 Molly keeps sesame seeds (optional). Sesame is not a nut but is a common allergen.
- RB-021 Keto still uses carrots (reduced to 3/4 lb). Decide whether that is keto enough.
- RB-003 seasoning and xanthan gum amounts are marked "estimate" in the recipe.
- RB-001 bakes at 390°F and RB-002 lists 2 tbsp flaky finishing salt. Confirm both against the source videos.
- Brand examples (Violife, Tofutti, Earth Balance, King Arthur) change their formulas; confirm current labels.
- Nothing has been kitchen-tested.

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
