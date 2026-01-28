Privacy Policy
Effective Date: October 26, 2023

Last Updated: October 26, 2023

At SatvikScan, we are committed to protecting your privacy while helping you maintain your dietary vows. This Privacy Policy explains how we collect, use, and safeguard your information when you use our mobile application.

1. Information We Collect
We aim to collect the minimum amount of data necessary to provide our food scanning and analysis services.

Authentication Data: We utilize Supabase Anonymous Authentication. This generates a unique, random identifier (UUID) for your device. We do not collect your name, email address, or phone number unless you explicitly choose to provide them later by updating your profile.

Dietary Preferences: We store your preferences, such as "Jain Mode" or "Strict Mode," to accurately filter ingredients like root vegetables, onion, or garlic.


Usage Data: We collect information about the products you scan (barcodes) and the timestamps of those scans to maintain your personal Scan History and award points.

Images and OCR Data: When you use the "Capture Ingredients" feature, the app accesses your camera to perform On-Device Optical Character Recognition (OCR). These images are processed locally to extract text and are not permanently stored on our servers unless submitted as part of a product report.

Device Information: We may collect basic metadata, such as your device model, to troubleshoot errors and optimize app performance.

2. How We Use Your Information
Dietary Analysis: To analyze food ingredients against our specialized Satvik and Jain databases.


Gamification: To maintain a leaderboard based on "Contribution Points" earned through scanning and verifying products.

Community Contributions: To allow users to contribute new products and ingredients to the global SatvikScan database.


Security: To prevent spam and maintain the integrity of our database through rate-limiting and automated audit logging.

3. Data Sharing and Third Parties
We do not sell your personal data. Information is shared only with the following services necessary for app functionality:


Supabase: Our primary backend provider where scan history, points, and anonymous profiles are securely stored.

Open Food Facts API: If a product is not in our local database, we query the Open Food Facts API using the barcode. No personal user identifiers are sent to this third party.

Google ML Kit: Used for on-device text recognition and language translation of ingredient lists.

4. Data Retention and Deletion
Anonymous Profiles: Your profile remains active as long as the anonymous session exists on your device.


Scan History: You can clear your scan history at any time through the "Scan History" screen, which removes the records from our servers.

Account Deletion: If you wish to delete your profile and all associated data, you may do so within the App Settings. Due to our use of anonymous authentication, clearing your app data or deleting the app may result in a permanent loss of access to your profile.

5. Security Measures
We implement rigorous security protocols to protect your data:


Row Level Security (RLS): We use Supabase RLS to ensure users can only access their own scan history and profile data.


Environment Obfuscation: Critical API keys and backend configurations are obfuscated within the application code to prevent unauthorized access.

Input Sanitization: All user-submitted data is sanitized to prevent SQL injection and cross-site scripting (XSS) attacks.

6. Children’s Privacy
SatvikScan does not knowingly collect or solicit personal information from children under the age of 13. If we discover we have collected information from a child under 13, we will delete it immediately.

7. Changes to This Policy
We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new policy within the app and updating the "Effective Date" above.

8. Contact Us
If you have questions regarding this Privacy Policy, please contact us at: Email: support@satvikscan.com