# Homonym Tracker

## Overview
Create a web app that can track homonyms Treits come up with.

## Problem
Treits like to discover homonyms but it's hard to keep track of them all across family members. We need a central repository for discovered homonyms.

## Definition of Homonym
For the purose of this app, a homonym is defined in the Treit manner as:

*Two or more words having the same pronunciation but different spellings and meanings. For example, rap and wrap.*

Note that technically a homonym in English may include words with the same spelling but different meanings. These are not Treit homonyms. 

## Goals
The app should work in any web browser and store data in a central repository so all Treits can access the current list of homonyms. 

## Non-Goals
Commercialization, or expansion beyond a simple tracking app.

## Milestones
MS1 - Create web app that accepts user input and stores it in some central repository in the cloud.

MS2 - Add functionality to store words in groups of homonyms.

MS2.1 - Add functionality to display all current homonyms.

MS3 - Add User authentication

MS4 - Track users who get credit for homonyms.

MS5 - Add search capability.

## Proposed Solution
V 1.0 Create a web app that will accept and display homonyms.

## Use Cases
### Search for Homonyms
**Actor** User

**Description** - User looks up a single word and the system returns search result. Search result includes related homonyms.

### Browse Homonyms
**Actor** User

**Description** - Display a list of the current homonyms in alphabetical order.

### Add Homonyms
**Actor** User

**Description** - Add homonym sets to list. Sets may be two words or more.

### Add Users
*Actor* Admin

**Description** - Add users who can access the list.

## Test Cases
Give to Treits
Fix probelems they find.

---
## Development Tools Decisions
Amazon AWS, HTML, and JavaScript