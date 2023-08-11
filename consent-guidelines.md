# Design Principles for Informed Consent

## Goal: 
- Transparent, without cognitive overload: People want to feel like they’re making informed decisions, so they’re curious to know more. However, the line between just-enough information and too much information is thin, and overshooting it can lead to cognitive overload and drop-offs.
- Empowering, with meaningful control: People value being in control, but it's important to present choices in the right context and with enough knowledge built beforehand to make that control meaningful.
- Trustworthy, while creating digital and financial confidence: People look for evidence of safety and security, especially when it comes to making high-stakes financial decisions where a wrong move can cost them time and money.
- Educational, with progressive awareness of consent: People are new to the idea of explicit and informed consent. It will take time for them to understand how to make the right decisions. This is more easily built over several instances rather than all at once in the first instance.

## Underlying Principles: 
### Transparent, without cognitive overload:
- What data sources am I sharing?
  - Both FIP and the account within the FIP for which consent is being requested should be clearly called out.
  - FI Type should be called out clearly indicating in the form of: bank account data, Mutual Fund Data, Insurance Information, etc.
- What information am I sharing for each data source?
  - Both account-specific information (balance, transactions, etc.) and user-specific information (PAN, DoB) must be called out either at the consent stage or at the linking stage (if the intention to link is considered as implied consent).
  - Any applied data filters should be called out.
- Who am I sharing my information with?
  - List of entities that will have access to this data must be called out on the screen where user consent is being collected.
- How long am I sharing my information for?
  - Duration for which said entity or entities can access the user’s data (consent life).
  - Duration for which said entity or entities will be able to store the user’s data (data life).
- Why am I sharing this data?
  - Clear callout of the purpose behind granting access to this information. Needs to be meaningful to the user. For example - “Personal finance management”.
- How often will my data be accessed?

### Educational, with progressive awareness of consent:
- Do I truly comprehend what information is in front of me?
  - Consent information should be offered in multiple Indian languages with the user given the option to switch languages if needed.
  - There should be visual cues for key information elements. For example - bank logos, account types, etc.
  - The terminology should be user-friendly and as close to layman language as possible.

### Empowering, with meaningful control:
- Am I demonstrating a deliberate action?
  - There should be a clear and explicit action to grant consent.
  - There should be a pathway for the user to exit the flow without granting consent.
- Do I feel I’m in control of my data even after I’ve possibly consented?
  - Users should be told that they can cancel (revoke) anytime.
  - Users should be told where they can manage their consent from.
- Do I know that I’ve actually given consent?
  - There should be clear indications of success/failure. This includes aural cues (think transaction success sound on PhonePe, GPay, Paytm), SMS, and other notifications.
  - Call out situations where the frequencies are uncommon, for example, if a PFM requests consent for 1000 times a day, that should be called out as unusually high.
- Should not overwhelm the user.
  - Is this too much information for me to process?
  - Most important details should be present on the L1 screen.
  - Other details can stay one level deep (under ‘view details’ or ‘view more’ or similar).

### Trustworthy, while creating digital and financial confidence:
- Do I feel that I can trust this screen?
  - The screen should have certain trust markers.
  - Clarify the ability to cancel consent before action for providing consent.
  - Issue a data receipt to indicate that the data share was successful and as proof of data being shared with a particular entity.

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
- Callout for the ability to cancel consent 

## Behind other elements (help, etc.)
- FI Category
- FIP Date Range
- FIP and Account Details
- Details on how to cancel (possibly under help?)
