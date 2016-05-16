# fresh-theme-elegant

Responsive resume theme for [HackMyResume](https://github.com/hacksalot/HackMyResume) adapted for the FRESH schema from [Mudassir](https://github.com/mudassir0909)'s [jsonresume-theme-elegant](https://github.com/mudassir0909/jsonresume-theme-elegant).
I used [Antonio Ruberto](https://github.com/aruberto)'s [fresh-theme-bootstrap](https://github.com/aruberto/fresh-theme-bootstrap) theme as base guidelines to make this theme using the [Handlebar](http://handlebarsjs.com/) template engine.

For now this **only** a **HTML** theme.
I'm open to suggestion concerning the frontend code and the UI/UX, see [Contributing](#contributing) for more information.

## Sections
The sectionss currently available are:
* Profile (with name, photo, label, address, phone, email, website, languages and social links)
* About (with you info.brief)
* Work Experience (employment)
* Skills
* Education
* Projects
* Volunteer Work (service)
* Interests
* Awards (recognition)
* References
If a section is not used in your FRESH resume it will simply not be displayed

### Supported Profiles
All the profiles not on this list may not have an icon and will not have any custom color.
* angellist
* behance
* bitbucket
* codepen
* dribbble
* dribble
* exercism
* facebook
* foursquare
* instagram
* github
* googleplus
* gratipay
* hackernews
* lastfm
* linkedin
* pinterest
* reddit
* skype
* soundcloud
* spotify
* stackexchange
* stackoverflow
* tumblr
* twitter
* vimeo
* youtube
* medium
* blogger
* steam


## How to use it
Go where your FRESH JSON resume is located and run:
```
npm install fresh-theme-elegant
```
Then to export your resume using this template run:
```
hackmyresume BUILD resume.json TO out/resume.all --theme node_modules/fresh-theme-elegant/
```

## Goals
In the long term this template will support all the FRESH sections and will let the final user decide what to put in their FRESH resume.
This template will also aim at supporting other languages that English.

## Contributing
There are many ways you can help improve this theme (and most don't even require coding):
* Open an issue to report a bug with the theme
* Open an issue to discuss the layout of a section (or of the entire resume) and we'll find what fits best
* Open an issue to request a particular section or field to be added (if you can describe how you imagine the layout it's even better)
* Open an issue to request the addition of a new feature, like displaying the duration between start to end (yes it is already on my to-do list)
* Fork the repo, make a new branch with your changes and make a pull request describing the changes you want to apply (bug fix, feature, section, layout, ...)
