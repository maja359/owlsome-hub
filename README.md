# owlsome-hub

Brand Hubs served on `hub.weareowlsome.com`, one folder per brand.
Each folder path carries a random suffix so the address is not guessable,
and every page is `noindex` with a site-wide `robots.txt` disallow.

Built from `brand-os/<brand>/` in the Maja-OS repo:

```
python3 brand-os/build-hub.py brand-os/<brand> --drive "<client Drive folder>"
cp brand-os/<brand>/brand-hub.html <this repo>/<brand>-<token>/index.html
git add -A && git commit -m "hub: <brand>" && git push
```
