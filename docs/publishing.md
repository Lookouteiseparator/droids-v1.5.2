# Publishing checklist

## 1. Repository

- **Name:** `droids`
- **Description:** Android ADB toolkit - debloat, backup, sideload, and mirror any device without root.
- **Topics:** `android adb debloat adb-toolkit scrcpy backup sideload no-root`
- **Visibility:** public

## 2. First push

```bash
git init
git add .
git commit -m "Droids 1.5.2 - initial release"
git branch -M main
git remote add origin https://github.com/<you>/droids.git
git push -u origin main
```

## 3. Release

1. Draft a release tagged `v1.5.2`.
2. Title: `Droids 1.5.2`.
3. Body: copy the top entry from `CHANGELOG.md`.
4. Attach the build archive.
5. Publish.

## 4. Settings

| Setting | Value |
| --- | --- |
| Website | the download folder |
| Discussions | enabled |
| Issues | enabled |
| Social preview | export `assets/hero.svg` at 1280x640 |

## 5. First week

- [ ] Release + pin
- [ ] Push a small follow-up commit
- [ ] Reply to every issue within 24 h
- [ ] Publish one screenshot or clip
- [ ] Ship 1.5.2 patch with a visible fix

Keep a 2-3 day commit cadence. Consistency beats volume.