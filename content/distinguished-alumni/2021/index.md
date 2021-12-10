+++
type          = "event"
title         = "Fourth Annual Knight of Distinguished Alumni"
titleAlt      = "Join Us in Celebrating a Knight of Distinguished Alumni"
shortTitle    = "Knight of Distinguished Alumni"
organizer   = "Norwin Alumni & Friends Association"
# Remember to adjust eventDate to reflect the appropriate date and time.
eventComplete = true
# EventStatus Type - https://schema.org/EventStatusType
# Valid states:
# => EventCancelled
# => EventMovedOnline
# => EventPostponed
# => EventRescheduled
# => EventScheduled (Default state)
eventStatus = "EventScheduled"
eventDate     = "2021-08-19T17:30:00-05:00"
eventDoorTime = "2021-08-19T17:30:00-05:00"
eventEndDate  = "2021-08-19T21:00:00-05:00"

ticketsAvailable = true
# Remember to change ticket deadline date to appropriate deadline for RSVPs. After this date, the ticket order form will be disabled the next time the site is built.
ticketsDeadlineDate = 2021-08-05T11:59:59-05:00

date          = 2020-02-13T12:00:00-05:00
description   = ""
draft         = false
layout_hero   = true
#url         = "/distinguished-alumni"
#aliases     = ["/news/distinguished-alumni-2020","/distinguishedalumni","/alumni-dinner","/alumnidinner"]
"news/categories" = ["Alumni","Events"]

sponsors = [
  "Al & Kim Raible",
  "Andrea Kuklis",
  "The Beef Jerky Outlet, Douglas Young",
  "Belak Flowers, Inc.",
  "Berkshire Hathaway, Rebecca Parry",
  "Brittany Hodgkins from Brittany’s Scentsy",
  "Carley Painter from Kenny Ross Ford",
  "Caruthers & Caruthers, P.C.",
  "C. Harper Auto Group",
  "CFS Settlement Services",
  "Cheryl C. Cook",
  "The Colonial Grille",
  "Commercial Bank and Trust",
  "Darlene Ciocca",
  "Diane Mardell, in memory of Heather Dervin",
  "DNK Creations, Debbie Flinner",
  "Eichelberger and Sons, Inc.",
  "Feathers Artist Market & Gifts",
  "Hildenbrand Design Center, Inc.",
  "Hillcrest Intermediate PTA",
  "Interiors by Woleslagle",
  "Jacktown Ride and Hunt Club",
  "James W. Shirley Funeral Home, Inc.",
  "Kristy Gareis from Thirty One",
  "Kristy Pierce",
  "The Lamp Theatre",
  "Lisa Blair from Jim Shorkey KIA",
  "Lisa Roe from Tastefully Simple",
  "Luehm Candy Company",
  "Lynn Clark",
  "Marlene Woleslagle",
  "Maureen Kroll, RN MN JD PC",
  "Melissa Johnson Cantalupo, in memory of Jerilyn Johnson/Smiles",
  "Michelle Ann Ogg",
  "Myers, Duffy, Dansak, and Clegg LLC",
  "Norwin Chamber of Commerce",
  "Norwin Education Association",
  "Norwin Express Tours LLC",
  "Norwin Landscape and Pond Supply, Inc.",
  "Norwin Play It Forward Fund, Inc.",
  "Norwin Rotary Club",
  "Norwin Teachers Federal Credit Union",
  "The Novotnak and Barry Families",
  "Ott Funeral Home, Inc.",
  "Parkview Community Federal Credit Union, Morgan McCallister",
  "Precision Defense Services, Inc.",
  "Quinn Brewing Company",
  "Redrock Fence, Inc.",
  "Salsa Sam's Eatery",
  "Scalise/Johnson Chiropractic",
  "Sheridan Terrace PTA",
  "S&T Bank",
  "Somerset Trust Company",
  "Stratigos Banquet Centre",
  "The Stoecklein Family",
  "Tom & Paula Steiner",
  "Tyler Jones, Attorney at Law - Petrillo Jones, LLC",
  "The UPS Store, White Oak, Krissy Tapocik",
  "William Snyder Funeral Home, Inc.",
  "Woleslagle Custom Contracting"
]

[tickets]
  childAges    = "Ages 4-10"
  childPrice   = "19.00"
  price        = "39.15"
  serviceFee   = "1.15"
  guestNamesText = "Please list each guest name and their respective dinner selection, including your own, on a separate line. Dinner options are *Chicken Romano*, *Sliced Sirloin of Beef Au Ju*, or special dietary meals upon request."
  guestNamesPlaceholder = "Guest names and dinner selection (beef, chicken, or special diet). One per line."
  supportingHonoree = "Please enter the name of the honoree you're attending in support of for seating purposes. Optional."
  supportingHonoreePlaceholder = "Name of honoree"

[menu]
  [menu.main]
    name        = "Knight of Distinguished Alumni"
    identifier  = "distinguished-alumni"
    weight      = 35
    url         = "/distinguished-alumni"


[[sections.sponsors]]
  title = "Thank you to our Event Sponsors"
  content  = "The Knight of Distinguished Alumni is possible thanks to the ongoing support of businesses, families, and individuals from the Norwin community."

[sections.advertisements]
  available = true
  content   = ""

[[sections.misc]]
  title   = "Support the NSDCF"
  content = "The NSDCF will offer a Chinese auction and raffle tickets for attendees wishing to voluntarily support future endeavors of the Association."

[[sections.misc]]
  title   = "Questions"
  content = "Please [email us](mailto:alumni@nsdcf.org) with any further questions or concerns regarding the event."

[[sections.recipientsIntro]]
  title   = "Our 2021 Distinguished Alumni"
  content = "Since 1952, the Norwin School District has graduated tens of thousands of students, many of whom have gone on to change the world, touching the lives of their fellow man. The NSDCF is proud to honor the following individuals for their outstanding achievements:"

[sections.schedule_intro]
  title = "Event Schedule"

[[sections.schedule]]
  [[sections.schedule]]
    title = "Cocktails and Cash Bar"
    time  = "2021-08-19T17:30:00-05:00"
  [[sections.schedule]]
    title = "Buffet Dinner"
    time  = "2021-08-19T18:30:00-05:00"
  [[sections.schedule]]
    title   = "Distinguished Alumni Awards and Scholarship Presentations"
    content = "After Dinner"

[[sections.support]]
  title   = "Support the NSDCF"
  content = "The NSDCF will offer a Chinese auction and raffle tickets for attendees wishing to voluntarily support future endeavors of the Association."

[[sections.questions]]
  title   = "Questions"
  content = "Further questions regarding the event may be directed to <FIRST> <LAST> by [email](mailto:alumni@nsdcf.org) or by phone at <PHONE>."

[[sections.venue]]
  title   = "Event Venue"
  name    = "Stratigos Banquet Center"
  street  = "131 Colonial Manor Road"
  city    = "North Huntingdon"
  state   = "Pennsylvania"
  postal  = "15642"

[[resources]]
  name = "sponsor"
  src = "duncan-group.svg"

  [resources.params]
    title = "Duncan Financial Group"
    href = "https://duncangrp.com"

[[resources]]
  name = "featured"
  src  = "mast.jpg"

[[resources]]
  name = "2021-recipients.jpg"
  src  = "2021-recipients.jpg"

[[resources]]
  src  = "recipients/*.jpg"
  name = "recipient-photo:counter"

[[resources]]
  name  = "reservation-form"
  src   = "docs/knight-of-distinguished-alumni-reservation-form.pdf"
  title = "Reservation Form"
  [resources.params]
    icon = "pdf"
+++

On August 19, 2021, members of the Norwin community and past graduates came together in celebration of the accomplishments of eleven Distinguished Norwin Alumni, one Distinguished Friend of Norwin, and two graduating NAFA Scholarship recipients.

The Norwin Alumni & Friends Association, together with the Norwin School District Community Foundation would like to thank the community for their support and a wonderful evening.

{{< img "2021-recipients.jpg" "img--full" >}}
