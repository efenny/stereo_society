# Project `stereo_society`

Generate data for events related to ((([Stereo](https://www.instagram.com/stereomontreal)))) Montreal.

## Roadmap

### MVP

- [ ] CLI for:
    - [ ] Use simple data source such as JSON and generate Markdown
- [ ] Save markdown output to repo

### Data features

- [ ] Spotify links of artists
- [ ] Soundcloud links of artists
- [ ] Server to:
    - [ ] Check Facebook to see if Stereo posted line up
        - [ ] Starting 15th of the month until last day for every 30 min 
        - [ ] If and only if there is no data required for the month
    - [ ] Download promitional images from Facebook and upload to image hosting platform
        - [ ] Imgur?
        - [ ] Other
    - [ ] From promotional images analyze and get:
        - [ ] Artists names
        - [ ] Dates
        - [ ] Metadata such as All Night Long or Day Rave

### Events

- [ ] Stereo
    - [ ] Scareo?
- [ ] Stereobar
- [ ] Stereobar - Les Beaux Dimanches

#### Stretch goals

- [ ] JSON and CSV output options
- [ ] Static site with past history

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### MakeFile

Run build make command with tests
```bash
make all
```

Build the application
```bash
make build
```

Run the application
```bash
make run
```

Live reload the application:
```bash
make watch
```

Run the test suite:
```bash
make test
```

Clean up binary from the last build:
```bash
make clean
```
