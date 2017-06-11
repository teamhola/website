# ¡Hola! Website

This is a hexo based static website, hosted on VividCloud Cluster L.

Our production server should sync with the `built` branch in this repo.

For our tech team members, you should be able to use `hexo g && hexo d` to deploy to that branch.

## Notes for website maintainers

### Adding a new event

1. Add a new entry in `source/_data/events.yml`;
2. Add a new page in `source/events/<slug>.md`;
3. Commit & push, then `hexo g && hexo d`. 

## Legal

All contents including images, text, hexo theme (`/themes/hola`) and other editorial things in this repo is copyrightted by Team ¡Hola!, and can not be used without license from Team ¡Hola!.

Other code in this repo is opensourced in MIT, if not specifically marked out.