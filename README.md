# ¡Hola! Website

This is a hexo based static website, hosted on VividCloud Cluster L.

Our production server should sync with the `built` branch in this repo.

## Notes for website maintainers

You should run `hexo g && hexo d` after your update. Don't forget to commit & push either.

Sometimes your update don't apply to the online version immediately after your `hexo d`. Just try `hexo g && hexo d` again later.

### No more direct event adding/editing

We're moving our event managing to a individual system, teamhola/osem, which is [open sourced on GitHub too](https://github.com/teamhola/osem). If you need access to the administration, please contact other team members.

### Adding members

1. Add in `source/_data/team.yml`;
2. Commit & push;
3. `hexo g && hexo d`.

## Legal

All contents including images, text, hexo theme (`/themes/hola`) and other editorial things in this repo are **copyrightted** by Team ¡Hola!, and can not be used without license from Team ¡Hola!.