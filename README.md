# Solo Operator Playbook — buyer download

Paid download page for **The Solo Operator's AI Team: Playbook (v0)**. Hosted on GitHub Pages from `main`. Not a marketing site, and not open source. See `LICENSE`.

Live page: https://joshtitan88-collab.github.io/solo-playbook-dl/

`robots.txt` and the page meta tag are `noindex, nofollow`. Leave both in place so the buyer link stays out of search results.

## What is here

| Path | Role |
|---|---|
| `index.html` | Page a buyer opens after checkout. One download button. |
| `solo-operator-ai-team-playbook-v0.zip` | The file that button serves. |
| `robots.txt` | `Disallow: /` for every crawler. |
| `stable/` | Separate phone board for AI-rep progress. A script on the Mini pushes it. Do not edit those files by hand. |

The page promises future versions at no charge to the email used at checkout, a 30-day refund, and a hand-sent copy if the file is missing. Keep the page honest with those three lines.

## Replace the zip

1. Build the new archive locally. Do not commit the source markdown of the paid playbook into this repo.
2. Replace `solo-operator-ai-team-playbook-v0.zip`, or add a new filename and point the button at it.
3. Push to `main`. Pages rebuilds from that branch.

Buying the playbook is permission to download that zip. It is not permission to republish the repo or the playbook.
