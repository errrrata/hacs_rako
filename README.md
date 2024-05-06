# Notice

This repository is intended to formalise as a HACS custom component the code submitted in a PR to homeassistant core by @marengaz but subsequently abandoned when he lost access to his Rako system: https://github.com/home-assistant/core/pull/45915

Since this was a PR from a fork of HA core, I believe that the Apache 2 license should be inherited.

## Why?

There are a few users of Rako lighting (including me) who have successfully used this code, but it is floating around in zip files on the forum (https://community.home-assistant.io/t/rako-lighting/3121) and relatively hidden in an abandoned PR.

So, in order to make this easier to maintain, I have migrated the code into a HACS'ified' form.

## Next steps

- Validate that this repository can be used as a custom-repo in hacs to easily allow access to this repo.
- Bring some of the Python "up-to-date" and make sure that near-future versions of HA don't break compatability with the repo.
- Increase coverage of the Rako API to allow things like fans (which I have in my Rako deployment but which aren't imported by the current implementation)