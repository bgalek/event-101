
The purpose of this document is to provide useful tips for organizing offline and hybrid events for larger audiences.
It can also serve as a checklist when preparing your own event!

## For organizers

### Time

Please remember that not everyone lives in the same time zone.
This is especially important when inviting guests to give keynotes or talks.

### Communication

* as soon as you know the date of the event, announce it!
  * use email aliases targeting your audience
	> When sending emails, remember to include the proper JSON-LD schema!
	> This will help your email get noticed and make it usable by AI and calendar tools.
	> Check out [https://schema.org/Event](https://schema.org/Event) for examples!
	> 
	> Reuse the same email subject to make it easier for your audience to find emails they've missed.
	> Remember to use BCC when sending emails to protect recipients' privacy!
  * use public chat channels targeting your audience
  * use social media if applicable

* create Slack/Teams/Discord channels for speakers, attendees, and organizers
  * \#event-speakers (private, only for speakers)
  * \#event-organizers (private, only for people who are involved)
  * \#event or #event-YEAR (public)

* create calendar entries for attendees
	* with agenda
	* with all necessary links

* create calendar entries for organizers
	* to discuss organizational matters regularly

* create calendar entries for speakers and organizers
	 * at least one opportunity to meet and discuss the speakers' requirements
	 * schedule an online rehearsal if needed

* send speakers and organizers reminders in Slack/Teams/Discord

### Guests

If you're holding a hybrid event, make sure keynote speakers and special guests will be there in person.
It's discouraging when your most important guests miss the opportunity to experience the whole event and only call in to kick it off.

### Webpage
> Use GitHub Pages for a quick start.

* create a domain (event.company.io / event.io) for the event, if one doesn't already exist
* create a webpage at that domain with the most important information:
  * agenda
  * venue
  * registration (if possible)
  * video streams (if possible)
 * preserve the event's history by providing a folder for each year
    so people can explore it in the future (event.company.io/2022; event.company.io/2023)

### Recording

* hire a recording company to have your event professionally recorded
* use YouTube as one of the most feature-rich platforms worldwide
  * subtitles 
  * live chat
  * playlists
  * ability to easily cast streams to screens
  * playback for people watching later
  * ability to create private playlists accessible to the whole organization
* use streaming studio software like OBS or StreamYard

### Venue

The venue should be large enough to accommodate everyone comfortably. Choose a place that meets your requirements and suits the expected number of participants.

Stage:
* ensure a stable network connection
	* if using Wi-Fi, it's a good idea to have two networks (one for speakers and one for the audience)
* mark the floor with a red dot or tape so speakers know where to stand
* prepare a monitor for speakers to see their notes and slides
	* or at least provide a clock they can see
* prepare physical cues that people in the first row can hold up
  * "5 minutes left"
  * "speak louder"
  * "repeat the question"
  * "speak into the microphone"
  * "halfway through"
  * "no time for audience questions"
* open and print individual [English](organizer-cue-cards.en.html) or [Polish](organizer-cue-cards.pl.html) cue cards
 * invite all speakers to sit in the first row
* provide microphones for speakers, hosts, and audience members (so people can ask questions without the host having to run around)

Add each cue card to `_data/organizer-cue-cards.yml` with a unique `id` and set `size: long` for longer messages. Add a small Markdown page for each card under `organizer-cue-cards/<language>/<id>.md`, with `layout: organizer-cue-cards`, the matching `language` and `card` values, and a permalink ending in `/<id>/`. The language page automatically lists cards from the data file. To add a language, add its translations and create a Markdown overview page with `layout: organizer-cue-cards` and the matching `language` value.

Share the following venue information with participants:
* where it is
* what time you can arrive
* where the entrance is
* how to recognize the event (e.g. signs with the event logo)
* how to get there (e.g. by bus, how to get from the train station, and whether parking is available; if not, mention that too)

On site:
* place signs and directions in key locations (e.g. to the restrooms, specific rooms, and registration; maps are welcome)
* keep the design consistent: all signs and other information should be identifiable with the event, e.g. by using the same color scheme and/or including the event logo (especially important if more than one event is held in the same building)
* if possible, give participants the option to go outside for some fresh air during breaks
* if necessary, provide a suitable place for event staff and/or speakers to prepare, take a break, or discuss further activities
* if possible, provide a place or a contact person for participants with questions or problems related to the event

### Hardware

* provide a slide advancer/clicker
* have extra cables and adapters, spare batteries, and extension cords
* set up microphones and test sound before the event

### Slide guidelines

Please tell speakers about the slide requirements, e.g. resolution, color scheme,
audio availability, file format, etc., and how to send their slides to the organizers.
If a presentation includes company announcements or other public-facing messages, ask the PR team to review it before the event.
Ask speakers to send a PDF copy in advance; if possible, download it and keep it available offline as a fallback.

### Procurement

Using SAP?
Remember to add vendors before you issue any purchase order.

### Photography

* ask or hire someone to photograph the event; give them some time to prepare
* notes, photos, and videos from the event are good material for its history webpage

### Breaks
Remember that your audience needs regular breaks. People get tired and can't focus on presentations after 90 minutes of continuous listening.
Breaks are also useful for people working at the event.

Short breaks:
* Provide breaks of at least 10 minutes so everyone has time to get a drink and use the restroom.
* If your event is held in more than one room, attendees also need time and space to move to the room they're interested in.

Long breaks:
* Provide at least one long break during the day that can be used for lunch and rest.

If possible, give participants the option to go outside for some fresh air during breaks.

### Food & Drinks 
* Provide drinking water at a minimum.
* If you want to serve alcoholic beverages, check with the venue owners.

### Registration
* Send attendees a reminder with the venue address, entrance details, and arrival instructions.
* Prepare a backup check-in method in case the registration system is unavailable.

## For speakers

### Software

* Turn off notifications
* If possible, try to run your presentation offline
* the font is never big enough; make it bigger
