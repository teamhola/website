# ¡Hola! Website

This is a hexo based static website, hosted on VividCloud Cluster L.

Our production server should sync with the `built` branch in this repo.

## Notes for website maintainers

You should run `hexo g && hexo d` after your update. Don't forget to commit & push either.

Sometimes your update don't apply to the online version immediately after your `hexo d`. Just try `hexo g && hexo d` again later.

### Adding a new event

1. Add a new entry in `source/_data/events.yml`;
2. Add a new page in `source/events/<slug>.md`;
3. Commit & push, then `hexo g && hexo d`. 

### Pinning an event on the home page

Just edit `home_event` in `source/_data/home.yml` with the slug of the event.

### Adding members

1. Add in `source/_data/team.yml`;
2. Commit & push;
3. `hexo g && hexo d`.

## Legal

All contents including images, text, hexo theme (`/themes/hola`) and other editorial things in this repo is copyrightted by Team ¡Hola!, and can not be used without license from Team ¡Hola!.

Other code in this repo is opensourced in MIT, if not specifically marked out.