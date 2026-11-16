# Multi-Language SCORM Wrapper: Staff Notes

Cobblestone Learning · *Learning. Creativity. Trust.*

A way to put several language versions of the same e-learning module into one SCORM 1.2 package. When a learner opens the course, they first see a short screen asking which language they want. They pick one and the course opens in that language. The learning platform only sees one course, however many languages are inside it.

## What you can do with it
- Offer one course in several languages without setting up a separate course for each.
- Set the course title, the wording on the language screen and the default language.
- Have the learner's choice remembered, so they go straight back to the same language next time.

## How to use it
1. Download this repo and work in its **package** folder.
2. Put each language version of the module into **package/scos**, one folder per language, named the same way with the language on the end (for example `My_Module_English`, `My_Module_French`).
3. Fill in the settings file **package/conf/conf.js**: the course name, the languages, and the wording on screen.
4. Update the course details in the package's manifest file.
5. Zip the contents of the **package** folder and upload the zip to the learning platform as a SCORM 1.2 course.

## Good to know
- All the language versions should be made with the same authoring tool, because they share one launch file name.
- The language choice is normally saved with the learner's course record. If that causes trouble, it can be saved in the browser instead, but then it will not follow the learner to another computer.
- This repo is public, because it is based on an open-source project. Keep anything private out of it.

## Who to ask
- Owner: **the Cobblestone Learning team**

## Shared notes
*Leave notes for each other here: ideas, problems, things to watch. Add your name and the date.*

- *(none yet)*
