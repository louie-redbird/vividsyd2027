# The Porch Light: phone prototype

A prototype of the phone experience for The Porch Light, Meals on Wheels NSW's proposed Vivid Sydney 2027 activation.

## Put it online with GitHub Pages

1. Sign in to github.com and create a new repository (for example `porch-light-prototype`). Set it to Public.
2. Click **Add file > Upload files**, drag in `index.html`, and click **Commit changes**.
3. Go to **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, then **Save**.
4. After a minute or two, your page is live at `https://<your-username>.github.io/porch-light-prototype/`.
5. Open that address on your phone. Add `#door1` to open a door screen, `#screen` for the big screen, or `#screendemo` for a big screen demo that plays sample messages.

## What works on GitHub Pages

- The full phone journey, including the camera with front and back switching (GitHub Pages uses HTTPS, which phones require for camera access).
- Messages are approved automatically after about 8 seconds, because there is no live moderator connection outside claude.ai.
- Payments are a demo only. No payment is taken.

## What needs claude.ai

The live connection between phones, the moderator, the big screen, the doors and the admin area only works in the claude.ai version:
https://claude.ai/artifact/BjYNrm2JxqTzy2rrgxb22a

## Privacy

Don't collect real personal details with this prototype. It is for discussion with Destination NSW only.
