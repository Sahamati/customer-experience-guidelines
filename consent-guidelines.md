# Design Principles for Informed Consent

## Goal:
- Ensure that users are able to provide explicit and informed consent to share their data
- Avoid cognitive overload for the users during the AA journey
- Ensure all critical information is dissipated to the user about the process and outcome of sharing data.

## Underlying Principles:
1. Should be transparent
    - What data sources am I sharing
    - Both FIP and the account within the FIP for which consent is being requested should be clearly called out.
    - FI Type should be called out clearly indicating in the form of: bank account data, Mutual Fund Data, Insurance Information, etc.
    - What information am I sharing for each data source
    - Both account specific information (balance, transactions, etc.) and user specific information (PAN, DoB) must be called out
    - Any applied data filters should be called out
    - Who am I sharing my information with
    - List of entities that will have access to this data must be called out
    - How long am I sharing my information for
    - Duration for which said entity or entities can access the user’s data (consent life)
    - Duration for which said entity or entities will be able to store the user’s data (data life)
    - Purpose life?
    - Why am I sharing this data
    - Clear callout of the purpose behind granting access to this information. Needs to be meaningful to the user. For example - “Personal finance management”
    - How often will my data be accessed

2. Should be understandable by the user
    - Do I truly comprehend what information is in front of me
    - Consent information should be offered in multiple Indian languages with the user given the option to switch languages if needed
    - There should be visual cues for key information elements. For example - bank logos, account types, etc.
    - The terminology should be user friendly

3. Should empower users with control
    - Am I demonstrating a deliberate action?
    - There should be a clear and explicit action to grant consent.
    - There should be a pathway for the user to exit the flow without granting consent
    - Do I feel I’m in control of my data even after I’ve possibly consented?
    - Users should be told that they can cancel (revoke) anytime
    - Users should be told where they can manage their consent from
    - Do I know that I’ve actually given consent?
    - There should be clear indications of success/failure. This includes aural cues (think transaction success sound on PhonePe, GPay, Paytm), SMS, and other notifications
    - Call out situations where the frequencies are uncommon, for example, if a PFM requests consent for 1000 times a day, that should be called out as unusually high

4. Should not overwhelm the user
    - Is this too much information for me to process?
    - Most important details should be present on the L1 screen
    - Other details can stay one level deep (under ‘view details’ or ‘view more’ or similar)

5. Should reassure the user
    - Do I feel that I can trust this screen?
    - The screen should have certain trust markers.
    - Clarify the ability to cancel consent before action for providing consent.
    - Issue a data receipt to indicate that the data share was successful and as proof of data being shared to a particular entity.

## FIP Selection Screen:
- FI Category
- Info Requested + Data filters
- FI Date Range
- Account and FIP details

## Consent Screen:
- Purpose
- Accounts Overview
- Consent life
- Data Life
- Fetch type - one time or recurring
- Frequency
- Action to grant consent
- Action to exit the flow
- Trust markers
- Callout for ability to cancel consent

Behind other elements (help, etc.):
- Details on how to cancel (possibly under help?)
