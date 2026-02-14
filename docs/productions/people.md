# People

The People management screen lets production admins manage the cast and crew for a production. You can add people manually, import from a CSV, or send email invitations.

## Adding people

There are three ways to add people to a production:

### Add manually

1. Open the People management screen for your production
2. Click **Add Person**
3. A new entry is created — fill in their details in the right panel
4. Click **Save**

### Import from CSV

For bulk imports:

1. Click **Import CSV**
2. Upload a CSV file with a **name** column (required)
3. Optional columns: email, phone, phone type, address, city, state, zip, emergency contact, emergency contact phone
4. Duplicates are automatically skipped by name

### Invite by email

1. Click **Invite**
2. Enter the person's **name**, **email** (comma-separated for multiple invitations), and **role**
3. If the email matches an existing ScriptMagic user, they're added immediately
4. If the email is new, an invitation link is sent with a 7-day expiration

See [Inviting Team Members](../collaboration/inviting-team-members.md) for more details on the invitation flow.

## Person details

Each person has two levels of information:

**Company-level fields** (shared across all productions in that [company](../account/company-management.md)):

- Full name, email, phone, alternate phone
- Pronouns, job title
- Address (street, city, state, zip)
- Emergency contact name and phone
- Headshot image
- Program bio
- Internal notes

**Production-level fields** (specific to this production):

- Audition notes
- Rehearsal notes and blackout dates
- Rehearsal conflicts
- Production-specific notes
- Role override (can differ from company role)
- Assigned [characters](characters.md)

!!! tip
    This two-tier approach means if someone is in multiple productions for the same company, their core contact information is maintained in one place.

## Profile sync

If a person updates their own ScriptMagic [profile](../account/profile-settings.md) (name, phone, etc.), you'll see a **User Profile Updated** banner on their record showing what changed. You can choose to accept the update or keep the existing company-level value.

## Removing people

To remove someone from a production:

1. Select the person
2. Click the remove button
3. Confirm the removal

This archives their production-level data and removes their access. Their company-level information is preserved, so they can be re-added later if needed.

## Searching

Use the search field at the top of the people list to filter by name.
