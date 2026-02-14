# Company Management

A company in ScriptMagic represents your theatre company or production organization. Companies are the top-level grouping that holds productions, people, and venues together.

## What is a company?

Companies serve as the organizational layer above [productions](../productions/creating-and-managing-productions.md):

- A company can have **multiple productions**
- People added at the company level are **available across all of that company's productions**
- Company admins have management access to **all productions in their company**
- [Venues](#venues) are defined at the company level and shared across productions

## Company information

Each company stores:

- **Name**
- **Phone number**
- **Address**
- **Notes**
- **Admins** — one or more users designated as company administrators

## Creating a company

Company creation requires [Site Admin](../collaboration/roles-and-permissions.md#site-admin) permissions. To create a company:

1. Access the admin dashboard
2. Create a new company with a name, contact info, and at least one admin
3. The company is now available when creating new productions

## Company admins

[Company admins](../collaboration/roles-and-permissions.md#company-admin) can:

- Create and manage productions under their company
- Edit company information
- Manage company-level people
- Manage [venues](#venues)
- They're automatically added as production admins on all productions within their company

A company can have multiple admins for redundancy and shared management.

## Company people

ScriptMagic uses a tiered data model for people:

1. **Company level** — Core contact information (name, email, phone, address, headshot) that's shared across all productions in the company
2. **Production level** — Production-specific information (audition notes, rehearsal conflicts, assigned characters) that's unique to each production

This means when someone works on multiple shows for the same company, you only need to maintain their contact details in one place. See [People](../productions/people.md#person-details) for more on how this two-tier system works.

## Venues

Venues represent the physical stages or theater spaces your company uses. Each venue stores:

- **Name** — the venue name (e.g., "Main Stage", "Black Box Theater")
- **Stage dimensions** — width and depth in feet or meters
- **Proscenium width** (optional) — the opening width for proscenium stages
- **Default background image** — a ground plan or stage layout that's automatically used as the background in [blocking maps](../blocking/the-blocking-editor.md)
- **Template elements** — default scenery items (e.g., wings, proscenium arch) that are pre-placed when creating a new blocking map for this venue
- **Stage direction labels** — customizable positions for stage direction labels (SR, SL, US, DS, etc.)

Venues are managed from the company management screen and can be linked to blocking maps across any production in the company.

!!! tip
    Setting up a venue with your ground plan and standard scenery saves time — every new blocking map for that venue starts with the stage layout already in place.
