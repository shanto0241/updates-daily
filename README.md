# Daily GitHub Commit Bot

This repo automatically commits once per day using GitHub Actions to keep your contribution graph green.

## Setup
1. Fork this repository.
2. Go to **Settings → Actions → General** and ensure "Allow all actions" is enabled.
3. Make sure the repository is public if you want contributions to count on your public profile.
4. Enable the GitHub Actions workflow by going to the **Actions** tab and clicking "Enable".
5. Done — it will run daily at 00:00 UTC.

---

**Tip:** You can change the schedule in `.github/workflows/daily.yml` by editing the `cron` expression.
