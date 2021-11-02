# Polyhedron Engine(Q2RTX Fork) base data repository.

One will need this repository to easily get up and running with Nail & Crescent (The defacto end-goal game for our engine.) Eventually (not today), this repository will include several python scripts to ensure only the data that matters to the game gets copied and thus exported into a clean new folder which is ready for release to the public.

## Description:

The repository comes with several files and folders:
### Files
Without these files in the root engine folder, you're going to have a nasty time.

>- default.cfg
>- nacconfig.cfg

### Folders
> - Root repository folder: > Any things such as README.MD or certain python scripts that automate things belong right here. (I can already see a .bat file in my magic ball to automatically pick the basenac, or.. > basenac: Content that is ready for publishing goes in here. In case a mod does not have several files, that means it either refers to the baes engine game, or the file is simply missing.
> - mods/*modname: > This can be used for us developers to make mods. A mod, does not need to be an entire copy of basenac. It can of course have its own custom client/server -game dll. It's own subfolders just like basenac. (Wise idea to do so)
> - developers: > Contains subfolders such as the Nail & Crescent game configuration entry for TrenchBroom as well as EricWA his latest compiler (for now).

## Acquiring it:
One has to acquire the repository by doing a recursive submodule clone. 

```git clone --recursive-submodules https://github.com/WatIsDeze/BaseNaC.git ```

## Usage:

>- Be sure to all work on .gitignore, and let's do it on a per folder basis. We do not want editors creating technically hidden temporarily backup files and all that being uploaded. 
>- Keep it clean, maintain it clean.
>- Working on a new feature that may require data to be ditches in case for example the code never gets completed to use it? Branch this repository.

## Outro:

For today I am pretty sure that'll be all :)
