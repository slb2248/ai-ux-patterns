# Duration-Bound Consent

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/duration-bound-consent](https://aiuxplayground.com/pattern/duration-bound-consent)

> Permissions that expire by default

## Overview

Duration-bound consent is an AI interface design pattern that grants agent permissions with a built-in expiration (an hour, a day, a session, a quarter) rather than letting access persist indefinitely until explicitly revoked. This UX pattern asks users to re-authorize on a visible cadence, so scope never silently outlives the intent that created it. By treating time as a first-class dimension of consent, the pattern protects users from the long-tail risk of forgotten grants: OAuth tokens issued years ago that still read the inbox, dev keys that still write to production, assistants that still have calendar access two jobs later. Pairing duration with visible countdowns and painless re-auth keeps friction proportional to the sensitivity of the scope, and it turns consent from a one-time event into a recurring, legible conversation.

## Good for

Essential for OAuth-based assistants, enterprise AI tools, and any agent whose permissions outlive a single task, where expiring grants prevent long-tail security risk from forgotten authorizations.

## Seen in

- 1Password SSH agent timeouts
- macOS screen-recording re-prompts
- GitHub fine-grained tokens
- AWS STS temporary credentials

## On the site

[Duration-Bound Consent demo](https://aiuxplayground.com/pattern/duration-bound-consent) · [more trust](https://aiuxplayground.com/patterns/trust)
