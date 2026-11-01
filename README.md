# ios_diet_app_hosted

The public website for the Diet App: the **privacy policy** (`index.html`) and the
**support page** (`support.html`), hosted free with GitHub Pages from the
[ios_diet_app_hosted](https://github.com/drew0ps/ios_diet_app_hosted) repository.

- Privacy policy: <https://drew0ps.github.io/ios_diet_app_hosted/>
- Support: <https://drew0ps.github.io/ios_diet_app_hosted/support.html>

Both URLs are entered in App Store Connect (App Information › Privacy Policy URL; the support URL).
App Review needs them, the more so because the app uses HealthKit.

## Editing

Plain static HTML, no build step: edit a page, push to `main`, and Pages republishes within a
minute or so. The privacy policy text must stay in sync with the in-app copy at
`ios_diet_app/DietApp/Resources/PrivacyPolicy.md` - change both together, with a new
"Effective" date when the meaning changes.
