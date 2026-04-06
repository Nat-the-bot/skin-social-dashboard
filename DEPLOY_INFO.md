# Skin Social Dashboard - Deployment Info

## Live URL (Cloudflare Tunnel - Active while Mac mini is running)
https://ronald-logs-sydney-thinking.trycloudflare.com

Note: This URL is active as long as the background processes are running on the Mac mini.
- HTTP Server PID: stored in /tmp/dashboard-http-pid.txt
- Cloudflare Tunnel PID: stored in /tmp/dashboard-cf-pid.txt

## Backup (Netlify - Password Protected)
URL: https://sage-parfait-24101b.netlify.app/
Password: My-Drop-Site
Claim URL: https://app.netlify.com/drop/sage-parfait-24101b#drop_token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9...

## For Permanent Hosting Options
1. Claim the Netlify site at the claim URL above to get a permanent free URL
2. Or deploy to GitHub Pages - requires `gh auth login` (Natalie to run once)
3. Or drag-and-drop index.html to app.netlify.com/drop for a fresh anonymous deploy

## Dashboard File
/Users/macmini/.openclaw/workspace/dashboard/index.html
