# iPhoto2

The public website, FoodPhotos privacy policy, and FoodPhotos support page for `iphoto2.com`.

## Files

- `index.html`: iPhoto2 home page
- `privacy.html`: FoodPhotos privacy policy
- `support.html`: FoodPhotos support and troubleshooting
- `AGENTS.md`: repository maintenance rules

## Technology

The site uses plain HTML and the pinned Tailwind CSS browser CDN package. It has no package manager, build process, application JavaScript, analytics, cookies, or forms.

## Local Preview

```sh
python3 -m http.server 8000
```

Open:

- <http://localhost:8000/>
- <http://localhost:8000/privacy.html>
- <http://localhost:8000/support.html>

## Deployment

Deploy the repository root as a static site. Configure the following public URLs in App Store Connect:

- Privacy Policy URL: `https://iphoto2.com/privacy.html`
- Support URL: `https://iphoto2.com/support.html`

Before production deployment, confirm that `support@iphoto2.com` can receive messages.
