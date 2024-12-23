---
title: GitLab and [x]
layout: home
---

The `x` in the title is not to be confused with `X`, which previously was named Twitter. It is `x` as in placeholder.

This is a living document and ideally a collaborative one: 

- (I will add some more info on how to collaborate on this doc soon.)
- Have something to add about tool x's interaction with GitLab? Go on and add it.
- Have suggestions or corrections? Open an issue or a pull request.
- Does something bother you about using GitLab, like "ahh, it is not usefull for x!"? Open an issue and describe what is bothering you.
- Need help with GitLab

## Why `GitLab and x`?

...

## GitLab and HackMD

- HackMD for live-synced collaboration, if *live* sync is what is specifically necessary.

## GitLab and NextCloud

- NextCloud files as link in GitLab: you risk that someone breaks the link when moving some file inside NextCloud.
- Put files into GitLab (probably best into a repository, maybe) and they are always linked to their "topic".
  - What about sharing files then?
    - Is the one you want to share with internal to your organization? Use GitLab!
    - Are they outside your organization? But do they have access to *that* specific GitLab project / repository? If not, but you want to collaborate, maybe they should have access to it?! Use GitLab!
    - They have absolutely no access and should not have it? Then ... (I have to think about this one, but it probably depends on what you want to achieve. Because if you internally still need to collaborate on that file or project, it still should live within GitLab. Once you let someone collaborate on that in another place, collaborating gets harder and slows you down, e.g. by merge conflicts, loosing track of changes, etc.)

## GitLab and Mail

- Some mails are actually good to keep and answer(!) in GitLab issues.
- (When, why, and how I still have to flesh out. Do you have an idea?)

## GitLab and MS Teams

- You use Teams direct messages, channels, etc. as storage or archive like "I post this here so we/I don't forget"? Use GitLab!

## GitLab

- Don't have editable text as updateable information, e.g. don't use the edit function of issue description (that is what is the top most part on an issue page) to use that text as an updateable info side. That is what wiki pages are made for. Edit is only for error corrections shortly after the time of original posting something.
- If a post is long a ago and you see an error: write the erratum e.g. in an issue comment and then do that fix in the editable text. Maybe also note there that you corrected something.
  - Exception: repositories and wikis. They are thought for this. Issues and discussions are not.

### Advantages / Benefits

- Issue templates for reoccuring things, e.g. newsletter organization, event organization.
  - Everything like "next time we should..." => adapt the issue template
  - Everything like "we do it like this step, than that step, than ... each time" => create an issue template
- Everythig is easily cross-referenceable
