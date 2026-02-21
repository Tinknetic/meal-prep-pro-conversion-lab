# Event Tracking Spec (Conversion Lab)

## Funnel events (recommended)
- landing_view
- cta_click
- signup_start
- signup_complete
- onboarding_start
- onboarding_complete
- paywall_view
- checkout_start
- purchase
- trial_start
- trial_cancel

## Properties to include
- variant (e.g. paywall_v1, paywall_v2)
- plan (monthly/annual)
- source (utm_source)
- campaign (utm_campaign)
- device (web/ios/android)
- country
- referrer

## Notes
- Always attach `variant` for experiments.
- Use consistent naming. Don’t change event names mid-test.
