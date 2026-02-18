# Roles & Permissions

ScriptMagic uses a role-based system to control what each person can see and do within a production. Roles determine access to features like annotation editing, cue management, and production settings.

## Production roles

When someone joins a production, they're assigned one of three roles:

### Cast

The default role for performers and general participants.

- View scripts and navigate pages
- Create and edit personal annotation [layers](../annotations/understanding-layers.md) ("Me" visibility)
- View production-level layers shared by the team

### Production Team

For stage managers, designers, technicians, and other crew members.

- Everything Cast can do, plus:
- Create and edit **Production** and **Design** visibility layers
- Create [cue layers](../annotations/understanding-layers.md#cue-layers) and [Sound DCA layers](../annotations/understanding-layers.md#sound-dca-layers)
- View and edit [cues](../annotations/cues.md)
- [Export](sharing-and-exporting.md) scripts with annotations and cues
- Access [breakdown reports](../productions/production-structure.md#breakdown-reports) (by character, by cast member, cue list, cast sheets)
- View production team notes on [structure items](../productions/production-structure.md)
- Open the [blocking editor](../blocking/the-blocking-editor.md) and manage people

### Production Admin

Full access to manage the production.

- Everything Production Team can do, plus:
- Edit production settings (name, dates, script, etc.)
- Manage [people](../productions/people.md) (add, remove, change roles)
- Manage [characters](../productions/characters.md) and [production structure](../productions/production-structure.md)
- Send [invitations](inviting-team-members.md)
- Delete the production

## Quick reference

| Capability | Cast | Production Team | Production Admin |
|---|---|---|---|
| View script | Yes | Yes | Yes |
| Personal annotations (Me layers) | Yes | Yes | Yes |
| Production/Design layers | View only | Edit | Edit |
| Cue layers & Sound DCA layers | - | Edit | Edit |
| Export with cues | - | Yes | Yes |
| Breakdown reports & cast sheets | - | Yes | Yes |
| Blocking editor & people management | - | Yes | Yes |
| Manage characters & structure | - | - | Yes |
| Edit production settings | - | - | Yes |
| Delete production | - | - | Yes |

## Administrative roles

In addition to production roles, there are administrative roles that span across productions:

### Company Admin

Manages a specific [company](../account/company-management.md) and all its productions.

- Create productions under their company
- Edit any production in their company
- Manage company-level people and settings
- Automatically added as a production admin on all company productions

### Site Admin

Full access to the entire ScriptMagic system.

- All Company Admin abilities
- Create and manage companies
- Access the admin dashboard
- Manage all users and global settings

## How roles are assigned

- **When invited**, the person sending the invitation chooses the role
- **After joining**, a production admin can change someone's role from the [People management](../productions/people.md) screen
- **Production-level overrides** — a person's role can be different in each production they belong to
