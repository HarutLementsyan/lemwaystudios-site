# Smash_Bash Website

Static support and compliance site for Smash_Bash.

## Files

- `index.html`: public support/homepage for App Store Connect.
- `privacy.html`: privacy policy URL for App Store Connect and AdMob.
- `terms.html`: terms of service.
- `contact.html`: public support contact page.
- `app-ads.txt`: AdMob authorized seller file.
- `assets/`: app icon and splash art used by the website.

## Before Publishing

The current public details are:

- Legal entity: `LemWay Prosperitas LLC`
- Domain: `https://lemwaystudios.com`
- Support email: `smashbashsupport@lemwaystudios.com`

Add a mailing address or additional entity detail if Apple asks you to publish one.

## AdMob Setup

Publish this folder so that `app-ads.txt` is available at the root of the verified app domain:

```text
https://lemwaystudios.com/app-ads.txt
```

The current file contains:

```text
google.com, pub-3445555154266190, DIRECT, f08c47fec0942fa0
```

After deployment, add the domain in AdMob and use the same domain as the app website or marketing URL in App Store Connect.

## App Store Connect LLC Switch

Use the deployed website URLs as:

- Support URL: `https://lemwaystudios.com/`
- Privacy Policy URL: `https://lemwaystudios.com/privacy.html`
- Marketing URL, if needed: `https://lemwaystudios.com/`

Make sure your App Store Connect legal entity, public seller name, support email, privacy contact, and this website all use the same LLC identity.
