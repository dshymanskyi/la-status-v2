# Incidents

All incidents are in [_posts](https://github.com/QualityUnit/LiveAgent-status/tree/gh-pages/_posts) directory. Each post is one incident or one notification.
You can find templates (drafts) for incident and notification in directory [_drafts](https://github.com/QualityUnit/LiveAgent-status/tree/gh-pages/_drafts).

### Creating new record

You need to copy content of some template to [new file](https://github.com/QualityUnit/LiveAgent-status/new/gh-pages/_posts).
Edit it and keep only necessary content. 
Name of new file should be in format `YYYY-MM-DD-incident-title.md` 

#### Incident headers   

Header of *incident* contains following metadata:
- `layout` - value is always `post`
- `title` - short title for the incident
- `status` - actual status of the incident. Possible values are:
    - `investigating` - we (or customer) noticed some problem, we are trying found out, where is the problem
    - `update` - we are still working on fix
    - `resolved` - all is working already fine
- `severity` - possible values:
    - `degradation` - performance problems
    - `outage` - services are not accessible
- `date` - initial datetime for incident
- `resolvedDate` - *keep empty if incident is still open* 
- `clusters` - list of affected clusters. Possible values:
    - `ustx`
    - `usnj`
    - `sg`
    - `uk`
    - `de`
    - `wseu`
    - `ec1`
    - `ue1`
    - `ap1`
- `services` - possible values:
    - `admin` - Admin panel actions - Login, logout
    - `calls` - Call and video services - asterisk, stun, turn
    - `tickets` - Ticket operations as ticket filters, ticket search, loading of ticket detail
    - `emails` - Sending and receiving of emails
- `incident_states` - structured state with:
    - `status` - same possible values as main status
    - `content` - more information about actual state
    - `date` - mandatory for *update* and *resolved* status
 
#### Notification headers
 
Header of *notification* contains following metadata:
- `layout` - value is always `post`
- `title` - short title for the notification (forexample: `Scheduled maintenance`)
- `subtitle` - another information 
- `action` - value is always `notification`
- `date` - date of publishing
- `validToDate` - date of notification invalidating
